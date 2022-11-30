# 職務経歴書
## 基本情報
|key|value|
|---|-----|
|Name| 八木洸太|
|Twitter|<a href="https://twitter.com/88888888_kota" target="_blank" rel="noopener noreferrer"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="6tJ9i7CvyWzGM1M" height="30" width="40" /></a>|
|Facebook|<a href="https://fb.com/yagikota888" target="_blank" rel="noopener noreferrer"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="八木洸太" height="30" width="40" /></a>|
|LinkedIn|<a href="https://linkedin.com/in/yagikota" target="_blank" rel="noopener noreferrer"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="八木洸太" height="30" width="40" /></a>|
|Leetcode|<a href="https://www.leetcode.com/kota888" target="_blank" rel="noopener noreferrer"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="kota888" height="30" width="40" /></a>|
|Wantedly|<a href="https://www.wantedly.com/id/kouta_yagi_b" target="_blank" rel="noopener noreferrer"><img align="center" src="https://user-images.githubusercontent.com/69202609/156877062-62d11efc-3f4c-4e70-9310-836bc599f416.png" alt="kota888" height="30" width="40" /></a>|
## スキル
* 実務で使用した技術だけを列挙しています。
### 言語
* Python
* Go
### フレームワーク
* Django

### RDB
* MySQL, PostgreSQL

### クラウド
* AWS

### その他
* Docker

## 職務経歴
### インターンシップ
#### 楽天株式会社(2022年8月~2022年9月)
【概要】
akamai CDNの設定情報を自動管理できるツールの開発。

【担当業務】
上記ツールの開発。

【成果】
* 既存のコードのリファクタリング。
* akamai CDNの設定情報に変更があればJIRAに反映させる処理の実装。
* 好ましくないwordが設定に含まれている場合は、slackにアラートを飛ばす処理の実装。
* ログファイルの作成処理の実装。
* リファクタリングの際、コードの責務や可読性、保守性を意識した。
* 実装に至るまでの過程などはドキュメントに残し、情報の共有を意識した。
* 計算量が大きくならないようなアルゴリズムを用いて実装した。

【使用技術】Python


#### 株式会社サイバーエージェント(2022年7月~2022年8月)
【概要】
2週間で、Tappleのクローンアプリを開発。

【担当業務】
バックエンド全般。技術選定。アーキテクチャ設計。技術面でのリード。

【成果】
* 運用保守性、テスタビリティを考えてクリーンアーキテクチャを導入した。
* 各層でテストを実装し、コードの品質を担保した。
* goのcontextをうまく活用し、middlewareでトランザクション処理を実装した。
* 不要なメモリアロケーションが発生しないよう実装した。
* N+1問題が発生しないようSQLを発行した(Eager Loading)。
* sqlboilerを導入し、DBスキーマからmodelを自動生成することで実装コストを削減した。
* Makefileを活用し、各種自動化スクリプトの作成をした。
* GitHubブランチの運用方法を規約化し、作業フロー統一した。
* チームメンバーの技術レベルなどを考慮してタスクの割り振りを行なった。
* notion, slack, gatherを活用し、チームの進捗管理、ナレッジ共有、ペアプロをすることでチーム全体の技術レベルを短期間で底上げできた。
* 初対面メンバー3人で協力して開発を進められた。結果、チーム優勝できた。

【使用技術】Go, Docker, MySQL

【参考URL】
https://zenn.dev/88888888_kota/articles/0f920bdd14cd60
https://github.com/yagikota/tapple_clone

#### Alpha Drive(2022年4月~2022年9月)
【概要】自社SaaS(toB)の新規開発。

【担当業務】
API開発。検索エンジンやバッチ処理の技術選定。

