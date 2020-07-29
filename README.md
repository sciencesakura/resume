# 職務経歴書

最終更新日: 2020-07-29（最新版は https://github.com/sciencesakura/resume を参照下さい）

## 基本情報

* 名前: Yosuke Nishikawa

* 拠点: 東京

## スキル

### 言語

#### プロダクト・コードが書け, 他人のコードを評価できる

* Java

#### プロダクト・コードが書ける

* bash

* Groovy

* JavaScript

* Kotlin

#### 読み書きはできる

* C

* TypeScript

### フレームワーク／ライブラリ

* Spring Framework (Boot/WebMVC)

* MyBatis

* JUnit

### 得意

* 他のメンバに対する技術サポート

* テスト, デプロイの自動化・省力化

### 資格

* LPIC-1 (2020年)

* IPA ネットワークスペシャリスト (2016年)

* IPA 応用情報技術者 (2014年)

## 経歴

### 2019-09 〜 2019-11: 自動音声案内システム新規導入

クレジットカード会社の電話窓口へのIVR新規導入

|チーム規模|アプリ規模|
|-|-|
|6人|APIx3, 画面x4, バッチx3|

|OS|言語|MW|FW|ORM|その他|
|-|-|-|-|-|-|
|RHEL|Java 8<br>JavaScript<br>bash|Apache<br>Tomcat<br>PostgreSQL|Spring Boot<br>Bootstrap|DBFlute|JUnit 5<br>VirtualBox<br>Git|

* コード, 運用設計のレビュアを担当

* フレームワークの他, GitやLinuxコマンドの使い方についてなど開発メンバをサポート

* ミドルウェア担当としてステージング／本番環境のTomcat, Apache構築. その他cronによるバッチスケジューリングやlogrotate設定等アプリに必要なサーバ上の作業全般を担当

* 運用チームと調整しMavenのタスク定義とデプロイ手順をリファクタリング, ビルド及びデプロイを省力化した

* CSVアップロード画面を高速化（レコード数10万件級を10分→30秒）

* リリースを迎えプロジェクト離脱

### 2019-06 〜 2019-08: 通関業務システム改修

総合商社の既存システムのフレームワーク移行（Struts→Spring）と機能改修

|チーム規模|アプリ規模|
|-|-|
|5人|画面x20, 帳票x15|

|OS|言語|MW|FW|ORM|その他|
|-|-|-|-|-|-|
|Windows|Java 8<br>JavaScript|Oracle 12c|Struts 1<br>Spring Framework<br>jQuery|-|biz-Stream<br>JUnit 4<br>Git|

* 期間限定のお手伝いとして参画

* 機能追加要望に伴う画面及び帳票の設計を担当

* 他社が導入したシステムの更改案件の受注であり, 使用している帳票パッケージの有識者が社内にいなかった為エンジンの仕様やデザインツールの使用法を調査しメンバへの展開を行った

### 2019-04 〜 2019-05: 営業支援システム改修

放送事業者既存システムのハードウェア刷新とOS, ミドルウェアのバージョンアップ

|チーム規模|アプリ規模|
|-|-|
|7人|APIx20, APサーバx10, DBサーバx4|

|OS|言語|MW|FW|ORM|その他|
|-|-|-|-|-|-|
|Windows|Java 8<br>C#<br>PowerShell|Apache<br>Tomcat<br>SQL Server|-|-|JMeter<br>Subversion|

* 期間限定のお手伝いとして参画

* 性能試験の計画と実施を担当

* 使用実績を元に繁忙期+αのアクセス数を想定, 本番環境のログから現実感のあるHTTPリクエストボディを生成し, JMeterで試験, 結果のレポートを行った

### 2019-01 〜 2019-03: 会計事務システム改修

中央官庁の会計システムの更改

|チーム規模|アプリ規模|
|-|-|
|10人|画面x20|

|OS|言語|MW|FW|ORM|その他|
|-|-|-|-|-|-|
|RHEL|Java 7|Apache<br>WebLogic<br>Oracle 11g|TERASOLUNA<br>Spring Framework|MyBatis|Subversion|

* 結合試験のシナリオ作成と実施を担当

### 2018-01 〜 2018-10: 料金計算システム新規導入

電力会社へのパッケージ新規導入とカスタマイズ

|チーム規模|アプリ規模|
|-|-|
|30人|画面x10, バッチx30|

|OS|言語|MW|FW|ORM|その他|
|-|-|-|-|-|-|
|Windows|Java 6<br>JavaScript|Interstage<br>PostgreSQL|INTARFRM|-|JUnit 4<br>Subversion|

* 設計開発において, 仕様の取りまとめ担当の一員としてドメインエキスパートからのヒアリングや集めた要件の整理, 開発担当者への説明, レビュアを担当

* 結合試験において, 試験計画の作成や進捗管理を担当. 一時的にサブリーダーを務める

* 経験の浅い方が多く品質の懸念やスケジュールの遅延があったが, 自身を含め年長者をそばに付けるよう配置し, いざとなったら作業を巻取れるようにして対処した

### 2016-04 〜 2017-12: 営業取引システム改修

