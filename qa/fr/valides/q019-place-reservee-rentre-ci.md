---
numero: 19
lang: fr
titre: "Est-ce qu'une place reste réservée si on ne rentre pas dans le CI ?"
theme: "CI / placement / file d'attente"
contexte: "NosFire 3 (01/04/2026 -> 10/06/2026) + serveurs classiques"
date_validation: "07/04/2026"
obsolete_nf3: true
statut: valide
---

# Q19 : Est-ce qu'une place reste réservée si on ne rentre pas dans le CI ?

**Question FR :** Enfaite, si quelqu'un reste co et donc a son rang dans la file, s'il ne rentre pas, est ce que y aura un glissement de ceux qui sont derrière lui pour prendre sa place, ou sa place reste en permanence réservé et comptabilisé ? En gros s'il a supposons 20 dans la file, alors s'il ne rentre pas, y aura 20 places vides reparties sur 1 ou 2 ci ? Ou ces 20 seront comblés par ceux derrière lui ?

**Réponse FR :**
Les places vides n'existent pas dans un CI. Si quelqu'un ne rentre pas, ceux derrière lui dans la file prennent sa place automatiquement. Le CI se remplit toujours dans l'ordre de la file, sans trou.

**Contexte :** NosFire 3 (01/04/2026 -> 10/06/2026) + serveurs classiques
**Date de validation :** 07/04/2026
**Thème :** CI / placement / file d'attente
**Note :** Suite directe de Q18. Pas de place réservée ni de trou dans un CI. Si un joueur ne rentre pas, la file avance automatiquement.