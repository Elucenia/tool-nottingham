<!-- ELUCENIA technical documentation · nottingham · it · no clinical/professional/rights approval -->

# Grado istologico di Nottingham

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/nottingham)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Formazione di tubuli/ghiandole

`tubulos`

- `1` — \> 75% del tumore
- `2` — 10% a 75%
- `3` — \< 10%

### Pleomorfismo nucleare

`nucleo`

- `1` — Nuclei piccoli, regolari e uniformi
- `2` — Moderato aumento di dimensione e variabilità
- `3` — Variazione marcata

### Conta delle mitosi (in 10 campi, corretta per il diametro del campo)

`mitoses`

- `1` — Punteggio 1 (basso)
- `2` — Punteggio 2 (intermedio)
- `3` — Punteggio 3 (alto)

## Edizione del metodo

Nottingham/Elston–Ellis 1991: 3 componenti 1–3, totale 3–9; mitosi per area del campo

## Formula documentata

Ogni componente vale 1–3 punti. Somma 3–5 = grado 1 · 6–7 = grado 2 · 8–9 = grado 3.

La soglia delle mitosi dipende dall’area del campo ad alto ingrandimento; usare tabella di conversione della fonte o protocollo del servizio.

## Limiti e popolazione

Graduazione istopatologica del carcinoma mammario mediante formazione tubulare, pleomorfismo e mitosi. Le soglie mitotiche dipendono dall’area del campo del microscopio. Il grado non è il Nottingham Prognostic Index, non sostituisce la valutazione anatomopatologica e non valida un’altra istologia.

## Riferimenti

- [Elston CW, Ellis IO. Pathological prognostic factors in breast cancer. I. The value of histological grade in breast cancer: experience from a large study with long-term follow-up. Histopathology, 1991.](https://doi.org/10.1111/j.1365-2559.1991.tb00229.x)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
