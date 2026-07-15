---
numero: 100
lang: uk
titre: "Divers petites questions du salon (graine rouge en 5.2, costumes d'arme PvE arc, monter atk/def d'une PSP chez Malcolm, % sur mini-Pollutus, désactiver le rangement auto des SP dans la hotbar)"
date_redaction: "2026-07-06"
statut: lecture

---

# Contexte

En marge du grand fil de quite shallow (q094-q099), le salon help-questions a porté plusieurs petites questions indépendantes de joueurs différents. Regroupées ici pour ne rien perdre. Répondants : **itspamu**, **hinony**, **KYO**, **Piotress**. Certaines restent sans réponse.

## Échange (EN → FR)

**Graine rouge (Red Seed) : quels actes ? - _shiden_ / itspamu / hinony**
EN: _shiden_: Is the red seed only in 5.2, or in 5.1 too? itspamu: Only 5.2. Dropping red seeds makes you feel like you're stuck in an asylum. _shiden_ (after 40 minutes, 0 mobs): I'm trying to make them pop on the East and West paths.
FR: _shiden_ : La graine rouge, c'est seulement en 5.2, ou en 5.1 aussi ? itspamu : Seulement en 5.2. Faire drop les graines rouges, on se croirait enfermé en asile. _shiden_ (après 40 minutes, 0 mob) : j'essaie de les faire pop sur les chemins Est et Ouest.

**Costume d'arme PvE pour arc - tonino1999 / KYO / Piotress**
EN: tonino1999: Which is a good PvE weapon costume (for a bow)? KYO: Cheap = floral, then summer, and top tier = zodiac. Piotress: zodiac > summer > laser/flower > underwater; steampunk if combined with Easter Monarch and you're doing a7-a9.
FR: tonino1999 : Quel est un bon costume d'arme PvE (pour un arc) ? KYO : Pas cher = floral, ensuite summer, et top tier = zodiac. Piotress : zodiac > summer > laser/flower > underwater ; steampunk si combiné avec Easter Monarch et que tu fais a7-a9.

**Augmenter l'attaque et la défense d'une SP partenaire - m0rgue / Piotress**
EN: m0rgue: How can I increase a partner specialist's attack and defence? Piotress: By upgrading at Malcolm (PSP fusion).
FR: m0rgue : Comment augmenter l'attaque et la défense d'une SP partenaire ? Piotress : En l'améliorant chez Malcolm (fusion de PSP).

**Quel % infliger sur un mini-Pollutus pour la graine - Kaleinyo (sans réponse)**
EN: Kaleinyo: What % of damage should I deal on a mini Pollutus to get the seed?
FR: Kaleinyo : Quel % de dégâts faut-il infliger sur un mini-Pollutus pour obtenir la graine ? (reste sans réponse)

