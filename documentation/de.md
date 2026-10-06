<!-- ELUCENIA technical documentation · nottingham · de · no clinical/professional/rights approval -->

# Histologischer Nottingham-Grad

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/nottingham)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Tubulus-/Drüsenbildung

`tubulos`

- `1` — \> 75 % des Tumors
- `2` — 10% bis 75%
- `3` — \< 10%

### Kernpleomorphie

`nucleo`

- `1` — Kleine, regelmäßige und gleichförmige Zellkerne
- `2` — Mäßige Zunahme von Größe und Variabilität
- `3` — Ausgeprägte Variation

### Mitosenzahl (in 10 Gesichtsfeldern, an den Felddurchmesser angepasst)

`mitoses`

- `1` — Score 1 (niedrig)
- `2` — Score 2 (mittel)
- `3` — Score 3 (hoch)

## Fassung der Methode

Nottingham/Elston–Ellis 1991: 3 Komponenten 1–3, Gesamt 3–9; Mitosen nach Feldfläche

## Dokumentierte Formel

Jede Komponente 1–3 Punkte. Summe 3–5 = Grad 1 · 6–7 = Grad 2 · 8–9 = Grad 3.

Die Mitosegrenze hängt von der Fläche des mikroskopischen Gesichtsfeldes bei hoher Vergrößerung ab; Quell-Konversionstabelle oder Protokoll der Einrichtung verwenden.

## Grenzen und Population

Histopathologische Graduierung des Mammakarzinoms nach Tubulusbildung, Pleomorphie und Mitosen. Mitoseschwellen hängen von der Fläche des Mikroskop-Gesichtsfelds ab. Der Grad ist nicht der Nottingham Prognostic Index und ersetzt weder histopathologische Beurteilung noch validiert er eine andere Histologie.

## Referenzen

- [Elston CW, Ellis IO. Pathological prognostic factors in breast cancer. I. The value of histological grade in breast cancer: experience from a large study with long-term follow-up. Histopathology, 1991.](https://doi.org/10.1111/j.1365-2559.1991.tb00229.x)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Grad 1 (gut differenziert)


### 2

Grad 2 (mäßig differenziert)


### 3

Grad 3 (schlecht differenziert)

