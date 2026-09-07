---
title: フロンティアモデル競争の勢力図（2026年7月時点）
status: tracking
date: "2026-07-02"
last_updated: "2026-09-07"
---

> **継続追跡ノート**: このファイルは一回きりの調査ではなく、関連ニュースが出るたびに追記・更新していく前提のノート。追跡トピック: Fable 5/Mythos輸出規制、GPT-5.6 Sol、フロンティアモデル各社の戦略、中国AI動向、日本のAI戦略。git pull時の新着ニュースにこれらの関連トピックが含まれる場合、新規ファイルを作らずこのファイルに追記すること。

# フロンティアモデル競争の勢力図（2026年7月時点）

## Claude Fable 5 輸出規制の顛末
- 6月12日: Amazon研究者が「特定プロンプトでFable 5からサイバー攻撃に使える情報を引き出せる」と指摘。Amazon CEOアンディ・ジャシー氏とホワイトハウスの協議を経て米商務省が輸出規制を発動、Fable 5・Mythos 5をオフライン化
- 6月30日: トランプ政権が規制解除。条件は①セキュリティリスクの積極検知・対処、②政府とのプロトコル協働、③悪意ある活動の報告
- 7月1日: 全プラットフォームでグローバルに再開。ただし「政府が今後も一定の関与を続ける」形での決着、との指摘あり
- 【2026-07-08追記】Anthropicは Amazon・Microsoft・Google他「Glasswing」パートナーと協力し、ジェイルブレイクの重大度を評価する業界横断的なフレームワークを提案。再開条件（セキュリティリスク検知・政府協働・悪用報告）の具体化として、7/2にサイバーセキュリティ対策の詳細も追加公表された

## Anthropicのインフラ多様化戦略【2026-07-03追記】
- Google・Broadcomと2027年以降に複数ギガワットの次世代TPU容量をオンライン化する新協定を締結（大部分は米国内配置）。2025年11月の50億ドル米国インフラ投資コミットメントの延長で、Anthropic「最大規模のコンピュート投資」とのこと
- 背景: 実績売上高が前年約90億ドル→300億ドル超に急拡大。年間100万ドル以上を支出する顧客数が2ヶ月で500社→1,000社超に倍増するなど、指数関数的成長への対応が急務
- AWSとの関係は継続（引き続き「主要クラウドプロバイダー・トレーニングパートナー」、Project Rainierも継続）。Anthropicは**AWS Trainium・Google TPU・NVIDIA GPUを併用するハードウェア多様化戦略**を採用し、ワークロードごとに最適なチップへ振り分ける方針
- ソース: https://www.anthropic.com/news/google-broadcom-partnership-compute

### Series H資金調達【2026-07-08追記】
- Altimeter Capital・Dragoneer・Greenoaks・Sequoia Capital主導のSeries Hで650億ドルを調達。ポストマネー評価額9,650億ドル(2026年5月28日発表)。Capital Group・Coatue・D1 Capital Partners等も参加
- ランレート収益は47億ドル超。資金使途は①安全性・解釈可能性研究、②計算容量の拡大、③製品・パートナーシップのスケーリング
- Amazon・Google・Broadcom・SpaceXとの新たな計算容量契約でクラウドプラットフォーム間の可用性をさらに拡大
- ソース: https://www.anthropic.com/news/series-h

### IPO準備：SECにS-1ドラフトを秘密裏に提出【2026-07-23追記】
- 2026年6月1日、AnthropicがIPOを見据えたForm S-1の草稿をSECに機密提出したことが判明。1933年証券法135条に基づく発表で、有価証券の売却提案ではなく法定通知の位置付け
- 現時点では提供株数・価格は未定。「市場条件その他の要因次第」でSEC審査完了後にIPOを実施する選択肢を確保している段階
- Series Hでの評価額9,650億ドル・ランレート収益470億ドル超という急成長を踏まえると、上場準備は資金調達の次のステージとして自然な流れ。OpenAIとの上場競争（どちらが先に上場するか）にも注目
- ソース: https://www.anthropic.com/news/confidential-draft-s1-sec

**市場の期待感【2026-07-23調査】**
- ターゲット時期は2026年10月、NASDAQ上場でGoldman Sachs・JPMorgan・Morgan Stanleyが主幹事。調達額は600億ドル超の見込み
- 評価額期待は「1兆ドル超えが投資銀行のベースケース」との報道多数。SpaceXの上場級インパクトに例えられる
- FutureSearchの分析予測（中央値）: 初日時価総額1.10兆ドル（前回ラウンド比+14%）、90日後1.09兆ドル。二次市場では1.05〜1.15兆ドルで取引
- Wall Street反応は総じて好意的（「AI狂騒曲を裏付けた」との評）。ただし「OpenAI(評価額8,520億ドル)より高い9,650億ドルは割高では」との声に対し、「ランレート収益470億ドルに対する倍率は約20.5倍でOpenAIより約4割安い」との反論も
- リスク要因: テック株全体の調整（rout）が起きればIPOを延期・撤回する可能性も指摘されている（24/7 Wall St.）
- ソース: https://cryptobriefing.com/anthropic-targets-ipo-by-october-2026-after-965b-valuation/ , https://m.investing.com/news/stock-market-news/instant-view-anthropic-ipo-filing-ratifies-wall-streets-ai-obsession-4720246 , https://247wallst.com/investing/2026/06/23/will-the-tech-stock-rout-force-anthropic-to-pull-its-ipo/

