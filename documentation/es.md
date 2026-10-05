<!-- ELUCENIA technical documentation · nottingham · es · no clinical/professional/rights approval -->

# Grado histológico de Nottingham

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/nottingham)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Formación de túbulos/glándulas

`tubulos`

- `1` — \> 75% del tumor
- `2` — 10% a 75%
- `3` — \< 10%

### Pleomorfismo nuclear

`nucleo`

- `1` — Núcleos pequeños, regulares y uniformes
- `2` — Aumento moderado del tamaño y la variabilidad
- `3` — Variación marcada

### Recuento de mitosis (en 10 campos, ajustado al diámetro del campo)

`mitoses`

- `1` — Puntuación 1 (baja)
- `2` — Puntuación 2 (intermedia)
- `3` — Puntuación 3 (alta)

## Edición del método

Nottingham/Elston–Ellis 1991: 3 componentes 1–3, total 3–9; mitosis por área de campo

## Fórmula documentada

Cada componente vale 1–3 puntos. Suma 3–5 = grado 1 · 6–7 = grado 2 · 8–9 = grado 3.

El umbral de mitosis depende del área del campo de gran aumento; use tabla de conversión de la fuente o protocolo del servicio.

## Límites y población

Graduación histopatológica del carcinoma mamario por formación tubular, pleomorfismo y mitosis. Los umbrales mitóticos dependen del área del campo del microscopio. El grado no es el Nottingham Prognostic Index ni sustituye la evaluación anatomopatológica ni valida otra histología.

## Referencias

- [Elston CW, Ellis IO. Pathological prognostic factors in breast cancer. I. The value of histological grade in breast cancer: experience from a large study with long-term follow-up. Histopathology, 1991.](https://doi.org/10.1111/j.1365-2559.1991.tb00229.x)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
