# 48｜メール基盤

## 目的
ドメイン・Web移管時に顧客メールを停止させないため、メール配送の仕組みを理解する。

## 目標レベル
**Lv2。** メールサーバー専門家ではなく、DNSとメール設定の影響を判断できる。

## 必要知識
- SMTP / IMAP / POP
- mail server / mailbox
- MX
- SPF
- DKIM
- DMARC
- From / Return-Path概要
- DNS切替とメール影響
- Microsoft 365 / Google Workspace / rental server mailの違い
- forwarding
- spam判定の基本

## ここまでできれば十分
- MXを見て現在のメール提供元を推測できる
- Web移管時にMX/TXTを維持できる
- SPF/DKIM/DMARCの役割を説明できる
- メール不達時にDNS/送信/受信のどこを見るか分かる

## 習得方法
- Google Workspace / Microsoft / Cloudflareのメール認証解説
- `dig`等で実ドメインのMX/TXTを確認
- テストドメインでSPF等のレコードを読む

## 実践課題
架空顧客の「WebはXserver→別hosting、メールはMicrosoft 365継続」という移管手順を作る。

## 完了判定
- [ ] SMTP/IMAP/MXを説明できる
- [ ] SPF/DKIM/DMARCの違いが分かる
- [ ] Web移管時にメール設定を保全できる
- [ ] 不達の基本切り分けができる
