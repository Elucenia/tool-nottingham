<!-- ELUCENIA technical documentation · nottingham · ja · no clinical/professional/rights approval -->

# Nottingham組織学的グレード

[条件・出典・許諾](https://elucenia.org/ja/tools/nottingham)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 腺管・腺形成

`tubulos`

- `1` — 腫瘍の\>75%
- `2` — 10% ～ 75%
- `3` — \< 10%

### 核多形性

`nucleo`

- `1` — 小型で規則的かつ均一な核
- `2` — 大きさと変動性の中等度増加
- `3` — 著しい変異

### 核分裂像数（10視野、視野径で補正）

`mitoses`

- `1` — スコア1（低い）
- `2` — スコア2（中間）
- `3` — スコア3（高い）

## 方法の版

Nottingham/Elston–Ellis 1991：3項目1–3，合計3–9；視野面積別核分裂

## 記載された計算式

各項目1〜3点。合計3–5 = グレード1 · 6–7 = グレード2 · 8–9 = グレード3。

核分裂数の閾値は顕微鏡高倍率視野の面積に依存。出典の換算表または施設手順を使う。

## 限界・対象集団

管状構造の形成、核の多形性、有糸分裂により乳がんを組織病理学的に評価します。有糸分裂の閾値は、顕微鏡の視野面積に依存します。このグレードはNottingham Prognostic Indexではなく、病理評価に代わるものでも、他の組織型を妥当とするものでもありません。

## 参考文献

- [Elston CW, Ellis IO. Pathological prognostic factors in breast cancer. I. The value of histological grade in breast cancer: experience from a large study with long-term follow-up. Histopathology, 1991.](https://doi.org/10.1111/j.1365-2559.1991.tb00229.x)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
