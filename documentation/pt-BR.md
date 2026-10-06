<!-- ELUCENIA technical documentation · nottingham · pt-BR · no clinical/professional/rights approval -->

# Grau histológico de Nottingham

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/nottingham)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Formação de túbulos/glândulas

`tubulos`

- `1` — \> 75% do tumor
- `2` — 10% a 75%
- `3` — \< 10%

### Pleomorfismo nuclear

`nucleo`

- `1` — Núcleos pequenos, regulares e uniformes
- `2` — Aumento moderado de tamanho e variabilidade
- `3` — Variação acentuada

### Contagem de mitoses (em 10 campos, ajustada ao diâmetro do campo)

`mitoses`

- `1` — Escore 1 (baixa)
- `2` — Escore 2 (intermediária)
- `3` — Escore 3 (alta)

## Edição do método

Nottingham/Elston Ellis 1991:3 componentes 1–3, total 3–9; mitosesporáreadecampo

## Fórmula documentada

Cada componente vale de 1 a 3 pontos. Soma 3–5 = grau 1 · 6–7 = grau 2 · 8–9 = grau 3.

O ponto de corte da contagem de mitoses depende da área do campo de grande aumento do microscópio; use a tabela de conversão da fonte ou do protocolo do serviço.

## Limites e população

Graduação histopatológica de carcinoma mamário por formação tubular, pleomorfismo e mitoses. Os limiares mitóticos dependem da área de campo do microscópio. O grau não é o Nottingham Prognostic Index e não substitui avaliação anatomopatológica ou valida outra histologia.

## Referências

- [Elston CW, Ellis IO. Pathological prognostic factors in breast cancer. I. The value of histological grade in breast cancer: experience from a large study with long-term follow-up. Histopathology, 1991.](https://doi.org/10.1111/j.1365-2559.1991.tb00229.x)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Grau 1 (bem diferenciado)


### 2

Grau 2 (moderadamente diferenciado)


### 3

Grau 3 (pouco diferenciado)