**個人投資家の動き【2026-07-23調査】**
- 個人投資家の関心は非常に高く、「上場前企業としては過去最高クラスの検索関心度」との報道。Goldman Sachsが主幹事を務め、リテール配分は20%超になる見込みとの観測もあり、需給は買い方優勢
- ただし直接アクセスは限定的：上場するまで個人は直接購入不可。浮動株比率もOpenAI同様5〜10%程度にとどまる見込みで、供給が絞られる分、上場直後に株価が急騰する可能性も指摘される
- Forge Global・EquityZen・Hiive等のセカンダリー市場経由で適格投資家(accredited investor)は購入可能だが、Anthropic・OpenAIともこうした取引の取り締まりを強化中で、無効化されるリスクがある
- 間接的な投資先としては **Amazon**（出資額約130億ドル、Anthropicの15〜20%を保有、Q1だけで税引前167億ドルの評価益を計上）と **Alphabet**（約14%保有、直近評価額で約1,350億ドル相当）が既に大株主。1.2兆ドル評価なら Amazonの持分価値は1,800億〜2,400億ドル規模との試算も
- ソース: https://www.investmentnews.com/equities/anthropic/266640 , https://finance.yahoo.com/markets/stocks/articles/buy-pre-ipo-shares-anthropic-202954054.html , https://www.fool.com/investing/2026/07/05/anthropic-could-be-a-1-trillion-ipo-this-fall-thes/

## 【2026-08-17追記】8月の大型アップデートまとめ

### Anthropic：Opus 4.7リリース＋事業規模がさらに拡大
- **Claude Opus 4.7が一般提供開始**（8/8）。ソフトウェアエンジニアリング領域で前世代Opus 4.6から明確に進歩。ビジョン能力も画像解像度が3倍以上（最大2,576px）に向上。あるコーディングベンチマークでは「Opus 4.6が解けなかった93タスク中4つを新たに解決」。価格は据え置き（入力$5/出力$25、100万トークンあたり）。全製品・API・Bedrock・Vertex AI・Microsoft Foundryで利用可能。VentureBeatは「最強汎用LLMの座をわずかに奪還」と評（ソース: https://www.anthropic.com/news/claude-opus-4-7 ）
- **Claude Sonnet 5の導入価格（入力$2/出力$10、100万トークンあたり）が恒久化**（8/16）
- ランレート収益は300億ドル超で継続確認（2025年末の約90億ドルから急増）。年間100万ドル以上の顧客は1,000社超で2ヶ月足らずに倍増
- Blackstone・Hellman & Friedman・Goldman Sachsと共同で中堅企業向けエンタープライズAIサービス新会社を設立（8/11）
- Gates Foundationと提携し、グローバルヘルス・ライフサイエンス・教育・経済的流動性向けに4年間で2億ドル（助成金＋Claude利用クレジット＋技術支援）をコミット（8/17）
- Google CloudとのTPU活用を拡大、最大100万基のTPUを計画。2026年中に1ギガワット超のキャパシティ稼働見込み
- EU AI Act対応でテキストへの透かし（ウォーターマーク）導入を発表（8/11）
- Tino Cuéllar氏がChief Global Affairs Officerに就任（8/4）

### OpenAI：GPT-5.6ファミリーが正式ロールアウト
- **8/6、GPT-5.6（Sol/Terra/Luna）が正式にChatGPTへ展開**。無料・Goユーザーのデフォルトモデルは旧GPT-5.5からLunaに切り替え、無料ユーザーのテキストチャット制限も撤廃（ChatGPTは週間ユーザー10億人超）
- Sol向けに処理速度を最大14倍にする「Ultrafast」モードを発表（8/13）
- Lunaのトークン単価を80%引き下げ——価格を主戦場にした競争が本格化（AnthropicはOpusで性能訴求を継続、値下げなし）
- サイバーセキュリティ特化モデル「GPT-5.6-Cyber」も投入。高度サイバータスクで95%完了率を主張しつつ、社内評価で「重大なサイバー能力の可能性を排除できない」とも公表（Preparedness Framework）
- 122億ドルの新規資金調達を発表、DevDay 2026を9/29サンフランシスコで開催予定。週間アクティブユーザー9億人超、加入者5,000万人超
- 70億ドル規模の従業員株式買い戻しを実施（評価額8,520億ドルで据え置き）
- Dali Rajic氏（前Wiz社長）をChief Revenue Officerに任命（前任者は9ヶ月で退任）

### 中国勢・その他プレイヤーがさらに肉薄
- **Moonshot AI「Kimi K3」**：史上最大のオープンソースモデルと報じられ、米トップシステムに匹敵
- **DeepSeek**：フラッグシップ「DeepSeek-V4-Pro」とClaude Code対抗のオープンソースエージェントハーネス「DeepSeek Harness v0.1」を同時公開。V4はOpus 4.7・GPT-5.5の約1/6のコストでほぼ最先端性能
- **Alibaba「Qwen3.8-Max」**：2.4兆パラメータMoE。エージェント型コンピュータ操作ベンチマークでGPT-5.6 Sol MaxとFable 5を上回ると主張
- **SpaceXAI「Grok 4.6」**：Kimi K3を上回りGPT-5.6 Solに並ぶ世界3位相当（Artificial Analysis基準、$0.84/タスク）
- **Z.ai「GLM-5.2」**：長期コーディング系ベンチマーク複数でGPT-5.5を上回りつつコストは約1/6。ただしオフェンシブサイバー・デュアルユース生物学タスクでの拒否率がゼロという安全性ギャップも指摘される
- スタンフォード2026 AI Indexは「フロンティアモデルは本番運用の3回に1回失敗し、監査もより困難に。ラボの透明性は低下、ベンチマークは飽和が速い」と報告——性能競争の裏で品質・監査性の課題が表面化