大手総合商社の既存システムにグループ子会社が統合されることに伴う機能追加改修

|チーム規模|アプリ規模|
|-|-|
|10人|APIx10, 画面x20, バッチx10|

|OS|言語|MW|FW|ORM|その他|
|-|-|-|-|-|-|
|RHEL|Java 7<br>JavaScript<br>bash|WebLogic<br>Oracle Service Bus<br>SAP ERP<br>Oracle 12c|Oracle ADF<br>Seasar2|JPA<br>S2Dao|JUnit 4<br>SoapUI<br>Subversion|

* 広く画面, API, バッチ, シェルスクリプトの設計開発〜試験を担当

* 結合試験においては入力値の多様さからケース数が多量になることが予想された為自動化を提案, APIをコールしレスポンスとDBを検証するツール（PowerShell製）を作成, 試験工数を削減した

* 上記ツールは後にSoapUI+Groovyに移植し性能試験にて活用

### 2015-05 〜 2016-03: 需要予測システム改修

食品メーカー既存システムの機能追加改修

|チーム規模|アプリ規模|
|-|-|
|3人|画面x5, バッチx10|

|OS|言語|MW|FW|ORM|その他|
|-|-|-|-|-|-|
|Windows|Java 6<br>JavaScript<br>PL/SQL|FOREMAST<br>Oracle 12c|intra-mart<br>jQuery|MyBatis|Subversion|

* 新設画面の設計開発〜試験を担当

* テーブルレイアウト変更に伴うDBのデータ移行計画と移行ツール（Groovy+PL/SQL製）を作成

* リリース後は保守担当として顧客からの問い合わせや障害に対応

### 2014-12 〜 2015-05: 通関業務システム改修

商社既存システムのHW刷新とOS, ミドルウェアのバージョンアップ

|チーム規模|アプリ規模|
|-|-|
|3人|画面x10|

|OS|言語|MW|FW|ORM|その他|
|-|-|-|-|-|-|
|Windows|Java 6|Apache<br>WebSphere<br>Tomcat<br>SQL Server|Struts 1|Torque|Hyper-V<br>Subversion|

* バージョンアップの調査, 見積, 実作業を担当

* ステージング環境の構築

### 2014-10 〜 2014-11: マスタ管理システム新規導入

化学メーカーへのマスタ管理パッケージ新規導入

|チーム規模|アプリ規模|
|-|-|
|3人|-|

|OS|言語|MW|FW|ORM|その他|
|-|-|-|-|-|-|
|Windows|Java 6<br>JavaScript<br>C#|Oracle 12c|intra-mart<br>jQuery<br>VSTO|MyBatis|Subversion|

* 客先で稼働中のフレームワークに合わせたパッケージのグレードダウンを担当（intra-mart 8→7, Java 7→6）

* ステージング環境の構築

### 2014-04 〜 2015-05: 通関業務システム保守

商社既存システムの保守

|チーム規模|アプリ規模|
|-|-|
|3人|画面x10|

|OS|言語|MW|FW|ORM|その他|
|-|-|-|-|-|-|
|Windows|Java 1.3|Apache<br>WebSphere<br>SQL Server|Struts 1|Torque|Hyper-V<br>CVS<br>Subversion|

* 保守担当として顧客からの問い合わせや障害に対応

* リポジトリサーバを刷新（CVS→Subversion）

* Eclipse上にて手動で行っていたビルド, デプロイ作業をMaven導入により省力化

### 2014-01 〜 2014-03: 文書管理システム新規導入

大手建設業での自社システム内製

|チーム規模|アプリ規模|
|-|-|
|13人|-|

|OS|言語|MW|FW|ORM|その他|
|-|-|-|-|-|-|
|RHEL|Java 7<br>JavaScript|Apache<br>JBoss<br>Oracle WebCenter Content<br>Oracle 11g|Spring Framework<br>intra-mart<br>Bootstrap|MyBatis|Subversion|

* システム試験のシナリオ作成と実施を担当

* 英語公用語（会話は日本語だが設計書やアプリUIは英語）

### 2013-04 〜 2013-12: 購買管理システム新規導入

化学メーカーへのERPパッケージ新規導入

|チーム規模|アプリ規模|
|-|-|
|11人|画面x10, バッチx5|

|OS|言語|MW|FW|ORM|その他|
|-|-|-|-|-|-|
|Windows|Java 6<br>JavaScript|SAP ERP<br>Oracle 11g|intra-mart<br>jQuery|MyBatis|Subversion|

* 画面, 共通部品の設計開発〜試験を担当

* フレームワークについて開発メンバをサポート

### 2012-06 〜 2013-03: 経費精算システム新規導入

機械メーカーへのERPパッケージ新規導入

|チーム規模|アプリ規模|
|-|-|
|7人|画面x15, バッチx5, 帳票x10|

|OS|言語|MW|FW|ORM|その他|
|-|-|-|-|-|-|
|Windows|Java 6<br>JavaScript|SAP ERP<br>SQL Server|intra-mart|iBatis|JasperReports<br>Subversion|

* 画面, 帳票の設計開発〜試験を担当

* リリース後は保守担当として顧客からの問い合わせや障害に対応
