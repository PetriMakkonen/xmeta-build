# xmeta-build

Kevyt dokumenttigeneraattori Pandoc-, DOT- ja CSV-putkelle.

Voit kirjoittaa yaml-speksinä tieteellisen artikkelin metatiedot
ja sisällön, kaavat ja dot-kaaviot, ja sopivan formaatin kuten ieee.
Skripti voi tuottaa automaattisen sisällysluettelon joko omana sivunaan
tai integroituna. Käyttää markup-kieltä.

Tuottaa joko yksi tai kaksirivisen scitex-artkkelin pdf:nä sekä
yksinkertaitamasi beamer-luennon kalvot, jos laitat %-merkin rivien alkuun.

Skripti tuottaa komentoriviltä:

- paperi-PDF:n
- beamer/slides-PDF:n

ja tukee lisäksi

- YAML-metatietoja
- valinnaista TOC:ia
- DOT-lohkojen renderöintiä
- CSV-lohkojen renderöintiä
- Xmeta-tyylistä `%` / `%%`-syntaksia dioille ja kommenteille 



## Käyttö

```bash
xmeta-build init paper.md
xmeta-build paper paper.md
xmeta-build slides paper.md

Kevyt markdown-pohjainen dokumenttigeneraattori, joka tuottaa

- paperi-PDF:n
- beamer/slides-PDF:n

ja tukee lisäksi

- YAML-metatietoja
- valinnaista TOC:ia
- DOT-lohkojen renderöintiä
- CSV-lohkojen renderöintiä
- Xmeta-tyylistä `%` / `%%`-syntaksia dioille ja kommenteille

## Käyttö

```bash
xmeta-build init paper.md
xmeta-build paper paper.md
xmeta-build slides paper.md
