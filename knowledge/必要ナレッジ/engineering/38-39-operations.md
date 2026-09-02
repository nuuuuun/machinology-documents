# 38-39｜保守運用・障害対応

## 目的
納品後のサイト・アプリを安定運用し、障害時に慌てず原因を切り分ける。

## 目標レベル
**Lv3。** 監視・バックアップ・更新・障害一次対応を自分で標準化できる。

## 必要知識
- availability / incident / maintenance
- backup、restore、retention
- domain/SSL期限
- dependency update
- logの読み方
- monitoring / uptime check
- error tracking（Crashlytics等）
- browser/network/server/app/DBの切り分け
- HTTP status code
- rollback
- severity / priority
- 顧客への障害連絡
- postmortemの考え方

## 基本切り分け順
1. 全員か一部ユーザーか
2. DNS/ネットワークか
3. hosting/serverか
4. frontend/appか
5. API/DB/authか
6. 最近の変更は何か

## ここまでできれば十分
- バックアップから復旧できる
- 主要サービスのstatus/logを確認できる
- 直前deployをrollbackできる
- 障害状況を顧客へ簡潔に説明できる

## 習得方法
- 自分のサイトにuptime monitorを設定
- 意図的に設定を壊したテスト環境で復旧練習
- 障害対応runbookを作る

## 実践課題
「サイトが見えない」「ログインできない」「一部データが表示されない」の3ケースで切り分け手順を書く。

## 完了判定
- [ ] backup/restoreを試したことがある
- [ ] logから一次原因を追える
- [ ] rollbackできる
- [ ] 障害連絡テンプレートを持っている
