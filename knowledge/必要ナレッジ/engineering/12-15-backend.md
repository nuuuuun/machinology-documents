# 12-15｜Firebase・DB・API・認証認可

## 目的
認証付きクラウドアプリのデータ設計とアクセス制御を安全に構築する。

## 目標レベル
**Lv3。** 「動く」だけではなく、誰がどのデータを読めるかまで設計できる。

## 必要知識
### Firebase
- Auth（email/Google/Apple）
- Firestore collection/document/query
- Storage
- Cloud Functionsの用途
- Crashlytics/Analytics概要
- Security Rules

### DB
- entity、PK/FK、1:N、N:N
- index、query
- transactionの概念
- Firestoreの非正規化・読み取りコスト

### API
- REST、GET/POST/PUT/PATCH/DELETE
- request/response、JSON、status code
- header、Bearer token
- pagination、rate limit
- webhook

### 認証/認可
- authentication vs authorization
- session/JWT概要
- role/owner/member権限
- least privilege

## ここまでできれば十分
- user/group/dataのモデルを設計できる
- Firebase Rulesで他人データを遮断できる
- REST APIと認証付き通信ができる
- webhook連携を理解できる
- DB設計時に読み取りパターンを先に考えられる

## 習得方法
- Firebase公式Docs + Emulator Suite
- Firestore Rules unit testのサンプル
- REST APIはPostman/Bruno等で手動確認
- 自作アプリのデータ構造をER図/ドキュメント化

## 実践課題
家族グループ型アプリを題材に、user/group/membership/logのデータモデルとRulesを作る。

## 完了判定
- [ ] 認証と認可の違いを説明できる
- [ ] Firestoreデータ構造を設計できる
- [ ] Rulesでowner/member制御できる
- [ ] APIエラーをstatus codeから切り分けられる
- [ ] secretをclientに置いてはいけないケースが分かる
