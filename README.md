# formation_zotero

Structure de travail du dossier. On s'y tient pour les prochaines itérations.

## Arborescence de référence

- `documentation/01_sources/` : sources brutes et documents de référence
- `documentation/02_planning/` : cadrage, notes, checklist, préparation
- `slides/zotero-jeudi/` : présentation Quarto Reveal.js de la séance
- `docs/` : rendus HTML générés pour diffusion ou publication
- `handouts/` : fiches à distribuer aux participant·es
- `assets/images/` : images et logos utilisés dans les supports
- `_extensions/` : extensions Quarto installées dans le projet

## Conventions

1. Tout document source externe va dans `documentation/01_sources/`.
2. Toute note de travail ou de préparation va dans `documentation/02_planning/`.
3. Toute présentation va dans `slides/zotero-jeudi/`.
4. Tout rendu HTML généré va dans `docs/`.
5. Toute fiche de distribution va dans `handouts/`.
6. Toute image ou logo va dans `assets/images/`.

## Présentation

Le thème de présentation retenu est :
- `grantmcdermott/quarto-revealjs-clean`

Commande de rendu :

```bash
quarto render
```

Le rendu courant est généré ici :

- `docs/slides/zotero-jeudi/index.html`