### Google：Gemini 3.5/3.7とAI Modeが規模で先行
- AI Modeが月間10億ユーザーを突破（1年未満で達成、クエリは四半期ごとに倍増）。デフォルトモデルをGemini 3.5 Flashに統一
- Gemini 3.7 Flashをコーディング・エージェント向けに投入、導入価格50%引き下げ（8/13）
- **組織面の動揺**: Jeff Dean氏（Googleで最も影響力のある幹部の一人）がSanjay Ghemawat・Quoc Le・Oriol Vinyalsら複数の著名研究者とともに退社し、独自スタートアップを設立すると報道（8/5）。7月時点で既に指摘されていた「Gemini 3.5 Pro遅延・DeepMind人材流出」の流れが続く形
  - 【8/17深掘り】新会社名は**「Discovery Loop」**（Public Benefit Corporation）。CEOはJeff Dean。共同創業メンバーはSanjay Ghemawat（Googleシニアフェロー兼エンジニア）、Quoc Le（Google Brain創設メンバー）、Oriol Vinyals（Google DeepMindシニアリサーチサイエンティスト）——いずれもGoogle/DeepMindのAI研究を長年牽引してきた中核人材
  - 事業内容: AIを使って科学研究そのものを加速させることに特化。大規模計算資源を使い「数千の実験を同時並行実行」する自動化研究プロセスを目指す。AI自身を改善する「再帰的自己改善」技術にも関心
  - 資金調達: Radical Ventures・Khosla Venturesが主導、Kleiner Perkins・Lightspeed・Doerr Capitalも参加。**Alphabet自身も出資**しており、完全な決別ではなく資本関係は維持
  - Deanの退社理由（本人弁）: 「遅く逐次的な人間の反復（slow, sequential human iterations）」が科学研究の進捗を妨げる最大のボトルネックであり、AIによる自動化で実験の量と質を同時に高められると主張
  - Googleへの影響: Deanは1999年入社の27年選手で、検索インフラ構築からGeminiまでGoogleの技術的中核を担ってきた人物。今回の離脱は単なる一人の退社ではなく、Google Brain創設メンバー・DeepMind中核研究者を含む「AI研究のコア人材ごとの流出」という点でインパクトが大きい
  - ソース: https://techcrunch.com/2026/08/05/jeff-dean-and-other-top-ai-researchers-are-leaving-google-to-launch-their-own-startup/
  - 【8/17さらに深掘り：Google側のその後の動き】単なる一研究者の退社ではなく、**DeepMind自体の大規模組織再編**だったことが判明
    - **Demis Hassabis氏（DeepMind創業者・CEO）も同時に役職を退任**し、チェアマン職＋Alphabet本体のチーフサイエンティストという名誉職寄りのポジションに移行。日々の経営執行権限を手放す
    - 後任は置かず、**Koray Kavukcuoglu氏（DeepMind長年の研究者・CTO）がSenior Vice Presidentに昇格**し、Sundar Pichai直属に。エンジニアの間では「権限がロンドン（DeepMind）からマウンテンビュー（Google本体）へシフトした」「DeepMindの独立性が徐々に失われている」との受け止め
    - Sundar Pichaiのコメント: "After an incredible 27-year run, Jeff Dean is at a moment where he wants to try something new, and we're excited to support him in that."（対立ではなく円満送り出しの姿勢）
    - **GoogleはDiscovery Loopの創業投資家＆クラウドパートナーとして出資**——少なくとも初年度分の計算資源を提供する関係を維持。人材は失うが資本・インフラの結びつきは切らない設計
    - **Alphabet株価は発表後約4〜5%下落**
    - **背景にあった組織の疲弊（Fortune報道）**: Gemini 3.5 ProはI/O発表後、6月・7月と2回連続で納期を逃す。エンジニア証言では「AIコーディング機能の優先順位が低かった」ことが一因で、コーディング領域でOpenAI・Anthropicに後れを取った。年60時間超の残業によるバーンアウト、Hassabisを「姿の見えないリーダー」とする批判、6月だけでNoam Shazeer氏（OpenAI転職）・John Jumper氏（Anthropic転職）が流出するなど人材流出が続いていた。4月署名のペンタゴン契約に対し従業員580名超が抗議書に署名し、ロンドン拠点で労組結成の動きも発生
    - **総括**: Google自体はチップ・クラウド・アプリ層を垂直統合できる構造的な強みを保持するものの、モデル性能競争そのものではAnthropic・OpenAI・xAI・Metaの後塵を拝しているとの評価。Jeff Dean退社は「DeepMindの独立性低下・権限のGoogle本体回帰」という大きな組織再編の一部として起きた
    - ソース: https://fortune.com/2026/08/10/how-stalled-models-missed-deadlines-and-staff-burnout-lead-to-the-unraveling-of-googles-deepmind/ , https://www.cnbc.com/2026/08/05/google-chief-scientist-jeff-dean-leaving-company-after-27-years.html

### レイオフ・労働市場への影響が継続
- 2026年に入りAIを理由に挙げた米テック企業のレイオフは約14万件規模に拡大（Amazon・Oracle・Meta・Microsoftだけで約5万件）。PayPalは2〜3年で全従業員の約20%削減を計画
- 一方でAnthropic・OpenAIなどAI専業企業は採用を急拡大し、流出人材の受け皿になっている

## 【2026-09-07追記】8月下旬〜9月上旬まとめ

### OpenAI：GPT-6 Astra を投入（9/3）――「AGI時代」を掲げる大型ジャンプ
- GPT-5.x系の細分化リリースが続いていたが、**約1年半ぶりの世代ジャンプ「GPT-6 Astra」を9/3出荷**。VentureBeatは「Welcome to the AGI era」と報道。Greg Brockmanは「明確な瞬間ではなくグレーな移行」「体験的にAGI時代に入った」という経済的現実ベースの論拠を提示
- **位置づけはコンピュータ操作（computer use）モデル**。ブラウザ・スプレッドシート・デスクトップアプリ・KiCad/FreeCADなど専門ツールまで人間と同じインターフェースで横断操作し、文書・スプレッドシート・プレゼンをテンプレート/指示に従って完成させる。マルチステップワークフローの自律遂行が主眼
- ベンチマーク（OpenAI提示、ハーネス構成込み）: OSWorld 2.0 72.6%（Solの65.7%から改善、タスク時間も短縮）、FrontierMath Tier 4 v2 97.6%（飽和）、ARC-AGI-3 ~99%（飽和、自社provider adapter harness下）、ExploitBench 100%、DeepSWE v1.1 74.1%、GPQA Diamond 96%、BenchCAD 95.9%
  - 批判: ①ARC-AGI-3の高スコアは「モデル単体ではなくエージェント構成込みの数値」で、NVIDIAのAVO技術はClaudeでも100%を出しており指標として割り引くべき、②**経済価値ある実務を測るGDPvalの結果が公開されていない**――AGI主張の裏付けとして重要なのに欠落
  - 思考過程を隠す「opaque recurrence」技術への透明性批判は継続（9/5ニュース）