**Désactiver le rangement automatique des SP dans la hotbar - outrageous_quail / Piotress**
EN: outrageous_quail: Is there a way to turn off the new SP-hotbar behaviour so it works like before, without having to drag and drop all the spells back? (Coming back after a long break, I now have over 100 hotbars to reset, it's the fifth circle of hell.) Piotress: No. Good luck resetting all your hotbars. I thought of making a suggestion for it but was too lazy; you could give it a try. (He credits Prism/Jophiel and someone at Entwell for the SP-hotbar feature.)
FR: outrageous_quail : Y a-t-il un moyen de désactiver le nouveau comportement de rangement des SP dans la hotbar pour qu'il refonctionne comme avant, sans devoir tout re-glisser-déposer ? (De retour après une longue pause, j'ai plus de 100 hotbars à re-régler, c'est le cinquième cercle de l'enfer.) Piotress : Non. Bon courage pour re-régler toutes tes hotbars. J'ai pensé à faire une suggestion pour ça mais j'ai eu la flemme ; tu peux tenter. (Il attribue la fonctionnalité à Prism/Jophiel et à quelqu'un chez Entwell.)

## Mécaniques à retenir (EN → FR)

EN: Red Seed (5.x): only drops in map 5.2, not 5.1. Drop rate feels very low (long farming). East/West paths are used to make the mobs spawn.
FR: Graine rouge (5.x) : ne drop qu'en map 5.2, pas en 5.1. Taux de drop ressenti très bas (farm long). Chemins Est/Ouest utilisés pour faire spawn les mobs.

EN: PvE bow weapon-costume ranking: zodiac (top) > summer > laser/flower > underwater; floral is the cheap entry. Steampunk is a special case (good with Easter Monarch for a7-a9).
FR: Classement des costumes d'arme PvE (arc) : zodiac (top) > summer > laser/flower > underwater ; floral est l'entrée de gamme pas chère. Steampunk est un cas particulier (bon avec Easter Monarch pour a7-a9).

EN: To raise a partner specialist's attack/defence, upgrade it at Malcolm via PSP fusion.
FR: Pour augmenter l'attaque/défense d'une SP partenaire, l'améliorer chez Malcolm via la fusion de PSP.

EN: The new SP-hotbar auto-sorting behaviour cannot be turned off (no client option); it's a suggested feature-request but not implemented.
FR: Le nouveau rangement automatique des SP dans la hotbar ne peut pas être désactivé (pas d'option client) ; c'est une suggestion possible mais non implémentée.

## Points à clarifier avant d'en faire une QA

- **Graine rouge / Red Seed** : identifier l'item exact en DB (« red seed » = graine rouge d'un event ? map 5.2 = Chemin ?). % de dégâts sur mini-Pollutus (question Kaleinyo) reste sans réponse : ne pas inventer de seuil.
- **Costumes d'arme** : « floral, summer, zodiac, laser/flower, underwater, steampunk, Easter Monarch » = costumes NosMall. Résoudre les noms officiels FR en DB avant de citer (nombreux homonymes).
- **« Malcolm » / « PSP fusion »** : PNJ de fusion des SP partenaires (PSP = Partner Specialist). Confirmer le nom FR du PNJ (Malcolm) et le libellé exact du service.
- **Fonctionnalité hotbar SP** : témoignage joueur (Piotress), pas une source officielle ; ne pas l'affirmer comme parole de dev. « Prism/Jophiel », « Entwell » = pseudos/équipe cités, hors périmètre.

## Conversation originale

_shiden_ - 16:18
Hi, the red seed is only in 5.2 or 5.1 too ?

itspamu - 16:20 (reply _shiden_)
only 5.2

_shiden_ - 16:20
ok... 40min and 0 mob \o/

itspamu - 16:23 (reply _shiden_)
ye dropping red seeds makes you feel like you're stuck in asylum

hinony - 17:15 (reply _shiden_)
where are you trying to make them pop ?

_shiden_ - 17:27 (reply hinony)
East and West path

tonino1999 - 18:30
which is a good pve weapon costume?

KYO - 18:31 (reply tonino1999)
? weapon and cost

tonino1999 - 18:31
bow

KYO - 18:31
cheap floral then summer and top tier zodiac

Piotress - 18:31 (reply tonino1999)
zodiac > summer > laser/flower > underwater
steampunk if combined with easter monarch and you do a7-9

tonino1999 - 18:32
thanks

corpska / m0rgue - 19:56
alr another question, how can i increase partner specialist attack and def?

Piotress - 19:57 (reply m0rgue)
upgrading at malcolm (psp fusion)

m0rgue - 19:58
i see, ty

Kaleinyo - 20:01
What % should I deal on a mini pollutus to get the seed ?

outrageous_quail_13370 - 21:21
Is there a board of ppl responsible for game/client features? I would like to personally thank someone for the hotbar thing with SPs.

Piotress - 21:22 (reply outrageous_quail)
Prism/Jophiel and ~~that one developer in~~ Entwell

outrageous_quail_13370 - 21:27 (reply Piotress)
Thank you ❤️
Do you maybe know if there is a possibility to turn that off so it behaves as before and I dont have to manually drag&drop all the spells back to its place ? (I have not been playing for a long time, so afaik I now have the fun thing of setting well over 100hotbars). I consider it 5th circle of hell.

Piotress - 21:28 (reply outrageous_quail)
no, gl in setting back all your hotbars tho
I thought of making a suggestion for it, but was too lazy to write it, you could give it a try