# 業務経歴書

## スキル

※　実務で使用したもののみ記載

### 言語

Go / PHP / Dart / JavaScript / TypeScript / Python

### フレームワーク・ライブラリ

Gin / go-zero / Laravel / Flutter / React.js / Vue.js 

### DB

MySQL / CloudFirestore

### Firebase

Firebase Authentication / Cloud Firestore / Firebase Analytics / Firebase Hosting / Cloud Functions / Cloud Messaging / Remote Config / Firebase Crashlytics

### AWS

ECS / Fargate / ECR / VPC / RDS / Route53 / ELB / SES / SMS / Cloud Watch / ACM / IAM / CodePipeline / CodeBuild / CodeDeploy / EC2 / S3 / CloudFront / SNS / OpsWorks / Batch / Transfer Family / Lambda / Secrets Manager / NAT Gateway

### その他ツール等

Protocol Buffers / Docker / Docker Compose / GitHub Actions / TestFlight / Codemagic / Redash / Squid / nginx / Ansible

---

## 業務経歴

### 受託開発企業での開発業務(複数プロジェクト参加したものを一つにまとめてあります) 2022年 8月~
#### 担当範囲（概要）

- Go (go-zero) を用いたバックエンド開発
- React.jsを用いたフロントエンド開発
- MySQLのDB設計作業
- issue作成作業

#### 使用技術・ツール

【バックエンド】

Go 1.18 / go-zero / MySQL

【フロントエンド】

React.js v18 / TypeScript

【Firebase】

Firebase Authentication

【その他ツール】

Docker / Docker Compose / dbdiagram / Swagger

#### 工夫したこと・発揮したバリュー

- 土日含む週3での参画だったが、テーブル設計等の基盤作業にも携わり、プロジェクトに貢献することが出来た。
- 平日の作業時に仕様やタスクの確認を行い、土日の作業ではタスク切れや待ちを起こさないように工夫した。結果、平日に参画したのと変わらないくらいのアウトプットを出すことが出来た。

#### 学べたこと

- React.jsは本案件で初めて使用したが、Vue.jsの3系に似ていると感じた。
Reactの方が記法がシンプルなので、自分が技術の採用担当になったらフロントではReactを採用しようと思った。

---

### ファッション系アプリの開発 2022 年 6月~ 

#### 開発チーム

開発 4 人

#### 担当範囲（概要）

- Go (Gin) を用いたバックエンド開発
- Flutter を用いたモバイルアプリ開発
- Vue.jsを用いたフロントエンド開発
- GitHub Actions・CodePipelineを用いたCI/CDパイプラインの構築
- AWS Batchを用いたバッチジョブ作成
- ECS・NLB・squidを用いたフォワードプロキシサーバーの構築
- S3・Transfer Familyを用いたSFTPサーバーの構築
- CloudWatch Alarmの作成、およびアラームに従って動作するlambda関数の作成
- RDSを用いたDBサーバーの構築作業
- SNS連携作業
- クローラー作成作業

#### 使用技術・ツール

【バックエンド】

Go 1.17.10 / Gin 1.4.1 / Python(lambda) / MySQL

【フロントエンド】

Vue.js (2.x) / TypeScript

【モバイル】

Flutter 3.3.5

【AWS】

ECS / Fargate / ECR / Batch /VPC / NLB / RDS / Transfer Family / Lambda / Cloud Watch / IAM / CodePipeline / CodeBuild / CodeDeploy / SNS / Secrets Manager / OpsWorks / NAT Gateway

【その他ツール】

Docker / Docker Compose / Squid / GitHub Actions / dbdiagram / Chef

#### 工夫したこと・発揮したバリュー

- Go言語はこの案件で初めて使用するプログラミング言語だったが、早期にキャッチアップすることが出来た。
- 別案件でCI/CDパイプラインを構築した経験を活かし、CI/CDの移行作業を行った。GiHub Actionsは本案件で初使用だったが、こちらも早期にキャッチアップし、貢献。

#### 学べたこと

- Go言語を使用するメリットとして、シンプルな記法でコードが読みやすいことや静的型付け言語であり安全なこと、処理速度の速さ等があることが分かった。
もしも自分がバックエンドの言語の採用決定に携わることになったら、真っ先に採用候補に挙げたいくらいには良い言語であると感じた。
- 今まで新規開発でCI/CDの構築を行うことはあったが、既にリリースされているサービスで構築した経験は無かったので、学びになった。
CI/CD構築にあたって、既存環境に影響を与えないように、現状のインフラ構成を把握する作業など、次回似たような作業をするときに活かせそうな気がする。

---

### 電子書籍サービスの保守改修 2022 年〜(3 ヶ月)

#### チーム構成

開発 4 人 PM ・マーケター 3 人

#### 担当範囲（概要）

