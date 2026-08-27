# qiita-voice

moritalous氏（Qiita）の文体・構成・トーンを再現してQiita記事を執筆するClaude Codeプラグイン。
396本の公開記事を分析して蒸留した文体ガイドと実例集を使用します。

## インストール

```shell
/plugin marketplace add moritalous/qiita-voice-plugin
/plugin install qiita-voice@moritalous-qiita-voice
```

## 使い方

```shell
/qiita-voice これまでの検証結果をQiita記事にしたい
```

トピック（技術要素）は依頼内容に従い、文体だけをこのスキルで再現します。

## 構成

- `SKILL.md` — 執筆手順・必須ルール・セルフチェックリスト
- `references/style_guide.md` — タイトル/構成/口調/絵文字/コード・画像・表の詳細ルール
- `references/titles.md` — タイトルパターンの実例集
- `references/intros_and_outros.md` — 書き出し・締めの実例集
- `references/avoid_ai_smell.md` — 「生成AIっぽさ」を消すためのチェックリストとBefore/After
- `references/examples/` — 全文サンプル5本

## ローカルでのテスト方法

```shell
/plugin marketplace add ./qiita-voice-plugin
/plugin install qiita-voice@moritalous-qiita-voice
```

## ライセンス

MIT License（[LICENSE](LICENSE)参照）
