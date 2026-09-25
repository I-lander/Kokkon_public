# Éléments tiers

Tout ce qui n'est pas listé ici est une création originale des coauteurs de
KOKKON, couverte
par `LICENSE` (tous droits réservés).

## Polices de caractères

Les deux polices sont embarquées dans la page publiée : les `woff2` sont
encodés en base64 et inlinés dans `dist/index.html`. Cette page est donc une
distribution du logiciel de fonte, et la SIL Open Font License impose que la
notice de copyright et le texte de la licence l'accompagnent. C'est l'objet de
ce fichier et du commentaire d'en-tête de la page publiée.

### Borel

```
Copyright 2023 The Borel Project Authors (https://github.com/RosaWagner/Borel)
```

SIL Open Font License, version 1.1. Texte complet : `Borel-OFL.txt`, publié
à côté de la page, et `src/assets/fonts/Borel-OFL.txt` dans le dépôt source.

### Quicksand

```
Copyright 2011 The Quicksand Project Authors
(https://github.com/andrew-paglinawan/QuicksandFamily),
with Reserved Font Name "Quicksand".
```

SIL Open Font License, version 1.1. Texte complet : `Quicksand-OFL.txt`, publié
à côté de la page, et `src/assets/fonts/Quicksand-OFL.txt` dans le dépôt source.

### État des fichiers embarqués

Les deux `woff2` sont des sous-ensembles latins des fontes d'origine. Ils n'ont
pas été renommés, ne sont pas vendus séparément et restent distribués sous la
SIL Open Font License, comme la licence l'exige.

## Sons issus de bibliothèques libres de droits

Les pistes et les routines de KOKKON sont des mixages. Certains des sons qui
les composent proviennent de bibliothèques de sons libres de droits et restent
la propriété de leurs auteurs, sous la licence de leur bibliothèque d'origine.
Ils ne sont distribués qu'intégrés à un mixage, et la licence de KOKKON ne
confère aucun droit sur eux.

## Bibliothèques

React et React DOM (MIT, Copyright (c) Facebook, Inc. and its affiliates) sont
compilés dans le bundle publié. La licence MIT demande que sa notice accompagne
les copies substantielles : le texte est dans `node_modules/react/LICENSE`, et
reproduit ci-dessous.

```
MIT License

Copyright (c) Facebook, Inc. and its affiliates.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
