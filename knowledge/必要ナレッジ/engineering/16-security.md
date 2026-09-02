# 16｜セキュリティ

## 目的
小規模Web/アプリ案件で重大事故を起こさないための最低限の設計・実装判断を身につける。

## 目標レベル
**Lv2〜3。** セキュリティ専門家になる必要はないが、基本リスクを発見し、必要なら専門家に渡せる。

## 必要知識
- CIA（機密性・完全性・可用性）の概念
- OWASP Top 10概要
- XSS / CSRF / SQL Injection
- authentication / authorization
- password hashの概念
- HTTPS/TLS
- API key / secret / credential管理
- environment variables / GitHub Secrets
- Firebase Security Rules
- CORSの概要
- input validation
- file uploadリスク
- dependency update
- backup
- loggingで個人情報を出しすぎない

## ここまでできれば十分
- secretをGitにcommitしない
- clientに置いてよいAPI key/悪いsecretを区別する
- 権限チェックをserver/rules側に置ける
- 基本的なWeb脆弱性を説明できる
- 顧客情報を扱う機能で追加注意点を列挙できる

## 習得方法
1. OWASP Top 10を一巡
2. PortSwigger Web Security Academyの入門演習を数本
3. Firebase RulesをEmulatorで検証
4. 自分のrepoでsecret/dependency/permissionレビュー

## 実践課題
既存アプリ1つを対象に簡易security review checklistを作り、改善点を洗い出す。

## 完了判定
- [ ] OWASP主要リスクをざっくり説明できる
- [ ] credential漏洩対策ができる
- [ ] 認可漏れをレビューできる
- [ ] security上自分で判断できないケースを識別できる