- 価格（API、100万トークン、Standard/Fast）: 入力 $10/$20、出力 $50/$100、キャッシュ入力 $1。**Fable 5と同水準の最上位価格帯**。OpenAIが「積極価格のラダー型ファミリー」路線からハイエンドで価格を上げてきた点は転換
- アクセス: まず信頼できる防御者向けプログラム「Daybreak（Blue）」の企業に限定提供、その後ChatGPT Plus/Pro/Business/Enterprise・API・AWS Bedrock・Azureへ順次。**サイバー能力がPreparedness FrameworkのCritical閾値到達の予備的証拠**（8/18公表）――評価中に未知の脆弱性2件を自律発見。「政府審査→条件付き段階提供」プロセスがGPT-6でも踏襲された
- 関連: DevDay 2026を9/29サンフランシスコ開催。「Path to Astra: critical capabilities and frontier safeguards」等の安全文書も同時公開

### Anthropic：インフラ拡大・提携ラッシュ、IPO準備が公に
- **Google・Broadcomとのコンピュート提携をさらに拡大**（9月発表）。2025年11月の$50億米国インフラ投資の一部で、**複数ギガワット規模の次世代TPU容量を2027年から順次オンライン化**（一部報道では2026年中に1GW超・最大100万TPU規模の計画）。AWSは引き続き「主要クラウド・トレーニングパートナー」でProject Rainierも継続。Trainium＋TPU＋NVIDIA GPUのマルチベンダー多様化戦略は不変（ソース: https://www.anthropic.com/news/google-broadcom-partnership-compute ）
- **S-1のSEC機密提出が正式アナウンス**（8/21に一次ソース公表、提出自体は6/1）。ランレート収益$300億超、年$100万超支出の法人顧客1,000社超を再確認。IPOターゲットは2026年10月・NASDAQ・評価額1兆ドル超という観測は継続（詳細は上記「IPO準備」セクション参照）
- **Gates財団と提携**（8/17）: グローバルヘルス・生命科学・教育・経済的流動性向けに4年で$2億（助成金＋Claudeクレジット＋技術支援）
- **Economic Futures Research Fund**（$2億）の研究アジェンダ公開。AIの経済的影響への社会的介入策の外部研究を支援。Claude向け「Anthropic Economic Index」コネクタも公開
- **Salesforceと「Claudeforce」**（8月下旬）: CRM全体をClaude内に統合、「Salesforceアプリ不要」を標榜。エンタープライズ配信での攻めの一手
- Blackstone・Hellman & Friedman・Goldman Sachsと中堅企業向けエンタープライズAIサービス新会社を設立（8/11）
- 【モデル】Claude Opus 4.7が8/8一般提供（前掲8/17追記参照）。ただしDeepSWEリーダーボードで「Claude Opusがベンチマークの抜け穴を利用」と指摘され首位はGPT-5.5との報道も（8月）

### xAI（SpaceXAI）：Grok 4.6 で世界3位に浮上
- **Grok 4.6**がArtificial AnalysisでKimi K3を上回り、**GPT-5.6 Solと並ぶ世界3位相当**（$0.84/タスク）。長時間エージェント挙動が強化。フロンティア上位4〜5モデルの性能収束がさらに進む
- 月額$120の永続エージェント「Grok Bot」early betaも公開――日常アプリ上で継続的にタスク実行する「デジタル同僚」路線

### 業界再編：Nvidia が Hugging Face を $129億で買収（9/3確認）
- Nvidiaが**Hugging Faceを$12.9Bで買収**すると正式確認（設立以来の調達総額は約$3.95億）。月間1,800万開発者・300万モデル・25万データセットをホストするオープンモデルの結節点をNvidiaが押さえる
- Jensen Huang「Hugging Faceは全AIエコシステムのためのオープンプラットフォームであり続ける」、開発者は任意のモデル/フレームワーク/クラウド/チップを選べるとし、Nvidiaチップ利用は必須にしないと明言。CEO Clem Delangueも協力関係を肯定
- 狙い: ハードウェア優位を背景にしたAIエコシステムの統制、遊休容量のエンタープライズ販売、オープンモデル戦略の強化。規制当局の反応は現時点で報道なし
- **「モデルよりハーネス（実行基盤）が主役」**という論調が強まっている（Nvidiaのデモ、DeepSeek Harness、Nvidia NeMo Switchyard/Nemotron等）。モデル単体の賢さから「エージェント構成・オーケストレーション・配信」へ主戦場が移る流れが加速

### Google/DeepMind：ロボティクスと科学AIにシフト、モデル競争では守勢
- **Gemini Robotics 2 / Gemini Robotics ER 2**発表。ロボットの「全身知能（whole body intelligence）」「具現化推論」に注力
- WeatherNext 2 / WeatherNext Cyclonesをオープンソース化（サイクロン予測でSoTA、警報を1日前倒し）。DOEとの科学AI「Genesis」、数学・理論計算機科学での成果公表
- 小型・効率モデル（Gemini 3.6 Flash / 3.5 Flash-Lite / Flash Cyber）でエージェント用途のコスパを訴求。フラッグシップProの苦戦とDeepMind組織再編（Jeff Dean離脱→Discovery Loop、Hassabis役職退任）は前掲8/17追記のとおり

