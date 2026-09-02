# 09-10｜Git・GitHub・CI/CD

## 目的
コード変更を安全に管理し、テスト・公開を再現可能にする。

## 目標レベル
**Lv3。** 一人開発でもbranch/PR/CI/CDを標準運用できる。

## 必要知識
### Git
- repository、working tree、stage、commit
- clone / pull / fetch / push
- branch / merge / rebase
- conflict解消
- reset / revert / restoreの使い分け
- tag

### GitHub
- issue、PR、review
- branch protectionの概念
- release
- Secrets / Environments

### CI/CD
- workflow、trigger、job、step
- GitHub Actions YAML
- build / test / deploy
- secretをコードに置かない
- deploy失敗時の確認

## ここまでできれば十分
- feature branch→PR→mergeを迷わず行える
- conflictを自力解決できる
- revertで安全に戻せる
- pushで静的サイトを自動deployできる
- Actions失敗ログから原因箇所を特定できる

## 習得方法
- Pro Gitの基礎章
- GitHub Skills / Actions公式Docs
- MachinologyサンプルrepoでPR運用
- 自動deploy workflowを1本構築

## 実践課題
GitHub Actionsでmainへのmerge時にbuild/check→deployするworkflowを作る。

## 完了判定
- [ ] branch戦略を説明できる
- [ ] conflictを解消できる
- [ ] revert/resetの違いが分かる
- [ ] Secretsを使ったActionsを作れる
- [ ] CI/CD失敗をログから追える
