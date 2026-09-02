# 23-24｜AI・AI自動化

## 目的
AIを単なるチャット利用ではなく、制作効率化・顧客業務改善へ組み込めるようにする。

## 目標レベル
**Lv3。** AIの得意不得意、データ取扱い、API/自動化を理解して実務提案できる。

## 必要知識
### 生成AI
- LLMの基本特性、hallucination、context
- prompt設計（目的・入力・制約・出力形式）
- structured output
- tool/function callingの概念
- token/cost/latency
- model選定

### AI機能
- OCR、speech-to-text、classification、summarization
- embedding / semantic search / RAG概要
- image generationの利用場面

### 自動化
- webhook、API連携
- scheduled job
- n8n / Make / Zapier等の考え方
- human-in-the-loop
- retry/error handling

### リスク
- 個人情報・機密情報
- 誤回答検証
- copyright/利用規約

## ここまでできれば十分
- 「AIを使うべき/使わないべき」を判断できる
- APIでLLMを呼びstructured JSONを得られる
- webhookを使った簡単な自動化を作れる
- AI出力を人が確認すべき工程を設計できる

## 習得方法
- OpenAI/Anthropic等の公式DocsをAPI中心に読む
- n8n/Makeで1つworkflowを作る
- 顧客業務を想定し、入力→AI→確認→保存の小さなPoCを実装

## 実践課題
問い合わせ内容をAIで分類・要約し、Google Sheets等へ保存するworkflowを作る。

## 完了判定
- [ ] hallucination対策を説明できる
- [ ] AI APIを実装できる
- [ ] structured outputを使える
- [ ] 自動化の失敗時処理を考えられる
- [ ] 個人情報を扱う際の注意点を説明できる
