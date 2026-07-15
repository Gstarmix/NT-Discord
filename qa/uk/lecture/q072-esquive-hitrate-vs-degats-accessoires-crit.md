---
numero: 72
lang: uk
titre: "Accessoires esquive/hitrate vs dégâts (Sealed / Hellord / Heaven), gants-chaussures dodge vs def"
date_redaction: "2026-07-03"
statut: lecture
---

# Contexte

Toujours **quite shallow**, question annexe posée à **godlikeforce [HALU]** après l'échange sur l'a7. Question de gear, indépendante des deux sujets précédents.

## Échange (EN → FR)

**quite shallow (03:19)** *(avec un screenshot à l'appui, non repris ici)*
EN: A question about dodge and hit rate: Sealed and Hellord are basically hit rate versus damage, is one significantly better than the other?
FR: Question sur l'esquive et le taux de touche : Sealed et Hellord c'est essentiellement taux de touche ou dégâts, est-ce que l'un est significativement meilleur que l'autre ?
EN: I think it's similar for gloves/shoes: one set gives dodge and the other full defense. I suppose full defense should be better, unless stacking dodge somehow makes you invincible?
FR: Pareil je crois pour les gants/chaussures, un set donne de l'esquive et l'autre full défense, je suppose que full défense doit être meilleur, sauf si empiler de l'esquive te rend en quelque sorte invincible ?

**godlikeforce (03:26)**
EN: Since I main mage, I never really had to worry about crits and never put much thought into them until very recently with my alts. But if I had to guess, I would probably pick Heaven(ly) because of the better crit chance: more crits = more consistency = more damage.
FR: Vu que je joue mage principalement, j'ai jamais vraiment eu à me soucier des crits, j'y ai pas trop réfléchi jusqu'à très récemment avec mes alts. Mais si je devais deviner, je prendrais plutôt Heaven(ly) à cause d'un meilleur taux de crit : plus de crits = plus de régularité = plus de dégâts.
EN: That said, I would still prioritize the shell over the base difference between the two sets. So whether it's Heaven or Hellord, it matters less than having a good shell.
FR: Cela dit, je prioriserais quand même la 'coquille' (shell) avant la différence de base entre les deux sets. Donc que ce soit Heaven ou Hellord, ça compte moins que d'avoir une bonne coquille.

## Ce qui reste flou

- Les objets exacts "Sealed", "Hellord" et "Heaven(ly)" ne sont identifiés nulle part dans `shared/nostale_ids.md` ni le glossaire du repo. Vu le contexte (bijoux/accessoires donnant taux de touche vs dégâts, gants/chaussures donnant esquive vs défense), ce sont très probablement des sets d'accessoires par paire (l'un orienté hitrate, l'autre dégâts/def), mais je n'ai pas de confirmation.
- Godlikeforce lui-même admet ne pas être spécialiste du sujet (main mage, pas hitrate/crit) : sa réponse est une supposition ("if I'd have to take a guess"), pas une certitude à citer telle quelle.
- Le terme "coquille" (shell) n'est pas défini clairement dans l'échange : pourrait désigner l'item de base avant renfo/cellon, ou un système de socket. À vérifier avant de le réutiliser.

## Points à clarifier avant d'en faire une QA

- Identifier les objets réels en DB (`_ops/db_acces.md` §B) avant de rédiger une réponse officielle : ne pas se fier uniquement à cet échange qui est lui-même une supposition d'un joueur non spécialiste du sujet.
- Si la réponse DB confirme des noms différents ou une mécanique différente, cette fiche de lecture doit être mise à jour ou écartée plutôt que servir de base directe à une QA.

## Conversation originale

quite shallowIcône de rôle, Forest Guardian · 03:19
ye i mean i dont really mind toxic community per say just didnt expect it in nostale honestly but its whatever to me, atp its just block and move on
also, question about dodge n hitrate, sealed and hellord is basically hitrate or damage, is one significantly better than the other? also i think its similar for gloves/shoes, 1 set gives dodge and the other all def, i suppose all def should be better unless stacking dodge makes you somehow invincible? @godlikeforce
Image

godlikeforce [HALU], Icône de rôle, Hell Lord Archdemon · 03:26
given that I main mage, I never had to bother about crits and never really put much thought into them until very recently with my alts; but if I'd have to take a guess I would probably pick heavenly because of better crit chance
more crits = better consistency = better damage

However, I would still prioritize the shells over their base difference instead
So whether heaven or hellord it doesn't matter as much as long as the shell is good