- proto 定義
- Vue.js を用いたフロントエンド開発
- PHP を用いたバックエンド開発
- Redash を用いたデータ統計作業
- マスターデータ・ランキング用データのキャッシュ化
- バッチ処理の実装

#### 工夫したこと

- スマホアプリで使う API では、出来るだけレスポンスするデータをサーバー側で整形して渡していた。そのようにしていた理由は、表示を変更したい場合、アプリ側で整形していた場合はユーザーがアプリのアップデートをする必要があるが、サーバー側だった場合ユーザーがアップデートをしなくても表示を変更することが出来るから。
- ユーザーデータ以外のデータはほとんどリアルタイムで取得してこなくても使えるものだったので、アプリ高速化のためにデータの取得先にはなるべくキャッシュを使用するようにしていた。

#### 学べたこと

- ユーザーが多いサービスでも高速でレスポンスを返す技術（特にキャッシュ周りの知見）について得ることが出来た。キャッシュを多用するかどうかはサービスによって良し悪しあると思うが、get が多くて post の回数が少ない電子書籍サービスにはマッチしていると感じた。
- Protocol Buffers を用いていたため、スキーマ駆動開発に関する知見を得ることが出来た。バックエンドエンジニアとモバイルエンジニアで話し合いながら proto を定義するので、API に関する仕様の認識のズレを起こすことが少なく出来ることが分かった。

#### 使用技術・ツール

【バックエンド】

PHP 7.3 / MySQL / Percona XtraDB Cluster

【フロントエンド】

Vue.js / Element / pug / Sass

【インフラ】

nginx / Ansible / Zabbix

【その他（OS・ツール等）】

Ubuntu / Protocol Buffers / ClickHouse / Redash / GitHub / IntelliJ IDEA / Vagrant / Slack / Jira / Confluence / Sequel Ace

---

### 飲食系モバイルアプリの開発 2021 年〜(1 年)

#### 開発チーム

エンジニア 1 人（自分）　 PM 2 人

#### 担当範囲（概要）

- 技術選定
- Flutter を用いたモバイルアプリ開発
- Laravel を用いた決済機能の開発
- Laravel+Vue.js(TypeScript)を用いた CMS 開発
- Linter・Formatter の導入
- Docker を用いた環境構築
- AWS を用いたインフラ構築作業
- ECS タスクスケジューリングを使用したバッチ処理の実装
- AWS CodePipeline を用いた CI/CD

#### 工夫したこと

- 開発当初は手動でデプロイを行なっていたが、人為的ミスが発生しそうなので、AWS の CodePipeline を用いてソースコードを push 後自動でデプロイする仕組みを構築した。結果、コマンドミス等も無くなりデプロイに掛かる人的コストの削減にも繋がった。
- Linter・Formatter を用いて、コードの統一性・保守性を高めたこと。
- 何度も打つコマンドは Makefile に書いておいて、ネットやメモ書き等で調べなくても良いようにしていた。結果検索時間の短縮やコマンドのタイプミスの軽減に繋げることができた。

#### 学べたこと

- インフラを一から全て自分で作ったので、Docker や AWS 周りの知見を一気に伸ばすことが出来た。バックエンドの CI/CD パイプラインを構築したことは無かったが、開発体験が上がるため、今後も自分でインフラを構築する機会があったら採用していきたいと思った。

#### 使用技術詳細

【モバイル】

Flutter 2.10.4 / Dart 2.16.2

【フロントエンド】

Vue.js 3.2.25 / TypeScript 4.5.4 / Vite 2.7.2 / Tailwind CSS / Alpine.js

【バックエンド】

PHP 8.1.0 / Laravel 8.74.0 / MySQL 8.0

【AWS】

ECS / ECR / VPC / RDS / Route53 / ELB / SES / SMS / Cloud Watch / ACM / IAM / CodePipeline / CodeBuild / CodeDeploy / SNS

【Firebase】

Firebase Authentication

【その他ツール】

Docker / Docker Compose / Bitbucket / PAY.JP

---

### イラスト投稿系サービスの新規開発 2021 年〜 （8 ヶ月）

#### 開発チーム

エンジニア 5 人　 PM1 人

#### 担当範囲（概要）

- 外部 API を用いた決済機能の開発
- Vue.js を用いたフロントエンド開発
- PHP を用いたバックエンド開発
- マスターデータのキャッシュの作成
- バッチ処理の実装
- 単体テストの導入・作成

#### 工夫したこと

- 開発当初は複数人での開発であったことに加えて仕様自体が複雑だったこともあり、デグレが頻繁に発生してしまっていた。そこで、単体テストを導入することにより、デグレやバグを未然に防ぐことに繋げた。
- 外部 API を使用する際には、リクエスト内容とレスポンス内容を全てログに取っていたこと。外部 API で問題が起きた際には、内部のものより原因が特定しづらいことがあったり、API を提供している会社に問い合わせをする際にリクエスト内容とレスポンス内容を求められることが多かったので、なるべく情報を残しておくようにしていた。
- 高速化のため、SQL を使用する際には、なるべくインデックスが効くようなクエリを書くようにしていた。また、そもそもリアルタイムにデータベースからデータを引っ張ってくる必要のないものは、キャッシュ化して高速でデータを取得出来るようにしていた。

