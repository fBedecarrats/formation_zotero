# Instructions détaillées pour le nouveau dépôt de formation GitHub

## 1. Finalité de ce fichier

Ce fichier sert de **document de cadrage complet** pour préparer un **nouveau dépôt GitHub indépendant** dédié à la session du lendemain sur **GitHub, la reproductibilité et la science ouverte**.

L'objectif est de repartir sur une base propre, tout en s'inspirant de la méthode, de la structure et des choix éditoriaux utilisés pour le dépôt de la formation Zotero.

Ce document doit permettre de travailler dans le nouveau dépôt sans devoir reconstituer le contexte à partir du dépôt actuel.

Ce repo ressemble dans son contenu à https://github.com/fBedecarrats/formation_zotero, qu'il faut garder comme inspiration.

---

## 2. Contexte général

Cette nouvelle formation s'inscrit dans le même événement que la session Zotero préparée dans ce dépôt, à savoir le programme **PSF CREONS** autour de la science ouverte, de la reproductibilité et des partenariats scientifiques équitables.

URLs de contexte à conserver dans le nouveau dépôt :

- https://www.umi-source.uvsq.fr/psf-creons-10-jours-de-formations-autour-de-la-science-ouverte-la-reproductibilite-et-les-partenariats-scientifiques-equitables
- https://www.umi-source.uvsq.fr/psf-creons

La nouvelle session porte cette fois sur **GitHub comme outil au service de la reproductibilité, de la collaboration et de l'ouverture des pratiques de recherche**.

Le public est comparable à celui de la session Zotero :

- doctorant·es ;
- chercheur·ses ;
- collègues impliqué·es dans des pratiques de recherche ouvertes ;
- participant·es venant de plusieurs sites et institutions ;
- personnes qui pourront ensuite **retransmettre** localement cette formation.

Cette dimension de **formation de formateurs** est centrale.

---

## 3. Intention pédagogique

La session ne doit pas présenter GitHub comme un outil de développeur réservé à l'informatique.

Elle doit le présenter comme un outil simple et utile pour :

- **versionner** des fichiers et des projets ;
- **documenter** les étapes d'un travail ;
- **collaborer** proprement ;
- **partager** des scripts, documents, données ou supports ;
- **renforcer la reproductibilité** ;
- **soutenir la science ouverte**.

Le message principal doit être le suivant :

> GitHub n'est pas une fin en soi. C'est un support concret pour rendre un travail plus traçable, plus collaboratif, plus partageable et donc plus reproductible.

---

## 4. Positionnement de la séance

La séance doit être conçue pour un public qui n'est pas forcément expert en ligne de commande ni en développement logiciel.

Il faut donc viser :

- un niveau d'entrée accessible ;
- des démonstrations concrètes ;
- des manipulations simples ;
- des exemples de recherche ou de formation, pas seulement de code ;
- un discours orienté usages réels.

La séance doit également assumer une logique de **transmission** : les participant·es doivent repartir avec un scénario qu'ils pourront reproduire plus tard sous un format plus court.

---

## 5. Objectifs pédagogiques visés

À la fin de la séance, les participant·es devraient pouvoir :

1. comprendre à quoi sert GitHub dans un projet de recherche ou de formation ;
2. distinguer Git, GitHub et le stockage de fichiers classique ;
3. créer ou utiliser un dépôt ;
4. comprendre la logique de base : fichiers, commits, historique, dépôt distant ;
5. modifier un fichier et enregistrer une version propre ;
6. documenter un projet avec un `README` clair ;
7. partager un support ou un petit projet publiquement ou dans un espace collaboratif ;
8. identifier en quoi GitHub contribue à la reproductibilité et à la science ouverte ;
9. retransmettre une version simplifiée de cette séance à des collègues ou étudiant·es.

---

## 6. Angle recommandé pour le contenu

Le contenu devrait éviter une entrée trop technique du type :

- branches complexes ;
- résolution de conflits trop avancée ;
- rebase ;
- workflows d'intégration continue dès le départ ;
- jargon de développeur non expliqué.

Il vaut mieux commencer par des gestes simples :

- créer un dépôt ;
- ajouter un fichier ;
- faire un commit ;
- comprendre l'historique ;
- synchroniser ;
- documenter ;
- publier.

