<!-- ELUCENIA technical documentation · nottingham · fr · no clinical/professional/rights approval -->

# Grade histologique de Nottingham

[conditions, sources et autorisations](https://elucenia.org/fr/outils/nottingham)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Formation de tubules/glandes

`tubulos`

- `1` — \> 75 % de la tumeur
- `2` — 10% à 75%
- `3` — \< 10%

### Pléomorphisme nucléaire

`nucleo`

- `1` — Petits noyaux réguliers et uniformes
- `2` — Augmentation modérée de la taille et de la variabilité
- `3` — Variation importante

### Compte des mitoses (sur 10 champs, ajusté au diamètre du champ)

`mitoses`

- `1` — Score 1 (faible)
- `2` — Score 2 (intermédiaire)
- `3` — Score 3 (élevé)

## Édition de la méthode

Nottingham/Elston–Ellis 1991 : 3 composants 1–3, total 3–9 ; mitoses par surface de champ

## Formule documentée

Chaque composant vaut 1–3 points. Somme 3–5 = grade 1 · 6–7 = grade 2 · 8–9 = grade 3.

Le seuil mitotique dépend de la surface du champ à fort grossissement ; utilisez le tableau de conversion de la source ou le protocole du service.

## Limites et population

Histograduation du carcinome mammaire selon la formation tubulaire, le pléomorphisme et les mitoses. Les seuils mitotiques dépendent de la surface du champ microscopique. Le grade n’est pas le Nottingham Prognostic Index et ne remplace pas l’évaluation anatomopathologique ni ne valide une autre histologie.

## Références

- [Elston CW, Ellis IO. Pathological prognostic factors in breast cancer. I. The value of histological grade in breast cancer: experience from a large study with long-term follow-up. Histopathology, 1991.](https://doi.org/10.1111/j.1365-2559.1991.tb00229.x)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
