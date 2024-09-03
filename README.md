# 業務経歴書

## スキル

※　実務で使用したもののみ記載

### 言語

Go / Node.js / TypeScript / PHP / Dart / Python

### フレームワーク・ライブラリ

Gin / echo / go-zero / ent / GORM / Nest.js / Laravel / Lighthouse / Next.js / Nuxt.js / Flutter

### DB

MySQL / PostgreSQL / CloudFirestore

### Firebase

Firebase Authentication / Cloud Firestore / Firebase Analytics / Firebase Hosting / Cloud Functions / Cloud Messaging / Remote Config / Firebase Crashlytics

### AWS

ECS / Fargate / ECR / VPC / RDS / Route53 / ELB / SES / SMS / Cloud Watch / ACM / IAM / CodePipeline / CodeBuild / CodeDeploy / EC2 / S3 / CloudFront / SNS / OpsWorks / Batch / Transfer Family / Lambda / Secrets Manager / NAT Gateway / Cognito

### その他ツール等

GraphQL / Protocol Buffers / Docker / Docker Compose / GitHub Actions / TestFlight / Codemagic / Redash / Squid / nginx / Ansible

---

## 業務経歴

※ 掛け持ちで仕事をしているので、期間に被りがある場合があります。


### 施設入室管理システムやNFTアプリの開発など 2022年 ~ 2024年(2年)

#### 使用技術

【バックエンド】

Go 1.18 / Node.js 21.0.0 / TypeScript / Nest.js / Prisma / Laravel / Lighthouse / go-zero

【フロントエンド】

Next.js / TypeScript / Tailwind CSS / aspida / SWR

【AWS】

Cognito

【Firebase】

Firebase Authentication

【その他ツール】

Docker / GitHub Actions / PostgreSQL / Alchemy / Vercel / OpenAPI / dbdiagram / Swagger / MySQL

#### 主な担当業務
- Go、Node.js、PHPを用いたバックエンド開発
- Next.jsを用いたフロントエンド開発
- DB設計作業
- GraphQLのスキーマ定義
- Linter・Formatter の導入
- GitHub Actionsを用いたCIの構築
- Dockerを用いたローカル用環境構築
- マルチステージビルドを用いたDockerイメージの軽量化(本番・開発環境)
- 3Dセキュア決済への移行作業
- Cognitoを用いた認証機能の実装
- テスト基盤の作成及びテストコード実装(バックエンド・フロント)

#### 参加プロジェクト一覧
以下より参加プロジェクトの詳細を確認できます。

<details>
<summary>NFTアプリの開発</summary>

##### 担当範囲（概要）
- Nest.jsを用いたバックエンド開発
- Next.jsを用いたフロントエンド開発
- ブロックチェーンとの連携
- DB設計作業
- バックエンドのアーキテクチャ設計
- Linter・Formatter の導入
- テスト基盤の作成及びテストコード実装(バックエンド・フロント)
- Cognitoを用いた認証機能の実装
- GitHub Actionsを用いたCI/CDの構築
- Dockerを用いたローカル用環境構築
- マルチステージビルドを用いたDockerイメージの軽量化(本番・開発環境)
- コードレビュー

##### 使用技術・ツール

【バックエンド】
Node.js 21.0.0 / TypeScript / Nest.js / Prisma / Jest

【フロントエンド】

Next.js / TypeScript / Tailwind CSS / aspida / SWR / Jest

【AWS】

Cognito

【その他ツール】

Docker / GitHub Actions / PostgreSQL / Alchemy / Vercel / OpenAPI

#### 工夫したこと・発揮したバリュー

- マルチステージビルドを用いることにより、Dockerイメージのサイズを軽量化を行った。
- バックエンドの担当者が自分一人だったため、アーキテクチャ設計から実装まで一貫して担当し、プロジェクトの技術的な部分をリードすることが出来た。
- GitHub Actionsを用いて、PR作成時に自動でテストや静的解析を行うようにしたことにようにした。これによって、コードの品質や安全性を自動的に保つ仕組みを構築した。
- ブロックチェーン関連の機能の実装は初めての経験だったが、早期にキャッチアップすることが出来、バックエンドとの連携処理もスムーズに実装することが出来た。

