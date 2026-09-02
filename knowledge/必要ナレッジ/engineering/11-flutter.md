# 11｜Flutter

## 目的
小規模業務アプリ・店舗アプリをiOS/Android共通コードで設計、実装、実機確認できるようにする。

## 目標レベル
**Lv3。** UIだけでなく状態・非同期処理・ナビゲーション・端末差まで含めて小規模アプリを完成できる。

## 必要知識
- Dart基本構文、null safety、class、Future/Stream
- Widget tree、Stateless/Stateful
- layout（Row/Column/Flex/ListView/Stack）
- navigation/routing
- form、validation
- state management（既存プロジェクト方式を1つ深く）
- async/await、HTTP
- local storage
- package管理、pubspec
- lifecycle
- permission
- responsive/adaptive UI
- build flavor/configの概要
- iOS/Android実機debug

## ここまでできれば十分
- CRUD画面を作れる
- loading/error/empty状態を実装できる
- API/Firebaseと接続できる
- state管理を理由付きで整理できる
- iOS/Android双方でbuild・実機確認できる

## 習得方法
1. Flutter公式tutorial
2. 既存の自作アプリを読み、Widget→state→data flowを図示
3. 小型CRUDアプリを1つゼロから作る
4. 実機でpermissionやplatform差を確認

## 実践課題
ログイン→一覧→追加→編集→削除を持つ簡単な業務メモアプリを作る。

## 完了判定
- [ ] Widget構成を自分で設計できる
- [ ] state管理を理解して修正できる
- [ ] 非同期エラー処理ができる
- [ ] iOS/Android実機でdebugできる
- [ ] release buildまで進められる
