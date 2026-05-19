# formation_zotero

Préparation de la session **Zotero** pour le programme **PSF CREONS**.
La présentation est en ligne ici : https://fbedecarrats.github.io/formation_zotero/


## Où se trouvent les éléments principaux ?

- [documentation/01_sources](documentation/01_sources) : sources brutes et documents de référence
- [documentation/02_planning](documentation/02_planning) : notes de préparation, cadrage, checklist
- [slides/zotero-jeudi](slides/zotero-jeudi) : source de la présentation Quarto
- [docs/slides/zotero-jeudi/index.html](docs/slides/zotero-jeudi/index.html) : rendu HTML
- [assets/images](assets/images) : images et logos utilisés dans les slides
- [handouts](handouts) : fiches à distribuer

## Fichier principal

La présentation est éditée ici :

- [slides/zotero-jeudi/index.qmd](slides/zotero-jeudi/index.qmd)

## Rendu

Depuis la racine du projet :

```bash
quarto render
```

Le rendu est généré dans :

- [docs/slides/zotero-jeudi/index.html](docs/slides/zotero-jeudi/index.html)

## Organisation retenue

- les **sources externes** vont dans [documentation/01_sources](documentation/01_sources)
- les **notes de travail** vont dans [documentation/02_planning](documentation/02_planning)
- les **slides** vont dans [slides/zotero-jeudi](slides/zotero-jeudi)
- les **rendus HTML** vont dans [docs](docs)
- les **images** vont dans [assets/images](assets/images)

## Thème utilisé

- `grantmcdermott/quarto-revealjs-clean`
