# 20-21｜App Store・Google Play・審査

## 目的
顧客アプリを署名・テスト配布・審査提出・公開・更新まで進められるようにする。

## 目標レベル
**Lv2〜3。** ガイドライン全文暗記ではなく、案件ごとに必要項目を調査し提出できる。

## 必要知識
### iOS
- Apple Developer Program
- Bundle ID、certificate、provisioning、signing
- App Store Connect
- TestFlight
- App Privacy
- review submission
- Sign in with Apple要件
- account deletion、permission、IAPの主要ルール

### Android
- Play Console
- package/applicationId
- signing key / app bundle(AAB)
- internal/closed/open testing
- Data safety
- production release

### 共通
- version/build number
- screenshot、description、privacy policy
- permission理由
- rejection対応
- release/update運用

## ここまでできれば十分
- 新規アプリをTestFlight/内部テストへ出せる
- 審査提出に必要なメタデータを揃えられる
- reject理由を読み修正方針を決められる
- 更新版を安全にreleaseできる

## 習得方法
- Apple/Google公式のsubmission guideを主教材にする
- 自作アプリを1本、テスト配布→審査まで通す
- rejected caseは都度ガイドライン原文を確認

## 実践課題
チェックリスト形式の「Machinologyアプリ公開手順書」を作る。

## 完了判定
- [ ] iOS/Androidテスト配布ができる
- [ ] signing関連用語を説明できる
- [ ] privacy/data safetyを入力できる
- [ ] 審査rejectへ対応できる
