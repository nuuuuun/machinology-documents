# 07-08｜ドメイン・DNS・ホスティング

## 目的
新規公開・移管・SSL・メール共存を事故なく対応する。

## 目標レベル
**Lv3。** 顧客ドメインを触る前に、変更影響を予測して手順化できる。

## 必要知識
### ドメイン/DNS
- domain / registrar / nameserver
- DNS zone
- A / AAAA / CNAME / MX / TXT / NS
- TTL
- apex / www / subdomain
- DNS propagation
- domain transferとnameserver変更の違い

### SSL/HTTPS
- TLSの役割
- certificate、Let's Encrypt
- HTTP→HTTPS redirect
- mixed content

### Hosting
- rental server / static hosting / VPS / serverlessの違い
- Xserver、GitHub Pages、Cloudflare Pages、Firebase Hosting等の位置付け
- FTP/SFTP/SSHの基本
- backupとrollback

### 移管
- 現行DNSを必ず記録
- Webとメールの依存関係を確認
- 切替前TTL、切替、動作確認、戻し手順

## ここまでできれば十分
- DNSレコードを読んで役割を説明できる
- Webだけ移管しメールは現状維持できる
- SSLエラーを基本切り分けできる
- 静的サイトを独自ドメインで公開できる

## 習得方法
1. Cloudflare Learning / 各ホスティング公式DocsでDNS基礎
2. 自分のテスト用サブドメインでA/CNAME/TXTを変更
3. GitHub Pages等へ独自ドメイン接続
4. 架空の移管手順書を作る

## 実践課題
`test.example.com` 相当のサブドメインを静的ホスティングへ向け、SSL化し、DNS変更前後を記録する。

## 完了判定
- [ ] 主要DNSレコードを説明できる
- [ ] Web移管時にメール影響を確認できる
- [ ] 独自ドメイン+HTTPS公開ができる
- [ ] rollback手順を作れる