Ensuite seulement, on peut ouvrir vers des usages plus riches :

- issues ;
- pull requests ;
- GitHub Pages ;
- gestion collaborative ;
- ouverture du code et des supports ;
- archivage ou citation des versions.

---

## 7. Lien avec la reproductibilité et la science ouverte

Le lien avec la reproductibilité doit être explicite à chaque étape.

Exemples de messages à faire passer :

- un dépôt permet de **savoir quelle version** d'un fichier a été utilisée ;
- un historique permet de **voir ce qui a changé** et quand ;
- un `README` permet de **comprendre comment réutiliser** un projet ;
- un dépôt partagé permet de **collaborer sans écraser le travail des autres** ;
- la publication ouverte d'un support, script ou protocole favorise la **transparence** ;
- GitHub facilite le passage d'un travail individuel à un travail **documenté et transmissible**.

Le lien avec la science ouverte peut être formulé ainsi :

- mieux partager ;
- mieux documenter ;
- mieux attribuer ;
- mieux réutiliser ;
- mieux transmettre.

---

## 8. Contraintes pédagogiques à garder en tête

Le public n'est pas supposé :

- connaître Git ;
- être à l'aise avec le terminal ;
- savoir lire une documentation de développeur ;
- comprendre le vocabulaire GitHub sans accompagnement.

Il faut donc :

- expliciter les termes ;
- montrer des exemples très concrets ;
- limiter le nombre de concepts nouveaux par séquence ;
- distinguer l'essentiel du secondaire ;
- privilégier les routines simples et robustes.

---

## 9. Format recommandé

Le format cible peut rester proche de celui utilisé pour la session Zotero : une séance assez pratique, avec support Quarto Reveal.js, démonstration et exercice.

Format recommandé : **2h30 à 3h** pour la version complète.

Il faut aussi penser dès le départ à une **version courte en 2h** réutilisable par les participant·es après la formation.

---

## 10. Déroulé suggéré pour la version longue

Exemple de séquençage possible :

1. Pourquoi GitHub en recherche ?
2. Git, GitHub, dépôt, version : vocabulaire minimal
3. Créer et organiser un dépôt simple
4. Modifier un fichier et faire un commit
5. Lire l'historique et comprendre la traçabilité
6. Ajouter un README utile
7. Partager un dépôt et collaborer
8. Lien avec reproductibilité / science ouverte
9. Exercice pratique
10. Comment retransmettre cette séance en format court

---

## 11. Exercice pratique recommandé

L'exercice doit être simple, faisable et directement relié aux usages de recherche ou de formation.

Exemple :

> Par petit groupe, créer ou compléter un dépôt contenant un mini-support ou mini-projet, puis produire un historique simple et un README réutilisable.

Sorties possibles :

- un dépôt propre ;
- au moins un fichier modifié ;
- au moins un commit explicite ;
- un README minimal ;
- une compréhension de l'intérêt de l'historique.

---

## 12. Ce qui doit absolument apparaître dans les objectifs

Comme pour la formation Zotero, la logique de **formation de formateurs** doit apparaître explicitement.

Le verbe **transmettre** doit figurer dans les objectifs.

Il faut prévoir une diapo ou une section spécifique du type :

- **Refaire cette formation en 2h**

avec un découpage simple et réaliste.

---

## 13. Livrables attendus dans le nouveau dépôt

Le nouveau dépôt devra idéalement contenir au minimum :

1. une présentation Quarto ;
2. un `README.md` succinct et clair ;
3. un dossier de documentation de cadrage ;
4. un rendu dans `docs/` pour GitHub Pages ;
5. un fichier `.nojekyll` dans `docs/` ;
6. un espace pour les images et les sources visuelles ;
7. éventuellement une fiche exercice et une fiche mémo.

---

## 14. Structure de dépôt recommandée

Le nouveau dépôt peut reprendre une structure analogue à celle mise en place ici :

- `documentation/01_sources/` : sources brutes, programme, notes externes
- `documentation/02_planning/` : cadrage, checklist, préparation pédagogique
- `slides/` : éventuelles copies de travail ou archives de versions
- `assets/images/` : images, logos, sources d'illustration
- `handouts/` : fiches exercice ou mémo
- `docs/` : rendu final pour publication
- `index.qmd` : source principale publiée
- `_quarto.yml` : configuration Quarto du projet
- `README.md` : vue d'ensemble du dépôt

