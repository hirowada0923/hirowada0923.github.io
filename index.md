
# 業務アプリケーションへのアジャイル適用時によくある質問
このサイトでは、従来型開発からアジャイルへ移行する際によくある疑問について、思いつきで順不同で記載します。

## エンタープライズ・アジャイル

1. [Scaled Agile Framework](http://www.scaledagileframework.com/)
  - Dean Leffingwellが中心になって開発した、スクラムを事業部や企業全体にまで拡大するためのフレームワークで、[VersionOneの11th annual State of Agile Survey](https://explore.versionone.com/state-of-agile/versionone-11th-annual-state-of-agile-report-2)で、スケーリング・アジャイル手法のシェア28％でトップ。
  - [日本語サイト](http://jp4.scaledagileframework.com/)
  - [オージス総研 SAFeサイト](http://www.ogis-ri.co.jp/solution/1210904_6793.html)
  - 書籍(英語)
  [![Scaling Software Agility: Best Practices for Large Enterprises](http://www.scaledagileframework.com/wp-content/uploads/2015/12/Scaling-Software-Agility-thumbnail.jpeg)](http://www.amazon.com/Scaling-Software-Agility-Practices-Enterprises/dp/0321458192)[![Agile Software Requirements: Lean Requirements Practices for Teams, Programs, and the Enterprise](http://www.scaledagileframework.com/wp-content/uploads/2015/12/Agile-Software-Requirements-thumbnail.jpg)](http://www.amazon.com/Agile-Software-Requirements-Enterprise-Development/dp/0321635841)
  - 書籍(日本語)
  [![](/ssa.jpg)](https://www.amazon.co.jp/dp/4798120405)[![](/asr.jpg)](https://www.amazon.co.jp/dp/B00IMRDXZW)
2. [Disciplined Agile Framework](http://www.disciplinedagiledelivery.com/)
  - Scott W Amblerが中心になって開発した、企業のIT組織のコンテキストに合わせて適切なアジャイル導入・展開をするためのディシジョン・フレームワーク
  - [日本語サイト](http://disciplinedagiledelivery.jp/)
  - 書籍(英語)
  [![Disciplined Agile Delivery: A Practitioner’s Guide to Agile Software Delivery in the Enterprise](https://i0.wp.com/www.disciplinedagiledelivery.com/wp-content/uploads/2012/08/ambler_cover_small1.jpg?h=212)](http://www.disciplinedagiledelivery.com/dad-book/)[![Introduction to Disciplined Agile Delivery: A Small Team’s Journey from Scrum to Continuous Delivery](https://i1.wp.com/www.disciplinedagiledelivery.com/wp-content/uploads/2015/06/IntroDADCoverMedium.jpg?h=212)](http://www.disciplinedagiledelivery.com/introduction-to-disciplined-agile-delivery/)[![An Executive’s Guide to Disciplined Agile: Winning the Race to Business Agility](https://i1.wp.com/www.disciplinedagiledelivery.com/wp-content/uploads/2017/07/ExecGuideFrontCover.jpg?h=212)](http://www.disciplinedagiledelivery.com/exec-guide-to-da/)
  - 書籍(日本語)
  [![](/dad.jpg)](https://www.amazon.co.jp/dp/B00G9QJ21M)[![](/intro_dad.jpg)](https://www.amazon.co.jp/dp/B06WGL3TS4)

3. その他スケーリング手法
  - [LeSS(Large Scale Scrum)](https://less.works/)
    - [日本語サイト](https://less.works/jp/)
  - [NEXUS](https://www.scrum.org/resources/nexus-guide)
    - [日本語ガイド](https://s3.amazonaws.com/scrumorg-website-prod/drupal/2016-09/NexusGuide_v1.1%20-%20Japanese%20nfv3.pdf?nexus-file=https%3A%2F%2Fs3.amazonaws.com%2Fscrumorg-website-prod%2Fdrupal%2F2016-09%2FNexusGuide_v1.1%2520-%2520Japanese%2520nfv3.pdf)

## Q1. アジャイルが向いている、向いていないの判断基準とは？

- IBMでは、[チェックリスト](/Agile_Assessment_Checklist_v1.xls)を用いて判断の参考にしています。
- [Harverd Business Review 2016 May Embracing Agile](https://hbr.org/2016/05/embracing-agile) 2. Understand Where Agile で、アジャイル向きの条件が記述されています。

- [その他アジャイルアセスメント](https://www.benlinders.com/tools/agile-self-assessments/) オランダのアジャイルコンサルタントBen Linderのサイトで70以上のアセスメントへのリンクが集められています。

## Q2. アジャイルの体制はどうあるべきか？

- Henrik Knibergの[Spotify Model](http://blog.crisp.se/2012/11/14/henrikkniberg/scaling-agile-at-spotify)
  - Scaling Agile @ Spotify with Tribes, Squads, Chapters & Guilds
  [![Scaling Agile @ Spotify with Tribes, Squads, Chapters & Guilds](https://dl.dropbox.com/u/1018963/Articles/Scaling-Agile-at-Spotify.png)](http://blog.crisp.se/2012/11/14/henrikkniberg/scaling-agile-at-spotify)
  - [日本語訳 藤原さん@楽天](http://lean-trenches.com/scaling-agile-at-spotify-ja/)

- 同時に、Spotify modelを真似るなとも言われています（形ではなく文化を真似よ）
  - https://www.infoq.com/news/2016/10/no-spotify-model
  - https://www.infoq.com/presentations/spotify-culture-stc

- IBM WatsonチームのSpotify Model
  - Spotify Modelは従来の組織図の上位への報告構造ではなく、逆にした支援構造にする文化を促進します。下図は、Spotify Modelを取り入れたWatsonチームのSpotify Modelの修正版です。Watsonチームは、Spotifyのように単独製品ではなく、複数の異なる製品を持っているため、TribleやProduct Levelを3or4人体制にしています。
  [![ImageCaption](/spotify.png)]()
  [![ImageCaption](/watson.png)]()

- その他体制について
  - DAD本の体制
    - 第5章チームを組織する
  - SAFe本の体制
    - 第3章 3.2 アジャイルチームの役割と責任
    - 第4章 4.2 アジャイルチームを大きな規模で組織化する
  - エッセンシャルスクラムの体制
    - 第12章 スクラムチームの構成
    [![エッセンシャル スクラム](http://www.seshop.com/static/images/product/17008/L.png?h=212)](https://www.amazon.co.jp/dp/B00MB6GO7E)

- モチベーションについて
  - Management 3.0
  [![Management 3.0: Leading Agile Developers, Developing Agile Leaders](https://1qjpt15fhlq3xjfpm2utibj1-wpengine.netdna-ssl.com/wp-content/uploads/2015/02/Management-3.0-agile-management-book-cover-230x300.jpg?h=212)](http://www.amazon.com/gp/product/0321712471/ref=as_li_ss_tl)
    - [やる気に関する驚きの科学（ダニエル・ピンク）](https://www.ted.com/talks/dan_pink_on_motivation?language=ja)
    - [Moving Motivator](https://management30.com/practice/moving-motivators/)
    - [Kudo Box](https://management30.com/practice/kudo-box/)

## Q3. アジャイルのアーキテクチャとはどうあるべきか？

- "Architecture is planned." by Waterfall
- "Architecture should be grown." by Grady Booch
- "Architecture emerges." by Kent Beck

- XP : Architecture emerges（アーキテクチャは現れる）
- Scrum : Scrum does not describe software architecture.
- RUP : Architecure-Centric and Use-Case Driven

- [ディシプリンド・アジャイル・デリバリー(いわゆるDAD本)]()
  - DADのアーキテクチャの考え方は、第9章 初期の技術戦略を識別するに記載されています。
  - [Potential Misconceptions about Agile Architecture](http://www.disciplinedagiledelivery.com/potential-misconceptions-about-agile-architecture/)
  - [Disciplined Agile Architecture: Initial Architecture Envisioning](http://www.disciplinedagiledelivery.com/disciplined-agile-architecture-initial-architecture-envisioning/)

- [アジャイルソフトウェア要求(いわゆるSAFe本) Dean Leffingwell](https://www.amazon.co.jp/dp/4798135321)
  - SAFeのアーキテクチャの考え方は、第17章 非機能要求、第20章 アジャイルアーキテクチャーに記載されています。
  - [Agile Architecture](http://www.scaledagileframework.com/agile-architecture/)
  - [Architecture Runway](http://www.scaledagileframework.com/architectural-runway/)

## Q4. スプリントゼロの完了基準とは？

- DADの方向付けフェーズの完了基準が参考になる
  - [Inception Goal](http://www.disciplinedagiledelivery.com/inception-goals-3/)
  [![DAD Goals](/dad-phase.png)]()
  - 方向付け
  [![DAD Inception Phase](/dad-inception.png)]()

- スプリントゼロ開始前サンプル

| 分類 | 主な追加チェックの観点 |
|:---------|:---------|
| ①契約 | •プロダクト・オーナーがアサインされる、もしくは、 |
|  | •プロダクト・オーナーに要件および要件の優先順位を決める権限があること |
| ②完了基準（Definition of Done） | •プロダクト・ビジョン（ゴール）が明確に定義され、お客様と合意されていること |
|  | •ゴール達成のKPIが定義されお客様と合意されていること |
|  | •各スプリントごとに、実施する作業と完了基準が定義されていること |
| ③ワーク・プロダクト | •各スプリントごとに作成するワーク・プロダクトが上記完了基準（Definition of done）に定義されること |
|  | •ワーク・プロダクトの作成時期が決定されていること |
|  | •ユーザー・ストーリーに対して受入基準が定義されていること |
| ④アーキテクチャー | •机上検証済みのアーキテクチャーの概要が定義されており（アーキテクチャー関連ドキュメント）、それに基づいてSprint0で検証する計画が策定されていること |
| ⑤プロダクト・バックログ | •ユーザー・ストーリーが作成されていること |
|  | •プロダクト・バックログが作成されていること。また、Minimum Viable Product（MVP）が定義されていること |
|  | •ユーザー・ストーリの優先順位付けのためのルールが決まっていること。また、そのルールに従って、ユーザー・ストーリーが優先順位付けされていること |
|  | •ユーザー・ストーリー・マッピングができていること |
| ⑥リリース計画 | •ウォーターフォール型開発とアジャイル型開発が共存する場合、個々のパーツの依存関係に基づいてリリース計画が作成されていること。また、変更時の影響確認など、連携方法について検討されていること |
| ⑦Collaborative environment | •チーム・メンバーは同じ場所（ルーム）で作業できること。もしくは、物理的に異なる場所で作業する場合は、それを補うためのコミュニケーション・ツールが準備されること |
| ⑧コミュニケーション計画 | •Planning、Dairy scrum、Sprint review、Sprint retrospectiveなどのアジャイル・イベント、および各種報告の実施頻度、参加者などが計画されていること |
|  | •プロダクト・オーナーは、開発期間中、アジャイル開発メンバーからの質問にいつでも対応できること、難しい場合には、プロダクト・オーナーのアサインとあわせて、支援体制等が検討されていること |
| ⑨品質戦略の定義と共有 | •スプリント/リリースごとに、アウトプットの品質を担保する品質戦略(Definition of Doneでも可)が策定され、メンバーと共有されていること。たとえば、ピア・レビュー、リグレッション・テスト、スプリント・レビューなど |
| ⑩Velocity | •Velocityを測定し、測定されたVelocityを次回以降のSprintに適用する計画があること |

- スプリントゼロ完了サンプル

| カテゴリーとレビュー観点サマリー | 成果物とチェックの観点(特記事項があれば） |
|:---------|:---------|
| 【テクニカル】 | •ユーザー・ストーリー：Sprint Planning時の見積りに十分な粒度で詳細化されていること。受け入れ基準が明記されていること |
| •右記のワーク・プロダクトが作成され、完了基準を満たしていることを確認 | •プロセス定義：ユーザー・ストーリー・マッピングが完成していることの再確認 |
| •完了基準は、ワーク・プロダクト作成指針をベースに各プロジェクトで定義する（Definition of Done） | •アーキテクチャー関連ドキュメント |
| •アーキテクチャーの検証 | •システム・コンテキスト |
| •プロトタイプによるユーザー・インターフェースと標準化の検証 | •非機能要件 |
| •開発/テストなどの環境の検証 | •コンポーネント・モデル |
|  | •オペレーショナル・モデル |
|  | •外部インターフェース仕様 |
|  | •ユーザー・プロファイル |
|  | •UIプロトタイプ |
|  | •概念データ・モデル |
|  | •設計規約、ガイド |
|  | •コーディング規約 |
| 【プロマネ】 | •マスター・スケジュール |
| •右記の計画が、Sprin0の実績に基づいて検証され、必要に応じて更新され、お客様と合意されていること | •スプリント計画：Sprint0の実績に基づき、次Sprintの計画が作成されている |
| •スプリント・バーンダウンによるSprint0の進捗、計画と実績との乖離の確認。今後の予測、アクションの確認 | •リリース計画：Sprint0の実績に基づき、リリース計画が検証されている |
| •Velocity実績の確認 | •プロダクト・バックログ：更新/変更箇所が明確であり、最新化されている　 |
| •リスク・課題の確認 | •品質戦略/品質計画、テスト戦略：各スプリントで実施するピア・レビュー、ペアプロ、リグレッション・テスト、スプリント・レビューなどの品質活動が詳細化され、計画されている |
| •次Sprintの計画の確認 | •Definition of Done ：各スプリントで実施すべきことと完了基準が定義されている |
|  | •Undone : 各スプリントで実施できてないことがUndoneとして管理されている |
|  | •テスト戦略：リリース/スプリントごとに実施するテスト・レベル、種別、テスト・ケース、テスト・データ、環境、開始/完了基準などが計画されている |
|  | •Velocity：Sprint0の実績が確認でき、次Sprintの見積りに適用されている |
|  | •バーンダウン・チャート |
|  | •スプリント・バーンダウン：Sprint0が期日までに達成可能か、工数が足りるか、予測しながら判断、管理されている |
|  | •リスク・課題 |

## Q5. 受け入れテストの自動化はどうあるべきか？

- [Agile Testing](https://www.amazon.com/dp/0321534468)
- [More Agile Testing](https://www.amazon.com/dp/0321967054)
[![More Agile Testing](/mat.jpg)](https://www.amazon.com/dp/0321967054)
  - Chapter 7. Levels of Precision for Planning
  - Chapter 8. Using Models to help plan
  - Chapter 18. Agile Testing for Enterprise
  - Chapter 21. Agile Testing for Regulated Environment
- [ISTQB Agile Testing Foundations](https://www.amazon.com/dp/B06Y116GD6)
[![ITSQB Agile Testing Foundations](/ISTQB_agile.jpg)](https://www.amazon.com/dp/B06Y116GD6)
- [QA to AQ: Shifting from Quality Assurance to Agile Quality](http://resources.sei.cmu.edu/library/asset-view.cfm?assetid=436589)

- [アジャイルソフトウェア要求(いわゆるSAFe本) Dean Leffingwell](https://www.amazon.co.jp/dp/4798135321)
  - 第10章 受け入れテスティング

- [アジャイルテストの4象限](http://jasst.jp/archives/jasst10n/pdf/S2.pdf)
- [楽天の藤原大さん](http://daipresents.com/2016/agile-testing/)
- [平鍋さんQiita　QA to AQ](http://qiita.com/kenjihiranabe/items/a0795dbdab4c58e746a1)

## Q6. 完成の定義のサンプル
[スクラムガイド](https://www.scrumguides.org/docs/scrumguide/v2016/2016-Scrum-Guide-Japanese.pdf#page=15)の完成の定義では、以下のように書かれています。インクリメントの「完成」の定義に関して、開発組織の慣例・標準・ガイドラインが存在する場合は、スクラムチームは最低でもそれを守らなければいけない。インクリメントの「完成」の定義が開発組織に存在しない場合は、スクラムチームの開発チームはプロダクトに適した「完成」を定義しなければいけない。複数のスクラムチームがシステムやプロダクトのリリース作業をする場合は、すべてのスクラムチームの開発チームが共通の「完成」の定義を使用しなければいけない。

- [スクラム現場ガイド](https://www.amazon.co.jp/dp/B01D4JHITO)
  [![スクラム現場ガイド](/sfg.jpg)](https://www.amazon.co.jp/dp/B01D4JHITO)
  - 7章 完成を知る 完成の定義のサンプルと半日で完成の定義を作成する手順が紹介されています。
    1. ブレーンストーミング
    2. カテゴリ分け
    3. 整理
    4. 完成の定義の作成と公開
- 完成の定義サンプル
  [![完成の定義サンプル](/dod.png)]()

## Q7. スプリントレビューで、利害関係者はどのような視点で臨むべきか？

[スクラムガイド](https://www.scrumguides.org/docs/scrumguide/v2016/2016-Scrum-Guide-Japanese.pdf#page=11)の定義によると「スプリントレビューとは、スプリントの終わりにインクリメントの検査と、必要であればプロダクトバックログの適応を行うものである。」と書かれています。参加する利害関係者にもインクリメントの検査とプロダクトバックログの適応を明確に分けて議論できるようにプロダクトオーナーが進行する必要があります。インクリメントの検査は、あくまで完成の定義とストーリーの受入基準を満たしているかどうかを確認することです。これは基準が明確であり利害関係者がもっとこうして欲しいといった要望を発言する余地はありません。もちろん完成の定義や受入基準が明確ではなかったり事前に存在しないケースはそもそも確認ができなくなります。スプリントレビューが上手くいかない原因の多くはそれに起因しています。ただし、スプリントを繰り返す中で完成の定義や受入基準を改善することが可能です。一方、プロダクトバックログの適応は、プロダクトの価値を高めるためのフィードバックを受けることで明確な基準があるわけではありません。但し、プロダクトの価値を高めるという条件はあります。利害関係者の好みを発言する場ではありませんので、フィードバックには、なぜそれがプロダクトの価値を高めるのかについて説明してもらうことが大切です。

## Q8. アジャイルの予算化はどうあるべきか？

従来型の予算管理や稟議の仕組みではいくら現場がアジャイルになってもうまくいかない。元々アジャイル開発とは関係なく、市場の変化が激しくなって従来型の予算管理の経営では市場の変化に対応できないということで出てきた予算管理の考え方が、Beyond Budgeting Modelで日本語では、脱予算経営とか超予算経営とか訳されている。Googleで脱予算経営とアジャイルで検索すると幾つかヒットする。Implementing Beyond Budgeting 2nd Editionには、Beyond Budgeting and Agileという章が2nd Editionで追加されており、元々アジャイルと関係のなかった著者がアジャイルコミュニティでの講演をきっかけにBeyond BudgetingがScrumと非常に相性が良いことに気が付きます。
日本ではKDDIの事例がBeyond Budgetingの事例として有名だそうですが、KDDIがScrumを積極的に推進しているのはまんざら偶然ではないような気がします。京セラのアメーバ経営もBeyond Budgetingを取り入れたわけではありませんが結果的に同じコンセプトを持っており企業文化としてアジャイルに向いていると考えられます。

- [Implementing beyond budgeting 2nd edition](https://www.amazon.com/dp/B01HXJIY80)
  - 2016年の第2版には、Beyond Budgeting and Agileという章が追加されている
- Beyond Badgeting Model（超予算経営モデルあるいは脱予算経営モデル）
- SAFe本 第22章 投資テーマ、エピック、ポートフォリオ計画

- アジャイル契約（内製の場合は予算化）
  - [SAFe Agile Cntract](http://www.scaledagileframework.com/agile-contracts/)
  - [非ウォーターフォール型開発に適したモデル契約書の改訂版を公開](http://www.ipa.go.jp/sec/softwareengineering/reports/20120326.html)

## Q9. プロダクトオーナーに求められるものは？

- [アジャイルソフトウェア要求(いわゆるSAFe本) Dean Leffingwell](https://www.amazon.co.jp/dp/4798135321)
  - 第11章 プロダクトオーナー、第14章 プロダクト管理者で、Scrumのよる理想的なひとりのPOにおける課題を、現実的にはPOとPMの2つの役割で分担することを提唱している。
- [ユーザーストーリーマッピング Jeff Patton](https://www.amazon.co.jp/dp/4873117321)
  - 12章 で「すべてのストーリーを書き、ストーリーについてすべての会話に参加するひとりのプロダクトローナーを設けても破綻する。」そこでプロダクトディスカバリーチームとして、デザイナーとアーキテクトを含めたチームを提唱している。
- エッセンシャルスクラム 第9章 プロダクトオーナー
- 日本のプロダクトオーナーコミュニティの昨年のイベント[2016PO祭り](https://postudy.doorkeeper.jp/events/52385)
  - DevOpsとリーン・スタートアップ時代のプロダクト・オーナーシップ
    - 楽天の川口さん
      - https://plaza.rakuten.co.jp/rakutentech/diary/201612020000/
    - リクルートテクノロジーズの黒田さん
      - http://i2key.hateblo.jp/entry/2016/11/29/091657
  - GxPの鈴木さん
    - http://arclamp.hatenablog.com/entry/2016/11/30/200201
  - 安井さん
    - https://www.slideshare.net/yattom/po-69540668
- [42 Product Owner Interview Questions to Avoid Hiring Agile Imposters](https://convertkit.s3.amazonaws.com/assets/documents/2010/353472/42-Product-Owner-Imposters-PDF-v1-2017-01-08.pdf)
- [38 + 6 Scrum Master Interview Questions to Avoid Hiring Agile Imposters ](https://convertkit.s3.amazonaws.com/assets/documents/2010/471750/Hands-on-Agile-38_6_Scrum_Master_Interview_Questions_2017-03-21.pdf)

## Q10. ハイブリッドアジャイルはどうか？

おそらく日本でハイブリッドアジャイルと言えば、日立ソリューションの英 繁雄さんの[ハイブリッドアジャイルへ至る道と、その真の姿](http://www.agilejapan.org/img/session/document/F-3_hybrid_agile_session_all_for_web.pdf)、や英さんの書籍の、[ハイブリッドアジャイルの実践](https://www.amazon.co.jp/dp/B00PXBOTRQ)がよく知られていると思います。私の理解では、現状の自社のITの環境の制約を変えずにアジャイルのプラクティスを取り入れるということを前提にしたプロセスと言う理解です。ハイブリッドアジャイルとアジャイルの最大の違いは、頻繁なリリースによって顧客に早期に価値を提供できない点だと思います。アジャイルと名前が付いていますが、ユーザー視点からはほとんどウォーターフォールです。それがユーザーには受け入れられやすいとも言えます。
また、グローバルでは、日本のハイブリッドアジャイルは、Water-Scrum-Fallと呼ばれ、一般にはアジャイルのアンチパターンと認識されています。ただし、海外でも同様の症状は見られ、[実用主義者が勝ったのか？Water-Scrum-Fallが一般的に](https://www.infoq.com/jp/news/2011/12/water-scrum-fall-is-the-norm)といった記事も見られます。だからWater-Scrum-Fallで良いということではないと思います。
また、Disciplined Agileでも、フェーズの概念を取り入れているため、[DADは、ウォーター・スクラム・フォールの一例ですか？](http://disciplinedagiledelivery.jp/faq/)といった誤解も見られます。私見ですが、イノベーションやタイムツーマーケットを目指すならハイブリッドアジャイルは正解ではないと思います。ハイブリッドアジャイルの目的は、英さん自身「変更受け入れ、リスク対策、利用者満足度の向上」と言っています。結局何を目的としているかでハイブリッドアジャイルを選択するということもありだと思います。