【成果】
* テナント設定APIの要件定義、DB設計、実装。
* 検索エンジンAlgoriaの技術選定及び導入。
* バッチ処理Lambdaの技術選定。
* Algoriaの導入する際、DBの情報をAlgoriaに反映させるバッチ処理の実装及び単体テストの実装。
* 新規サービス開発チームにジョインし素早くキャッチアップした。
* 担当範囲外のコードも読み、常にキャッチアップし続けた。
* APIの要件定義から実装まで一人でやり切った。
* 実装に至る過程や懸念点などはslackやConfluenceにドキュメントとして残し、情報をできるだけ共有した。
* slackやgithubなどのテキストベースコミュニケーションでは、認識の差異が出ないよう工夫して文章を書いた。
* フロントエンドエンジニアと綿密にコミュニケーションをとり、実装のすり合わせを行い、出戻りを最小限にした。

【使用技術】Go, PostgreSQL


#### ゲームAPIの開発 株式会社サイバーエージェント(2022年2月~2022年3月)
【概要】2週間で、ゲームのAPIを開発。

【役割】バックエンド全般。

【成果】
* コードの責務、役割を考え、実装。
* トランザクションやn＋1問題対策、エラーハンドリング、負荷試験など学びの多い二週間だった。

【使用技術】Go, Docker, MySQL, vegeta, pprof

【参考URL】
* https://docs.google.com/presentation/d/1ifPgw0LO6u1NxpWGALjVxw8Eb28EGrACLYDr9qPeBYE/edit?usp=sharing
* https://github.com/yagikota/clean_arch_with_go
* https://zenn.dev/88888888_kota/articles/ef3f223e1c70f0


#### 簡易証券アプリをマイクロサービス開発 株式会社Finatextホールディングス(2022年2月)
【概要】チーム4人で簡易証券アプリを開発。それぞれが、サーバー１つを開発し、APIでつなげた。

【役割】注文サーバーを開発。他のサーバーからのリクエストを処理したり、外部APIを用いて株価の現在価格を取得する機能を実装。

【成果】
* Go, AWSなどは初体験であったが、開発に必要な機能を速習し開発に取り組んだ。
* 5日間という短い期間だったが、積極的にコニュニケーションをとって開発を進められた。
* Notionでの学びの共有など、互いに高めあえた。

【使用技術】Go, Docker, AWS

【参考URL】
* https://zenn.dev/88888888_kota/articles/da05fef0cb1234

#### CA 1Day Youth Boot Camp バックエンド/インフラエンジニア編：現場で使うコンテナ技術、Kubernetes＆コンテナ入門 株式会社サイバーエージェント(2022年11月)
【概要】Docker, Kubernetesに関するハンズオン講義を通し、両技術に関する知見を深めた。

【成果】Dockerに関しては、すでに使用したことがあったので新たな学びは少なかったが、Kubernetesに関しては初体験ということもあり、非常に勉強になった。学んだ内容を下記URLにまとめてある。

【使用技術】Docker, Kubernetes

【参考URL】https://gist.github.com/yagikota/6726405044730a6e340edfc9396620d6

#### 仮想通貨分析アプリ開発 株式会社ソウ(2022年8月)
【概要】FTXの提供するAPIを用いて仮想通貨分析に必要なデータの取得と分析をおこなった。

【担当業務】APIを用いたデータの取得、前処理、分析を担当。

【成果】
* 初めてのオンラインインターンシップということもあり、コミュニケーションに苦労したが、slack, discordなどを使用し積極的にコミュニケーションをとった。
* 取得するデータが膨大であったため処理に時間がかかったが、並行処理、レコードの一括処理など行い、処理時間を50%短縮した。

【使用技術】Python, Django, pandas

### 個人プロジェクト
#### 大学専用のQ&Aアプリを開発
【概要】コロナ禍で大学生活に困っている学の助けになると考え、開発しているアプリ。個人開発。

【担当業務】企画、開発、デザイン全てを担当。

【使用技術】Python, Django, HTML, CSS, Docker, PostgreSQL, Nginx, gunicorn, CircleCI

【参考URL】https://github.com/yagikota/univ_app