### 安全性・ガバナンス面の底流
- OpenAI・Anthropic・Google・Microsoftら**100社超が「rogue AI」対策を求める公開書簡**に署名（8/27）
- ただし「主要ラボの多くがrogue model封じ込め計画を公開・実証していない」との調査指摘（TechCrunch 8/22）
- OpenAIは顧客データを保持せず不正監視する「Private Safety Processing / Zero Data Retention」をプレビュー（Anthropic対抗）。Google DeepMindはFrontier Safety Framework強化＋世界初のダブルブラインドAI評価をパイロット
- 対世論: 「AIの日常利用に期待より懸念」が2021年37%→2026年52%に上昇（米調査）。Satya Nadellaも「AIが産業を空洞化しうる」と警告。2026年に入りAI理由のテックレイオフは約14万件規模

## Fable 5 の料金体系
- API: 入力$10 / 出力$50（100万トークンあたり）。Anthropicの一般提供モデルで最高値
- サブスク（Pro/Max/Team/一部Enterprise）: 7/7まで追加料金なし（週間利用上限の50%としてカウント）、7/7以降は従量課金（Usage Credits）に移行
- Freeプランでは利用不可

## GPT-5.6 Sol vs Claude Fable 5
| 項目 | GPT-5.6 Sol | Claude Fable 5 |
|---|---|---|
| 価格（100万トークン） | 入力$5 / 出力$30 | 入力$10 / 出力$50 |
| Terminal-Bench 2.1 | 88.8%（Ultra版91.9%） | 83.4% |
| 提供状況 | ~~政府審査済みの限定プレビューのみ~~ → **2026-07-09に一般提供開始**（下記追記参照） | グローバル一般提供中 |

- 戦略の違い: Anthropicは「一点集中の最高性能モデルを全員に一律価格で」。OpenAIは「ラダー型ファミリーを積極価格で、ただしアクセス制限」
- ~~Solは性能・価格で優位だが提供制限あり~~。**7/9に制限解除・一般提供へ移行**（下記参照）。Fable 5にとって性能・価格の両面で強力な対抗馬に

### GPT-5.6 Sol プレビュー公開【2026-07-08追記】
- OpenAIがGPT-5.6シリーズのプレビューを開始。Sol(フラッグシップ)・Terra(バランス型)・Luna(高速・低コスト)の3バリアント構成
- SolはTerminal-Bench 2.1でSoTA。コーディング・生物学・サイバーセキュリティで能力向上。7月中にCerebras上で最大750トークン/秒の提供を予定
- 現状は約20組織限定のプレビューのみ(上表の「政府審査済みの限定プレビュー」を裏付け)
- ソース: https://openai.com/index/previewing-gpt-5-6-sol/

### GPT-5.6 一般提供開始【2026-07-10追記】
- **2026-07-09、GPT-5.6がChatGPT・ChatGPT Work・Codex・APIで一般提供開始**（グローバルロールアウトは24時間かけて展開）。約1ヶ月弱で「政府審査済み限定プレビュー」から一般提供へ移行し、Fable 5と同じ「グローバル一般提供中」のステータスに並んだ
- API価格（100万トークン、入力/出力）: Sol $5/$30、Terra $2.50/$15、Luna $1/$6。上表の「Sol $5/$30」を裏付け
- 新機能「Ultra」設定: 最大4エージェントを並列調整して複雑タスクを高速処理（デフォルトで4並列）
- 一般提供前に「これまでで最も広範な評価期間」（人手によるレッドチーム+大規模自動テスト）を実施したとする
- 英AI Security Institute (AISI) が公開前にSolをテストし、system cardに貢献した旨を英国議会議員が言及（政府関与の継続を示唆）
- ソース: https://openai.com/index/gpt-5-6/

### OpenAI×Broadcom「Jalapeño」推論チップ【2026-07-08追記】
- OpenAIとBroadcomがLLM推論最適化チップ「Jalapeño」を共同発表。OpenAI初のIntelligence Processorで、2026年末に初期展開予定
- 複数世代にわたるコンピュートプラットフォーム構想の第一弾。Anthropicの「マルチベンダー（AWS Trainium・Google TPU・NVIDIA GPU）多様化」戦略に対し、OpenAIは自社製シリコンで垂直統合を進める動き
- ソース: https://openai.com/index/openai-broadcom-jalapeno-inference-chip/

## 高性能化レースの展望
- 2026年はAI史上最も密なリリースサイクル（2〜4月だけで7つのフロンティアモデル）。GPT-6・Claude 5(社内コード名Fennec)・Gemini 4のような大型ジャンプは噂止まりで、各社ともGPT-5.x/Claude 4.x系の細分化リリースに切り替え
- ベンチマーク性能は各モデルとも僅差に収束（Intelligence Index 57〜61程度）。差別化の主戦場は「知能そのもの」から「エージェントとしての実務遂行力」（コーディング・長時間タスク自律実行・マルチエージェント連携）に移行
- 新変数: 「政府による提供制限」が性能とは別にレースの勝敗を左右する時代に（Fable 5・GPT-5.6の例）。ただし制限は恒久的ではなく、Fable 5(7/1)・GPT-5.6 Sol(7/9)ともに1ヶ月弱で一般提供へ移行しており、「政府審査→条件付き一般提供」がフロンティアモデルの標準的な立ち上げプロセスになりつつある
- 【2026-07-10追記】GoogleのGemini(Deep Think搭載上位版)が国際数学オリンピック(IMO)で金メダル水準を達成(6問中5問正答)。純粋な推論・数学能力の指標としては依然頂点を争っており、「知能そのもの」の競争も並行して続いている
- 次の大型モデル時期: Geminiは年1回ペース（1.0→2.0→3.0）が続けば2026年後半〜2027年初頭に大型版の可能性。GPT/Claudeの次期大型版時期は不透明
- xAI共同創業者は、AIが自律的に自己改良する「再帰的自己改良ループ」が2027年上半期にも出現し得ると予測

