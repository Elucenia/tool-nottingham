<!-- ELUCENIA technical documentation · nottingham · en · no clinical/professional/rights approval -->

# Nottingham histological grade

[conditions, sources and permissions](https://elucenia.org/en/tools/nottingham)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Tubule/gland formation

`tubulos`

- `1` — \> 75% of the tumor
- `2` — 10% to 75%
- `3` — \< 10%

### Nuclear pleomorphism

`nucleo`

- `1` — Small, regular and uniform nuclei
- `2` — Moderate increase in size and variability
- `3` — Marked variation

### Mitotic count (in 10 fields, adjusted for field diameter)

`mitoses`

- `1` — Score 1 (low)
- `2` — Score 2 (intermediate)
- `3` — Score 3 (high)

## Method edition

Nottingham/Elston–Ellis 1991: 3 components 1–3, total 3–9; mitoses per field area

## Documented formula

Each component scores 1 to 3 points. Sum 3–5 = grade 1 · 6–7 = grade 2 · 8–9 = grade 3.

The mitotic-count threshold depends on microscope high-power-field area; use the source conversion table or local service protocol.

## Limits and population

Histopathological grading of breast carcinoma by tubule formation, pleomorphism and mitoses. Mitotic thresholds depend on the microscope field area. The grade is not the Nottingham Prognostic Index and does not replace pathological assessment or validate another histology.

## References

- [Elston CW, Ellis IO. Pathological prognostic factors in breast cancer. I. The value of histological grade in breast cancer: experience from a large study with long-term follow-up. Histopathology, 1991.](https://doi.org/10.1111/j.1365-2559.1991.tb00229.x)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Grade 1 (well differentiated)


### 2

Grade 2 (moderately differentiated)


### 3

Grade 3 (poorly differentiated)

