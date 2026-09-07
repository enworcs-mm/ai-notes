---
title: Claude Tag（Slack）詳細調査
status: completed
date: "2026-07-02"
---

# Claude Tag（Slack）詳細調査

## 概要
2026年6月23日、AnthropicがClaude Tagを発表。AIコラボレーションの単位を「個人の会話」から「チームチャネル」へ転換するのが最大のポイント。従来は各人が自分専用のClaudeセッションを持っていたが、Claude Tagでは**1つのClaudeが固有のID・記憶を持ったチームメンバーとしてSlackワークスペースに参加**し、管理者が指定したツール・データにアクセスする。

## 主な機能
- **`@Claude`タグ付け**でタスク依頼 → 段階分解して自律的に実行 → 結果をスレッドに投稿
- **チャネル単位の記憶**: チャネルの会話履歴から文脈を蓄積し、同じ説明を繰り返す必要がない
- **アンビエントモード**: 有効化すると自発的にチャットへ参加し、進捗更新や問題フラグ立てを行う
- **マルチユーザー対応**: チャネル内の誰でも進捗を確認・引き継ぎ可能
- **権限スコープ**: 管理者がアクセス可能なチャネル・ツール・情報を指定。Claude IDごとにチャネルが限定される（例: 法務部用Claudeはエンジニアリングチャネルの記憶を持ち込めない）
- Anthropic社内では、プロダクトチームのコードの**65%がClaude Tag経由で生成**されている

## 提供条件・料金
- **対象**: Claude Enterprise / Team顧客向けベータ
- **価格**: 対象組織には導入クレジットが提供され、まず試せる形。具体的な単価は未公開
- **移行期限**: 既存の「Claude in Slack」アプリは**2026年8月3日に廃止**。管理者はClaude Tag公開から30日以内にオプトイン・移行する必要がある

## 競合との比較
- 記事内ではMicrosoft Graph、Snowflake、Databricks、Glean等の「企業コンテキスト」系プラットフォームが言及されるが、直接の機能比較は明言されていない
- Slack自体はSalesforce傘下。**Salesforce社内ではAgentforceとの競合・共食いへの懸念**が報じられている（Claude TagがSlack上でSalesforce自身のAIエージェント戦略と競合する構図）

## 評価・懸念点
- 業界的には「これまでで最も野心的なSlack AI統合」と評価。リクエスト応答型ボットから常駐アンビエントチームメイトへの転換は新しい試み
- **スイッチングコスト = 記憶の蓄積**: チャネルの文脈を蓄積するほど便利になる一方、蓄積された文脈が「乗り換えにくさ」を生む（ベンダーロックインの懸念）
- プライバシー・セキュリティはチャネル/ツール単位の権限スコープで担保する設計だが、外部レビューでの詳細な検証記事は未見

## 結論
Claude Tagは「個人アシスタント」から「チーム常駐メンバー」への発想転換で、特に長期プロジェクトの文脈保持に強み。ただしEnterprise/Teamプラン限定のベータであり、個人・副業ユースでは現時点で直接使えない。SlackのAI統合を検討する際は、既存の「Claude in Slack」からの移行期限（2026年8月3日）に注意。

## ネクストアクション
- 個人開発の副業でSlack運用がある場合、Team/Enterpriseプランへの移行が必要かどうかは要検討（現状は対象外の可能性が高い）
- 今後、料金詳細や個人向け展開のニュースがあれば追跡する

## 出典
- https://www.anthropic.com/news/introducing-claude-tag
- https://techcrunch.com/2026/06/23/anthropics-claude-tag-is-learning-your-company-one-slack-message-at-a-time/
- https://venturebeat.com/technology/anthropic-launches-claude-tag-replacing-its-slack-app-with-a-persistent-ai-teammate-that-learns-monitors-and-works-autonomously
- https://fortune.com/2026/06/23/anthropic-claude-tag-virtual-employee-tool-slack/
- https://cryptobriefing.com/salesforce-anthropic-claude-tag-concerns/