## Google/Microsoft/Apple/Amazonの立ち位置
- **Google**: 技術的にはGemini 3.1 Proが最強クラスとの評価もあるが、「ベンチマークで勝ってもナラティブで負けている」。理由は①2026年のAI採用の主戦場であるコーディング領域に存在感がない（開発者はGPT-5.5・Claude Codeを使う）、②Googleの関心が検索・Android・広告など消費者帝国全体に分散しており本気度が伝わりにくい、③Brinのコーディングチーム発表なども「意思表示止まりで未出荷」。強みは億単位ユーザーへの配信網
- **Microsoft**: OpenAI・Anthropic・自社の3正面待ち戦略。OpenAIに約$1,350億相当出資しつつCopilotにClaudeを組み込み、自社製MAIモデル（Polaris等）も投入。「1社依存を薄める主権確保」の動き。OpenAIとの関係解消ではなく段階的疎結合
- **Apple**: 自社モデル開発は苦戦（Siriの複雑クエリ失敗率は約33%）。年間$10億規模でGoogleからGemini 3を調達しSiriに搭載。「モデルは作らず勝ち馬に乗る」ポジション
- **Amazon**: 自社汎用フロンティアモデルでは戦わず、Anthropicへの巨額出資（追加$50億、将来最大$200億）+ AWS Bedrock経由の配信・インフラ提供に徹する「胴元」ポジション。Project Rainierで大規模計算クラスタを共同構築
- まとめ: モデルそのものを作って戦っているのは実質OpenAI・Anthropic・Googleの3社。Microsoft・Apple・Amazonは「モデルを作る側」ではなく「どのモデルに乗るか・どう配信するか」で勝負。競争の主戦場は「一番賢いモデル」から「一番安く・広く・自律的にタスクをこなせる形で届けられるか」にシフト
- 【2026-07-09追記】Google Search が「Search agents」時代に突入。AI Mode利用者は1年で10億人超・四半期ごとにクエリ倍増。Gemini 3.5 FlashをAI Modeの新デフォルトに設定し、25年ぶりにSearch box自体を刷新。情報収集エージェントやAgentic Coding（検索内でのミニアプリ生成）にも進出しており、「検索という配信網の強み」を軸にコーディング領域にも侵食し始めている点が従来の弱点認識を変えつつある（ソース: https://blog.google/products-and-platforms/products/search/search-io-2026/）
- 【2026-07-23追記・トーンダウン】上記の強気な流れと対照的に、フラッグシップの**Gemini 3.5 Proが数ヶ月単位で延期**。5月のGoogle I/Oで6月ローンチ予告も、コーディング性能・トークン効率・長時間の多段階推論が社内目標未達。6月末にプログラミング関連データを増やしファインチューニングするも改善せず、現在はトレーニングプロセスを再スタート中とされる。現状はVertex AIの限定エンタープライズプレビューのみ。7/16にAlphabet株が約4.4%下落し時価総額約2,000億ドル消失。一部報道では「DeepMindの人材流出が深まっている」という組織面の課題も指摘。「AI Mode向けFlashは好調・フラッグシップProは苦戦」という二極化が鮮明に（ソース: https://www.fool.com/investing/2026/07/19/alphabets-gemini-35-pro-is-late-and-the-stock-is-s/ , https://the-agent-report.com/2026/07/google-gemini-3-5-pro-delayed-july-2026/）
- 【2026-07-23追記】Google、Metaへのモデルアクセスを制限。MetaがGeminiモデルへの計算リソース追加を要求したが供給しきれず。「計算資源がAI競争の真のボトルネック」を象徴する出来事

## 中国の動き

### モデル面
- オープンウェイトAIのトップ5枠中4つを中国勢が占有: GLM-5（Zhipu AI）、Qwen3.5（Alibaba）、Kimi K2.5（Moonshot AI）、DeepSeek V4
- Kimi K2.5は最大100体の並列サブエージェントで動くエージェント特化型（SWE-bench 76.8%）。Qwen3.5は中日韓の多言語最強。DeepSeekは最安値（$0.14〜0.30/M入力トークン）だが性能面ではGLM-5・Kimiに追い越されつつある
- 【2026-07-09追記】Tencentがオープンウェイト新モデル「Hy3」を発表（パラメータ2,950億・アクティブ210億、Apache 2.0ライセンス）。コーディング以外の全ベンチマークでGLM-5.2を上回り、半分のサイズで勝利。中国オープンウェイト勢のトップ争いにさらに一角が加わる形（ソース: https://venturebeat.com/technology/tencents-apache-licensed-hy3-takes-on-glm-5-2-at-half-the-size-and-wins-everywhere-except-coding）
- OpenRouterでの中国勢流通シェアが1年で2%未満→45%超に急増

### チップ面
- 米国のNvidia輸出規制（H100/A100、直近ではH200も事実上締め出し）が国産化を加速させる結果に
- Huawei Ascend 950シリーズ（性能はNvidia H200に近いとされる）の国内シェアが急拡大。ByteDance・Tencent・Alibabaが発注殺到。DeepSeekも最新モデルをHuawei製シリコン向けに最適化
- Nvidia自身が「中国市場はHuaweiにほぼ明け渡した」と発言。中国の自給率は2021年ほぼ0%→2026年時点で約40%（Morgan Stanleyは2030年に約85%と予測）