Si le dépôt ne comporte qu'une seule présentation principale, il est recommandé de publier depuis un **`index.qmd` à la racine**, afin d'obtenir directement `docs/index.html` pour GitHub Pages.

---

## 15. Choix techniques recommandés

Pour rester cohérent avec la formation Zotero, on peut reprendre les choix suivants :

- Quarto pour l'édition du support ;
- Reveal.js pour la présentation ;
- thème `grantmcdermott/quarto-revealjs-clean` ;
- publication via GitHub Pages depuis `docs/` ;
- lien vers le dépôt GitHub sur la page de titre ;
- `README` minimal orienté usage.

---

## 16. Publications et GitHub Pages

Le dépôt devra être pensé pour être publié facilement.

Le bon objectif est :

- source principale : `index.qmd`
- rendu principal : `docs/index.html`

Cela évite les problèmes classiques où la page d'accueil GitHub Pages ne trouve pas de `index.html` à la racine du dossier publié.

Prévoir aussi :

- `docs/.nojekyll`

---

## 17. Convention de travail recommandée

Quelques conventions à reprendre :

- tout document brut externe va dans `documentation/01_sources/`
- toute note de préparation va dans `documentation/02_planning/`
- toute image utilisée va dans `assets/images/`
- toute image doit idéalement avoir une source documentée
- le rendu publié doit aller dans `docs/`
- le fichier principal publié doit être clairement identifié

---

## 18. Éléments éditoriaux à conserver

La présentation doit rester :

- visuelle ;
- assez épurée ;
- pensée pour l'oral ;
- avec des notes de présentation détaillées ;
- avec une hiérarchie entre contenu principal et annexes.

Les annexes peuvent accueillir :

- points plus avancés ;
- veille sur les nouveautés GitHub ;
- options techniques ;
- éléments utiles mais non essentiels au cœur de la séance.

---

## 19. Exemples de thèmes à traiter dans les annexes

Pour une formation GitHub/reproductibilité, les annexes pourraient par exemple couvrir :

- GitHub Pages ;
- licences ;
- README exemplaires ;
- issues et pull requests ;
- archivage et citation de versions ;
- articulation GitHub / Zenodo ;
- travail collaboratif sur supports pédagogiques ;
- comparaison dépôt public / privé.

---

## 20. Ce qu'il faut éviter

Éviter de construire une formation trop lourde, trop technique ou trop proche d'un tutoriel pour développeurs expérimentés.

Éviter aussi :

- les longues séquences de terminal sans contextualisation ;
- les détails avancés dès le début ;
- le vocabulaire non expliqué ;
- les exemples purement logiciels sans lien avec la recherche ;
- la surcharge de texte à l'écran.

---

## 21. Démarche conseillée pour démarrer le nouveau dépôt

Ordre recommandé :

1. créer le nouveau dépôt GitHub indépendant ;
2. installer Quarto et le thème choisi ;
3. poser la structure des dossiers ;
4. créer `index.qmd` ;
5. configurer `_quarto.yml` vers `docs/` ;
6. créer un `README.md` simple ;
7. préparer un premier plan de slides ;
8. documenter les objectifs pédagogiques ;
9. préparer l'exercice pratique ;
10. ajouter ensuite illustrations et annexes.

---

## 22. Résultat attendu

À l'issue du travail dans le nouveau dépôt, on doit disposer d'un support qui soit à la fois :

- utilisable en séance ;
- publiable en ligne ;
- compréhensible par un public non expert ;
- réutilisable par d'autres ;
- cohérent avec les enjeux de reproductibilité et de science ouverte ;
- suffisamment simple pour être retransmis localement.

---

## 23. Résumé opérationnel

Si tu travailles dans le nouveau dépôt, garde toujours en tête :

- dépôt indépendant ;
- structure claire ;
- publication via `docs/index.html` ;
- Quarto + Reveal.js ;
- pédagogie accessible ;
- lien explicite avec la reproductibilité ;
- logique de formation de formateurs ;
- objectif final : **un support transmissible**.