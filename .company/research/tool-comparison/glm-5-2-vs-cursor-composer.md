---
title: "GLM-5.2 vs Cursor Composer — コーディングモデル比較"
category: tool-comparison
status: completed
created: "2026-06-23"
tags: [coding-llm, glm, cursor, open-weights, moe]
---

# GLM-5.2 / Cursor Composer 調査メモ

> 2026-06-23 のAIニュースで話題になった2つのコーディングモデルを調査。
> 方向性が異なる（コスト重視のオープンモデル vs 速度特化のプラットフォーム一体型）ため、競合というより棲み分け。

---

## 1. Z.ai GLM-5.2 — 「GPT-5.5超え＆1/6コスト」

### 基本スペック
- 中国 Z.ai のオープンウェイトモデル
- **753B パラメータ／MoE（Mixture-of-Experts）**
- **MITライセンス**（Hugging Face 公開・商用利用可）
- **コンテキスト 1M トークン**（前世代 GLM-5.1 の20万から5倍）
- リリース: 2026-06-13〜16

### 「GPT-5.5超え」の実態
- **FrontierSWE**（長期コーディングベンチ）で GPT-5.5 を**約1%上回る** ← 僅差で抜いた、が正確
- オープンソース勢では長期コーディングで**1位**
- Terminal-Bench 2.1: **81.0** / SWE-bench Pro: **62.1**

### コスト（本命）
| | 入力 | 出力 | 合計/1Mトークン |
|---|---|---|---|
| GLM-5.2 | $1.40 | $4.40 | **$5.80** |
| GPT-5.5 | $5.00 | $30.00 | $35.00 |

→ **約6分の1**。1M長文時はトークンあたり計算量を約2.9倍削減する工夫あり。
公式サブスクは月$12.60〜（本領はAPI/セルフホスト運用）。

### 注意点
- 優位はあくまで**僅差**＆コーディング特化ベンチ中心。汎用タスクで同様とは限らない

---

## 2. Cursor Composer — 「4倍速」のエージェント特化LLM

### 基本スペック
- Cursor 初の**自社製コーディングLLM**（Cursor 2.0 の目玉）
- **MoE + 強化学習（RL）**で構築
- Cursor プラットフォーム一体型（単体API提供ではない）

### 「4倍速」の実態
- 生成速度 **250 トークン/秒**
- 比較基準は **Claude 4.5 Sonnet（約63 tok/s）≒ 約4倍**、高速推論モデル比でも約2倍
- ほとんどの操作を**30秒以内**で完了

### 特徴
- **エージェント前提の学習**: セマンティック検索・コード編集・ターミナル・テスト実行など実ツールを使う環境で訓練
- 評価は社内ベンチ **"Cursor Bench"** ＝正解率だけでなく**既存の抽象化・スタイル・設計規約への準拠**も測る

### 注意点
- 賢さより**速度トレード**寄り（"Trading Smarts for Speed" と評する分析あり）。複雑な推論ではフロンティアモデルに譲る場面も
- Cursor 内専用

---

## 結論
- **GLM-5.2** = "オープンで安い、長期コーディングで僅差トップ" → **コスト重視・セルフホスト派**向け
- **Cursor Composer** = "Cursorの中で爆速で回るエージェント特化" → **Cursorユーザーの開発体験**向け
- 用途が違うので併用も現実的。コストを抑えたいバッチ/長文処理は GLM-5.2、対話的な高速開発は Composer。

## ネクストアクション
- [ ] GLM-5.2 を実際にAPIで触ってコスト感とコーディング品質を体感（セルフホスト可否も確認）
- [ ] Cursor 2.0 / Composer を普段の開発フローで試用し、速度と品質のトレードを評価
- [ ] 数週間後にベンチ更新（GLM-5.x / 主要モデルの追従）を再チェック

## 出典
- VentureBeat: [GLM-5.2 beats GPT-5.5](https://venturebeat.com/technology/z-ais-open-weights-glm-5-2-beats-gpt-5-5-on-multiple-long-horizon-coding-benchmarks-for-1-6th-the-cost)
- Z.AI公式ドキュメント: https://docs.z.ai/guides/llm/glm-5.2
- VentureBeat: [Cursor Composer](https://venturebeat.com/ai/vibe-coding-platform-cursor-releases-first-in-house-llm-composer-promising)
- TechTalks: https://bdtechtalks.com/2025/10/31/cursor-composer-coding-llm/
