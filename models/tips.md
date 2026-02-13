---
layout: default
title: models
---

# [これはなに？](#what-is-this) {#what-is-this}

状況に合わせてモデルを使い分けると、もっと快適になります

ここでは、使い分けのコツを紹介します

---

## [こんなときはこのモデル](#use-cases) {#use-cases}

{: .labeled}

| シーン                                     | おすすめ |
| ------------------------------------------ | -------- |
| コードを書く、レビューする                 | Sonnet   |
| 自動で動くAI（エージェント）を長時間動かす | Sonnet   |
| 会話するAI（チャットボット）を作る         | Haiku    |
| 大量の問い合わせ（リクエスト）を処理する   | Haiku    |
| コストを抑えたい                           | Haiku    |
| 複雑な問題をじっくり解きたい               | Opus     |
| 最高品質の出力がほしい                     | Opus     |

---

## [選ぶときのポイント](#selection-criteria) {#selection-criteria}

### [1. まずは Sonnet から試す](#start-with-sonnet) {#start-with-sonnet}

困ったら Sonnet から始めてみてください

いろんなタスクをそつなくこなすバランス型です

### [2. 速さ重視なら Haiku](#speed-first) {#speed-first}

速さが大事なら Haiku がおすすめ

試作品づくり（プロトタイプ）やコストを抑えたいときにもぴったりです

### [3. 品質重視なら Opus](#quality-first) {#quality-first}

最高の品質がほしいときは Opus

コストより結果の精度を優先したい場合に選んでみてください

---

## [モデルを変えるタイミング](#when-to-change) {#when-to-change}

{: .labeled}

| 状況                   | 対応                     |
| ---------------------- | ------------------------ |
| 返事が遅いと感じる     | Haiku に変えてみる       |
| もっと良い答えがほしい | Opus に変えてみる        |
| コストが気になる       | Haiku に変えてみる       |
| 十分な品質が出ている   | そのまま or Haiku で試す |

---

## [以前のモデルのこと](#legacy-models) {#legacy-models}

古いバージョン（Claude 4.1、4、3.7 など）もまだ使えます

新しく始めるなら最新のモデルがおすすめ

{: .source}
[公式ドキュメント](https://docs.anthropic.com/en/docs/about-claude/models/choosing-a-model){:target="\_blank"}
