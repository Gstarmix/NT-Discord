# NT-Discord : base de connaissances NosTale

Base de connaissances multilingue (9 langues) que j'utilise pour deux choses : répondre aux joueurs sur le Discord officiel de NosTale, et alimenter **Gstar GPT**, l'assistant IA du site [nostar.fr](https://nostar.fr).

Ce n'est pas un bot. C'est de la doc structurée que je fournis à Claude Code pour qu'il m'aide à formuler des réponses cohérentes, dans le bon style, sans inventer.

Auteur : **Gstar** ([nostar.fr](https://nostar.fr), guides de progression NosTale).

---

## C'est quoi NosTale ?

**NosTale** est un MMORPG free-to-play 2D édité par Gameforge, sorti en 2007. 4 classes (Escrimeur, Archer, Mage, Artiste Martial), système de SP (Specialist Cards) pour spécialiser les classes, progression par actes (1 à 10), niveaux héroïques (H1 à H99) après le niveau 85.

Deux serveurs internationaux actifs : **Undercity** (communauté francophone, héritière de FR-Cosmos depuis la fusion du 16/07/2025) et **Dragonveil** (le plus peuplé au global).

---

## Structure du dépôt

### `shared/` : référence bilingue, source unique

- **nostale_glossary.md** : correspondances EN/FR (classes, SP, maps, items, abréviations Discord)
- **nostale_limits.md** : règles strictes à lire en priorité (niveaux, restrictions, sujets à ne pas traiter)
- **nostale_style_errors.md** : règles de style (niveaux de réponse, casse, ponctuation, format Discord et Gstar GPT)
- **nostale_ids.md** : IDs techniques (items SP, maps, raid bosses, gemmes d'âme)

### `lang/<code>/` : contenu par langue

Neuf langues disponibles (codes du site : `fr` `uk` `pl` `es` `it` `de` `tr` `cz` `ru`). Chaque dossier contient :

- **nostale_mechanics.md** : connaissances permanentes (routes de leveling, farm, classes par élément, raids, multicompte)
- **nostale_workflow.md** : politiques externes (codes nostar.fr, liens, DM)

`lang/fr` et `lang/uk` sont les versions primaires validées. Les autres langues sont créées à la demande.

### `qa/<lang>/` : questions-réponses validées

Une question par fichier, rangée dans le dossier de sa langue :

- `valides/` : réponses validées, publiées (accessibles via ce dépôt)
- `brouillons/` : en attente de validation (exclu du miroir public)

Un index global dans `qa/INDEX.md` liste toutes les questions validées par langue.

### À la racine

- **CLAUDE.md** : instructions pour Claude Code (flow, style, workflows). Ce fichier pilote le comportement de l'assistant (non publié dans le miroir public).

---

## Comment ça marche

### Réponses Discord

1. Je colle la question dans Claude Code.
2. Claude détecte la langue et me demande le niveau de réponse souhaité : **1 Réflexe** (ultra court), **2 Décontracté**, **3 Posé**, **4 Argumenté**.
3. Il consulte `shared/` (style, limites, glossaire) puis `lang/<langue>/` et `qa/<langue>/valides/`.
4. Il génère la réponse dans un fichier brouillon, prête à coller.
5. Je valide, il déplace en `valides/` et met à jour l'index.

### Gstar GPT

L'assistant IA de nostar.fr utilise ce dépôt comme base de connaissances (RAG) : les fichiers `lang/fr/` et les Q&A validées alimentent les réponses de Gstar GPT en temps réel.

### Ajouter une info

Je dis simplement à Claude : "ajoute cette Q&A", "ajoute ce terme au glossaire", "ajoute cette mécanique". Il sait dans quel fichier écrire.

---

## Style des réponses Discord

Le persona Discord, c'est un joueur expérimenté qui traîne sur le Discord officiel : pas un bot, pas un community manager. Pas de pavés, pas de listes à puces, pas de "je pense que".

Si je sais pas, je le dis franchement. Pour corriger un autre joueur sans le brusquer, on introduit avec `ngl`, `actually` : jamais de correctif sec.

Tout est détaillé dans `shared/nostale_style_errors.md`.

---

## Liens utiles

- **Assistant Gstar GPT** : [nostar.fr](https://nostar.fr)
- **Forum communautaire** : [nostar.fr/forum](https://nostar.fr/forum)
- **Questions fréquemment posées** : [nostar.fr/faq](https://nostar.fr/faq)
- **Guides de progression** : [nostar.fr/progress](https://nostar.fr/progress)
- **Claude Code** (l'outil derrière l'assistant) : [claude.ai/code](https://claude.ai/code)

---

*Dernière mise à jour : 25/06/2026*