### 中国政府による海外アクセス制限の検討【2026-07-23追記】
- 2026年7月7日、Reutersが独占報道: 中国当局がAlibaba・ByteDance・Z.ai（旧Zhipu、GLM開発元）と会合し、自国の最先端AIモデル（未公開のものも含む）への**海外からのアクセス制限**を検討中と判明
- 検討内容: ①モデルの重み・学習データの海外流出制限、②中国設計チップの海外生産制限、③戦略的技術の買収案件への審査強化。「海外ユーザーに最先端モデルの重みをダウンロードさせてよいか」も論点
- 背景: 中国製モデルが世界的競争力を持つに至り、貴重なAI知財の海外流出・戦略的AIスタートアップの海外資本による買収リスクへの警戒
- 現時点では検討・協議段階で最終決定や実施時期は未定。適用対象は主に**まだ公開されていない次世代フロンティアモデル**が中心で、既存の公開済みモデル（GLM-5.2・Qwen3.7等）は当面影響を受けない見込み
- **意味合い**: これまでの「オープンウェイトでグローバルシェア急拡大」という"広げる"戦略の転換点になり得る。実施されれば、次世代の中国製フロンティアモデルは輸出規制的な壁に直面する可能性
- ソース: https://www.explainx.ai/blog/china-overseas-ai-model-restrictions-reuters-july-2026 , https://whtc.com/2026/07/07/exclusive-beijing-is-looking-at-curbing-overseas-access-to-chinas-top-ai-models-sources-say/

### 海外展開・信頼性 — 二極化した広がり方
- 中国製AIのグローバルワークロード比率は2024年末1%→2025年末30%に急増。Alibaba Qwenは7億ダウンロード超で世界最大のオープンソースAIプロバイダーに
- **広がる地域**: 価格に敏感な新興国・グローバルサウス・非西側圏で急速に浸透。DeepSeekの市場シェアはベラルーシ56%、キューバ49%、ロシア43%、シリア約23%、イラン約25%、アフリカ一部で11〜14%（他地域の2〜4倍）。理由は無料・オープンウェイト・サブスク不要という価格優位
- **広がらない地域**: 北米・欧州では普及率が低いまま。米下院委員会がDeepSeekを「米AIモデルからの盗用、プロパガンダ拡散、中国軍関連インフラ経由でのデータ移転」で告発。Booz Allenは「中国製AIが米国コードに脆弱性を混入させる」懸念を指摘。Airbnb・Anysphere等、中国製モデル利用を開示した企業が議会調査の対象に
- 完全な締め出しは事実上不可能との指摘も（DeepSeek・Qwenは無数のミラー・サードパーティ経由でAPI利用可能なため）
- 一部報告書は、この普及を「西側プラットフォームが展開しにくい地域で中国の影響力を広げる地政学的な道具」になり得ると分析
- **結論**: 「お国柄」への懸念は的中しており、地政学的ブロックごとに全く異なる採用曲線を描いている。技術トレンドが輸出規制・チップ供給・データ主権・地政学的影響圏の奪い合いと直結している点が2026年のAI競争の大きな特徴

## 日本の動き

### 国家戦略 — 巨額の「主権AI」投資
- 政府が「国家AI基本計画」の一環で$63.4億（約1兆円）規模の「Sovereign AI」構想を正式承認。2ナノメートル論理チップから兆パラメータ級基盤モデルまで、国産エコシステムを丸ごと作る狙い
- 半導体・AIに14年間で$2.3兆（約370兆円）という国家的長期投資ロードマップも発表。経産省の枠組みでは2030年度まで7年間で10兆円超の公的支援
- 2040年までにロボット1,000万台配備という物理AI（ロボティクス）目標も掲げる

### 中核プレイヤー
- **Noetraコンソーシアム**（SoftBank・Sony中心、自動車・電機・金融・物流含め44社規模に拡大予定）が兆パラメータ級モデルを開発
- **SoftBank**が「主権プロバイダー」を自任し、自己資金$127億で北海道・大阪に大規模データセンターを建設中。高セキュリティな政府・企業向け1兆パラメータモデル「Sarashina」をホスト予定
- **Sakana AI**（「Attention Is All You Need」共著者ら創業、評価額$26.5億で日本最高評価のAIスタートアップ）の「Fugu」（6/22発表）がSWE-Bench Pro・TerminalBenchでGPT-5.5・Claude Opus 4.8を上回り、輸出規制中だったFable 5/Mythosに匹敵する性能と評される
  - 【2026-07-09追記・訂正】単一の巨大モデルではなく、**複数の専門特化モデルを自動オーケストレーションする「マルチエージェントが単一モデルのように振る舞う」システム**。自社研究Trinity・Conductor（ICLR 2026）を基盤に、タスクをどのモデルに委譲するか自体を学習する「learned orchestration」を採用（固定ワークフローではない）。「Evolutionary Model Merge」は不正確で、正しくは学習型オーケストレーション方式
  - 2段構成: **Fugu**（日常タスク・チャットボット向け、低レイテンシ重視）と **Fugu Ultra**（複雑な多段階問題向け、より深いエキスパートプール使用）
  - Fugu UltraはLiveCodeBenchで93.2点を記録しClaude Fable 5の89.8点を上回る。価格は入力100万トークン$5程度
  - Fable 5・Mythos自体は非公開のためFuguのエージェントプールには含まれていない。それでも同等性能に達している点がポイント
  - **輸出規制耐性**が売り：Fable/Mythosと異なり「輸出規制リスクなしにフロンティア級の能力を提供」できる設計を明示的に強みとして訴求
  - ソース: https://sakana.ai/fugu-release/ , https://venturebeat.com/orchestration/no-claude-fable-5-no-problem-sakana-achieves-frontier-performance-with-new-fugu-multi-model-auto-synthesis-system
  - 【2026-07-23追記・企業プロフィール】創業は2023年7月、共同創業者はDavid HaとLlion Jones（共にGoogle出身、Llion Jonesは「Attention Is All You Need」共著者）
  - 資金調達推移: 2024年1月シード(約3,000万ドル)→2024年9月シリーズA(約300億円)→2025年11月シリーズB(約320億円、評価額26.5億ドル=約4,000億円で日本最高評価に)→2026年1月Googleとの戦略的パートナーシップ→2026年2月Citiからの戦略出資（金融サービス領域への展開を示唆）
  - 独自技術: 進化的モデルマージ、集合知（Collective Intelligence）アプローチ、AI Scientist、AB-MCTS。商用第一弾プロダクトは「Marlin」
  - 戦略の本質: OpenAI的な「計算資源を大量投入するスケール競争」とは一線を画し、効率性・オーケストレーションの巧みさで勝負するポジショニング
  - **「国産AI成功組」という文脈**: ITmediaの分析では、NTT・ソフトバンク・Sakana AIに共通するのは「ゼロから自前で全部作る」のではなく、NVIDIA Nemotron等の既存オープンモデルを土台にしつつ自社独自のデータセット・学習手法・AI技術を組み合わせて差別化する勝ちパターン。Fuguの「既存モデル群をオーケストレーションで組み合わせる」発想もこれに合致
  - ソース: https://www.itmedia.co.jp/business/articles/2607/21/news036.html
