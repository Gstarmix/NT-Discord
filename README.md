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

`lang/fr` et `lang/uk` portent en plus **nostale_nf3.md** : le contexte de NosFire 3 (serveur événement fermé le 10/06/2026), gardé en référence mais à requalifier vers le serveur classique. `lang/fr` et `lang/uk` sont les versions primaires validées ; les autres langues sont créées à la demande.

### `qa/<lang>/` : questions-réponses

Une question par fichier, rangée dans le dossier de sa langue (aujourd'hui surtout `fr` et `uk`). Quatre états :

- `valides/` : réponses validées, la base de référence.
- `brouillons/` : réponses en attente de validation.
- `lecture/` : notes de contexte et de traduction sur une conversation, avant d'en faire une réponse. Elles conservent la conversation d'origine ; les fiches de source anglaise sont bilingues (anglais puis français) pour servir aussi d'appui d'apprentissage.
- `auto/` : questions-réponses distillées **automatiquement** depuis le salon d'aide du Discord officiel de NosTale. Provenance fiable (vrais joueurs) mais **non relues à la main** : chaque fiche porte un niveau de confiance dans son en-tête, à recouper avant de s'en servir.

Les images référencées par les fiches vivent dans `qa/assets/`. Un index global dans `qa/INDEX.md` liste les questions validées par langue.

> La numérotation `qNNN` est **propre à chaque langue** : une même question en `fr` et en `uk` n'a pas forcément le même numéro (les langues sont indépendantes, on ne traduit pas systématiquement).

### À la racine

- **CLAUDE.md** : instructions pour Claude Code (flow, style, workflows). Ce fichier pilote le comportement de l'assistant (non publié dans le miroir public).

---

## Comment ça marche

### Réponses Discord

1. Je colle la question dans Claude Code.
2. Claude détecte la langue et me demande le niveau de réponse souhaité : **1 Réflexe** (ultra court), **2 Décontracté**, **3 Posé**, **4 Argumenté**.
3. Il consulte `shared/` (style, limites, glossaire) puis `lang/<langue>/` et les Q&A existantes (`valides/`, et le contexte de `lecture/` / `auto/`).
4. Il génère la réponse dans un fichier brouillon, prête à coller.
5. Je valide, il déplace en `valides/` et met à jour l'index.

### Lecture avant réponse

Quand je colle une conversation entière (plusieurs joueurs) sans encore vouloir de réponse, Claude produit une fiche `lecture/` : traduction, mécaniques expliquées, points à clarifier. C'est la matière première ; elle devient une réponse seulement si je le demande.

### Distillation du Discord officiel

Les fiches `auto/` sont extraites automatiquement des questions-réponses du salon d'aide officiel, puis condensées en Q&A courtes avec un niveau de confiance. Elles élargissent la couverture sans travail manuel, en attendant une relecture.

### Gstar GPT

L'assistant IA de nostar.fr utilise ce dépôt comme base de connaissances (RAG) : les mécaniques par langue et les Q&A (validées, lecture, auto) ancrent ses réponses en temps réel, dans la langue du joueur.

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
- **Mémoire du Gstar GPT** (ce qu'il a appris) : [nostar.fr/learned](https://nostar.fr/learned)
- **Forum communautaire** : [nostar.fr/forum](https://nostar.fr/forum)
- **Questions fréquemment posées** : [nostar.fr/faq](https://nostar.fr/faq)
- **Guides de progression** : [nostar.fr/progress](https://nostar.fr/progress)
- **Claude Code** (l'outil derrière l'assistant) : [claude.ai/code](https://claude.ai/code)

---

*Dernière mise à jour : 12/07/2026*