</details>

<details>
<summary>施設管理アプリの開発</summary>

##### 担当範囲（概要）
- Laravel (Lighthouse) を用いたバックエンド開発
- Next.jsを用いたフロントエンド開発
- DB設計作業
- GraphQLのスキーマ定義
- Linter・Formatter の導入
- GitHub Actionsを用いたCIの構築
- 3Dセキュア決済の実装
- テストコード実装

##### 使用技術・ツール

【バックエンド】

PHP 8.2 / Laravel 8.8 / Lighthouse

【フロントエンド】

Next.js / TypeScript

【Firebase】

Firebase Authentication

【その他ツール】

Docker / GitHub Actions / dbdiagram / GraphQL / MySQL

#### 工夫したこと・発揮したバリュー

- 既存プロジェクトに静的解析・フォーマッターなどが導入されていない状態だったので、早急に導入することにより、コードの統一性・保守性を高めた。
  また、CIが導入されていなくマージ前に安全なコードであるかのチェックがされていなかったので、GitHub Actionsを用いて自動で静的解析・テストを実行するようにした。
- テスト実行で並列テストを使うことにより、テスト実行時間を短縮出来るようにした。
- 手続き型のコードをデザインパターンを用いてリファクタリングすることにより、コードの可読性を高めた。

</details>

<details>
<summary>診断アプリの開発</summary>

##### 担当範囲（概要）
- Go (go-zero) を用いたバックエンド開発
- Next.jsを用いたフロントエンド開発
- DB設計作業
- テストコード実装

##### 使用技術・ツール

【バックエンド】

Go 1.18 / go-zero

【フロントエンド】

Next.js / TypeScript

【Firebase】

Firebase Authentication

【その他ツール】

Docker / GitHub Actions / dbdiagram / Swagger / MySQL

#### 工夫したこと・発揮したバリュー
- 参画時は週3の稼働であったが、早期に仕様のキャッチアップを行い実装に入ることが出来た。結果として、プロジェクトの進捗に貢献することが出来た。

</details>

---

### 受託開発企業での開発業務(複数プロジェクト参加したものを一つにまとめてあります) 2023年 ~ (8ヶ月)

##### 担当範囲（概要）
- Go (echo) を用いたバックエンド開発
- Next.js・Nuxt.jsを用いたフロントエンド開発
- DB設計作業
- OpenAPIを用いたAPI設計

#### 使用技術・ツール

【バックエンド】

Go 1.20 / echo / ent

【フロントエンド】

Next.js / Nuxt.js / TypeScript

【Firebase】

Firebase Authentication

【その他ツール】

Docker / OpenAPI　/ GitHub Actions

#### 工夫したこと・発揮したバリュー

- entは初めての使用だったが、今までのORMを使用した経験を活かし、早期にキャッチアップすることが出来た。
- テスト基盤の作成やDB設計など、プロジェクトのコア部分を担当したことにより、プロジェクトの技術的な部分をリードすることが出来た。

---

### ファッション系アプリの開発 2022 年 ~  (7 ヶ月)

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

---

### イラスト投稿系サービスの新規開発や漫画アプリの保守開発など 2021 年〜 （1年 2ヶ月）

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

#### 使用技術

【フロント】

vue 3.0.5 / Vite

【バックエンド】

PHP 8.1.0 / phinx / MySQL / Protocol Buffers

【インフラ】

Ansible / Nginx

【その他（OS・ツール等）】

Ubuntu / Vagrant / ClickHouse / GitHub / IntelliJ IDEA / Jira / Confluence / Sequel Ace

---

### 飲食系モバイルアプリの開発 2020 年〜(1年半)

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