#### 学べたこと

- 複数人での開発はほぼ未経験に近かったので、チーム開発に関する知見が得られた。特に、今までの開発ではコードにコメントを残すことはほとんど無かったが、チーム開発を始めてからはコメントを残すことの大切さを知り、積極的にコメントを書くようになった。
- データの取得先にキャッシュを使用することが多かったので、キャッシュ周りの知見について得られた。レスポンスを高速にすることが出来るメリットがある一方、アプリケーションの複雑度が上がることやバグの発見のしづらさなど、キャッシュを採用することのデメリットも分かったので良かった。

#### 使用技術

【フロント】

vue 3.0.5 / Vite

【バックエンド】

PHP 8.1.0 / phinx / MySQL / Percona XtraDB Cluster

【インフラ】

Ansible / Nginx

【その他（OS・ツール等）】

Ubuntu / Vagrant / ClickHouse / GitHub / IntelliJ IDEA / Jira / Confluence / Sequel Ace

---

### 飲食系モバイルアプリの新規開発 2020 年~ (半年)

#### 開発チーム

エンジニア 1 人　 PM 2 人

#### 担当業務

- 技術選定
- UI/UX
- DB 設計
- 静的解析の導入
- ドキュメント作成作業
- ストア申請作業(App Store・Google Play)
- CI/CD（Codemagic を用いた CI/CD パイプラインの構築）
- TestFlight を用いた社内配布
- Firebase Authentication を用いた認証機能の開発
- Riverpod(hooks_riverpod)+StateNotifier+freezed を用いた状態管理
- barcode_scan を利用した QR 読み取り機能
- Google Maps API の導入
- google_maps_flutter を利用した GoogleMap 表示機能
- location を用いた現在地所得機能
- flutter_native_splash でのスプラッシュ画面作成
- Firestore を用いた DB 作成
- google_sing_in を用いた Google ログイン機能の実装
- AWS(EC2・VPC・Route53・IAM・ELB・S3・CloudFront・CloudWatch)を用いたインフラ構築作業
- Python(qrcode ＋ pilolw)を用いた QR 生成作業
- shared_preferences を用いた端末に情報を保存する機能の実装
- pacage_info を用いたパッケージ情報呼び出し機能
- Firebase Hosting による静的サイトの配信
- sign_in_with_apple を用いた Apple ログイン機能
- Cloud Functions と FCM を用いたプッシュ通知機能

#### 工夫したこと

- 基本的にはクラウドには GCP(Firebase)を用いていたが、ストレージには Firebase が提供している Cloud Storage ではなく、AWS の S3 を採用したこと。このプロジェクトにおいては、S3 と Cloud Storage と比べた場合に、S3 の方が料金的に得だったので運用コストを下げることが出来た。
- API から取得してきたデータをキャッシュしておくことによって、2 回目以降の画面の読み取りの高速化を行ったこと。
- 静的解析を導入することによって、自動でコードの統一性と高められるようにしたこと。
- 実験的なプロジェクトで高速で開発を行う必要があったため、工数を減らすためにバックエンドに Firebase を用いたこと。Flutter とも相性が良かったため、3 ヶ月ほどで大枠作り終えることが出来た。
- 一人での開発であったが、後から人が入ってきても大丈夫なようにドキュメントを書いておいたこと。

#### 学べたこと

- DB に Cloud Firestore を使っていたため、NoSQL に関する知見を得ることが出来た。RDB と違い SQL の知識があまり無くてもざっくりサービスが作れるメリットがある一方、検索性に優れていないというデメリットもあることも知ることが出来た。
- クロスプラットフォーム開発に Flutter を採用するメリットデメリットを知ることが出来た。Flutter 自身にかなり多くの Wiidget が定義されているため、自分であれこれ機能を作らなくても良く開発効率が良いこと。また、ホットリロードがデフォルトで用意されている点などのメリットがあることが分かった。その一方、ネイティブと比べるとパフォーマンス面で劣る点や、新しい技術過ぎて情報が少ない点などのデメリットがあることも分かった。

#### 使用技術詳細

【モバイル】

Flutter 1.22.4 / Dart 2.10.4

【AWS】

EC2 / VPC / Route53 / IAM / ELB / S3 / CloudFront / CloudWatch

【Firebase】

Firebase Authentication / Cloud Firestore / Firebase Analytics / Firebase Hosting / Cloud Functions / Cloud Messaging / Remote Config / Firebase Crashlytics

【その他】

Android Studio / Codemagic / Bitbucket / Python 3.8.5 / TestFlight / Testmagic / Docker / Node.js12
