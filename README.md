# resume

## 職務経歴(概要)
具体的な社名は伏せつつ、新しい順に記載しています。

* Webアプリ/スマートフォン向けアプリの自社プロダクト開発および受託開発の企業(2019/07~現在)
	* スキルを認められグループ会社から転籍。
	* サーバーサイド開発リーダーとして要件定義からプロジェクトに参画し、設計、開発、テストまで関わり、今後リリースを控えている。主にAPI開発、バッチ開発、インフラ構築を担当。
	* 新人エンジニアの教育に携わる。
* 現在勤めている企業のグループ会社(業務内容は同じ  2018/09~2019/06)
	* サーバーサイドとフロントエンドの開発に携わる。
* プログラミング学習に取り組む(2018/05~2018/08)
* ポストプロダクション企業にてMAエンジニアとして従事(2013/04~2018/05)

## 職務経歴(詳細)
新しい順に記載しています。

### スマートフォンアプリおよびWebサイトのサーバーサイド開発(2019/10~現在)

#### 担当内容
* サーバーサイドチームリーダーとして要件定義、設計、開発、テストを経験。
* 開発用のベース環境構築。
* OpenID ConnectのRP側として、主に認証系APIの設計と開発(認証トークン発行、検証、トークン管理など)。
* アプリケーションで使用するDB(MySQL、DynamoDB、Redis)の全てのテーブル設計、KVS設計およびマイグレーション設定の作成。
* CloudFormationを用いたAWSインフラ環境の構築とリソース管理。
* [openapi-generator](https://github.com/OpenAPITools/openapi-generator)をカスタマイズし、Swaggerからのコードの自動生成の仕組みを作成。
* CI/CD構築。

### 従業員呼び出しシステムのサーバーサイドとフロントエンド開発(2019/03~2020/03)

#### 担当内容
* サーバーサイドとフロントエンドの開発用のベース環境構築。
* サーバーサイドのAPIを20本程開発。
* SPAのフロントエンド画面および非同期APIリクエスト処理を実装。
* DB(MySQL)の既存テーブル設計の見直しと新規テーブルの設計。

## 技術スキル

### 言語

名称 | 技術レベル
-- | --
Kotlin 1.4 | API / バッチの設計と開発を半年経験。APIは20本程、バッチは3本程実装。最も得意な言語。
Java 11 | バッチの設計と開発を半年経験。最近はKotlinをメインで使用しており、OSSをカスタマイズする際に少し触れる程度。
Scala 2.13 | APIの設計と開発を1年経験。APIは20本程実装。半年ほど触れていない。
Ruby 2.3.7 | 業務経験無し。プログラミングの勉強を始めたての頃に少し触れた程度。
TypeScript 3.7.2 | フロントエンド画面および非同期APIリクエスト処理の開発を1年経験。半年ほど触れていない。

### フレームワーク

名称 | 技術レベル
-- | --
Spring Boot (2.1.1.RELEASE) | JavaとKotlinによる開発で1年使用。開発のベース環境構築が出来る。
Play Framework (2.7.1) | Scalaによる開発で1年使用。開発のベース環境構築を経験。半年ほど触れていない。
Vue.js (Vue CLI 3.7.0) | TypeScriptによる開発で1年使用。開発のベース環境構築を経験。半年ほど触れていない。
Ruby on Rails (5.2.0) | 業務経験無し。プログラミングの勉強を始めたての頃に少し触れた程度。

### AWS

名称 | 技術レベル
-- | --
CloudFormation | 開発環境、検証環境、本番環境構築の共通コード化とデプロイを経験。スラスラ書けるわけではなく、公式ドキュメントを読みながら作業ができる。
ECS(Fargate) | 環境に応じたサービス設定、タスク定義が可能。初期は手動で設定していたが、最近は全てCloudFormationで管理している。
DynamoDB | テーブル設計に応じてCloudFormationによる管理が可能。
KMS | 対称キーのみ使用経験あり。Java SDKを使用した暗号化および復号化処理を実装可能。
CloudWatch | 監視内容に応じたメトリクス、アラームの作成が可能。CloudWatch Synthetics、Chatbot、SNSを組み合わせたメール通知、Slack通知の仕組みの作成経験あり。
Lambda | CloudWatchアラームによって発火するエラー通知処理の作成経験あり。
その他使用経験のあるリソース | ALB, EC2, TargetGroup, SecurityGroup, IAM, CloudFront, WAF, S3など。

### DB

名称 | 技術レベル
-- | --
MySQL | テーブル設計が可能。Java Persistence APIまたはDoma2を用いたデータベース連携処理を実装可能。
DynamoDB | 使用目的に応じたテーブル設計(項目定義、GSI設定、インデックス設定)が可能。Java SDKを使用したリクエスト処理を実装可能。
Redis | 認証トークン管理およびAPIキャッシュの設計と実装の経験あり。Spring Data Redisを用いた連携処理を実装可能。
Oracle Database | MyBatisを用いた簡単なSELECT処理の実装経験あり。

### その他

名称 | 技術レベル
-- | --
Docker | jarファイルのdockerイメージ化とECRプッシュ、ECSでの稼働経験有り。MySQL、Redis、AWS X-Rayコンテナの環境構築、docker composeの設定経験有り。

## 資格

名称 | 取得年月
-- | --
基本情報技術者 | 2019/11

実務経験重視と考えているが、情報系の学部出身ではない為、基礎知識を体系的に身に着ける目的で取得。
