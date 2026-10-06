<!-- ELUCENIA technical documentation · nottingham · zh · no clinical/professional/rights approval -->

# Nottingham 组织学分级

[条件、来源与许可](https://elucenia.org/zh/tools/nottingham)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 腺管/腺体形成

`tubulos`

- `1` — 肿瘤的\>75%
- `2` — 10% 至 75%
- `3` — \< 10%

### 核多形性

`nucleo`

- `1` — 细胞核小、规则且均一
- `2` — 大小和变异性中度增加
- `3` — 显著变异

### 有丝分裂计数（10 个视野，按视野直径校正）

`mitoses`

- `1` — 评分1（低）
- `2` — 评分2（中）
- `3` — 评分3（高）

## 方法版本

Nottingham/Elston–Ellis 1991：3项各1–3，总计3–9；按视野面积计有丝分裂

## 已记录的公式

每项计1至3分。总和3–5 = 1级 · 6–7 = 2级 · 8–9 = 3级。

有丝分裂计数阈值取决于显微镜高倍视野面积；使用来源换算表或本机构方案。

## 限制与适用人群

按腺管形成、核多形性和有丝分裂对乳腺癌进行组织病理分级。有丝分裂阈值依赖显微镜视野面积。该等级不是Nottingham预后指数，不能代替病理评估，也不能验证其他组织学类型。

## 参考文献

- [Elston CW, Ellis IO. Pathological prognostic factors in breast cancer. I. The value of histological grade in breast cancer: experience from a large study with long-term follow-up. Histopathology, 1991.](https://doi.org/10.1111/j.1365-2559.1991.tb00229.x)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

1级（分化良好）


### 2

2级（中等分化）


### 3

3级（低分化）