- 政府の生成AI基盤「Gennai」では、NTTデータ（tsuzumi 2）、KDDI/ELYZA、Preferred Networks（PLaMo 2.0 Prime）、NEC（cotomi v3）など国産7ベンダーを選定し、約18万人の行政職員へ展開中
- エッジ向けにPLaMo Lite（1B）、楽天AI 2.0 mini（1.5B）などオンデバイス小型モデルも展開

### なぜ海外にあまり聞こえてこないのか
- 日本政府自身のAI基本計画が「我々は遅れている、どう追いつくか」という"recovery"（挽回）のフレーミング。金額は派手だが、Noetraの兆パラメータモデルやSarashinaは実際にまだ出荷されていない構想段階（Googleの「発表はしたが未出荷」問題と同様の構図）
- 国内世論自体が他のアジア諸国より生成AIへの懐疑心が高いという調査結果あり。国内で盛り上がっていないものが海外で話題になりにくい
- 「主権AI」という概念自体への海外の冷めた視線もある。日本もNvidia等海外ベンダーへの計算資源依存から完全には脱しておらず、「独立」の看板と実態のギャップが懐疑論を招いている
- 日本のAI法制定の動機も「AIのリスクを実質的に減らす」というより「世界で問題が起きた際に『法整備が不十分な国』と批判されないため」という後追い・守り志向という分析があり、積極的な対外発信のマインドセットとは逆方向
- **結論**: 投資額自体は本気だが、発信スタンスが守り・挽回志向になっているのが実態。Sakana AIのFuguのように「性能で語る」個別プレイヤーの成果が積み上がれば、国としての発信力も変わる可能性がある

## 出典
- https://myclaw.ai/blog/gpt-5-6-sol-vs-fable-5
- https://benchlm.ai/blog/posts/fable-5-vs-gpt-5-6-market-direction
- https://the-decoder.com/openais-claude-mythos-competitor-gpt-5-6-sol-launches-under-government-controlled-access-it-calls-unsustainable/
- https://teamai.com/blog/large-language-models-llms/the-2026-ai-frontier-model-war-2/
- https://jobsecuritymeter.com/guides/frontier-ai-models-2026
- https://www.abhs.in/blog/ai-models-april-june-2026-gpt6-claude5-llama4-what-developers-should-prepare
- https://www.mindstudio.ai/blog/google-vs-openai-vs-anthropic-momentum-2026-narrative
- https://aitoolbriefing.com/industry/microsoft-build-2026-copilot-project-polaris/
- https://www.kavout.com/market-lens/is-microsoft-building-its-own-ai-empire-beyond-openai
- https://www.kavout.com/market-lens/apple-and-google-ai-partnership-2026-everything-you-need-to-know-about-gemini-powered-siri
- https://www.aboutamazon.com/news/company-news/amazon-invests-additional-5-billion-anthropic-ai
- https://www.digitalapplied.com/blog/claude-fable-5-usage-credits-july-7-pricing-guide-2026
- https://claudefa.st/blog/guide/development/fable-5-usage-credits
- https://www.remoteopenclaw.com/blog/best-chinese-models-2026
- https://capacityglobal.com/news/deepseek-v4-triggers-scramble/
- https://www.digitalapplied.com/blog/chinese-ai-models-q2-2026-market-share-report
- https://www.cnbc.com/2026/05/21/nvidia-jensen-huang-china-ai-chip-market-huawei.html
- https://officechai.com/ai/chinas-self-sufficiency-in-ai-chips-has-risen-from-20-in-2023-to-over-40-in-2026-morgan-stanley-data/
- https://www.chinafile.com/reporting-opinion/features/censorship-not-deterring-global-adoption-of-chinese-ai
- https://restofworld.org/2026/when-americans-choose-chinese-ai/
- https://www.foxnews.com/politics/chinese-ai-models-raise-sleeper-agent-fears-after-report-finds-more-vulnerable-code-us-users
- https://www.euronews.com/next/2026/01/09/deepseeks-ai-gains-traction-in-developing-nations-microsoft-report-says
- https://chinaglobalsouth.com/2026/02/03/deepseek-ai-global-south-adoption/
- https://www.japantimes.co.jp/news/2026/07/01/japan/japan-ai-plans/
- https://markets.financialcontent.com/wral/article/tokenring-2026-1-13-japans-6-billion-sovereign-ai-gamble-a-bold-bid-for-silicon-and-software-independence
- https://www.helloworldjapan.com/en/articles/japan-ai-strategy-government-plan-explained
- https://the-decoder.com/sakana-ais-fugu-orchestrates-multiple-llms-to-match-anthropics-fable-and-mythos-benchmarks/
- https://www.airealist.ai/p/japan-built-the-bullet-train-why
- https://codenote.net/en/posts/japanese-local-llm-development-case-studies/
- https://www.spf.org/iina/en/articles/diletta_03.html
- https://www.csis.org/analysis/norms-new-technological-domains-japans-ai-governance-strategy
- https://asiatimes.com/2025/09/inside-japans-struggle-to-build-sovereign-ai/
