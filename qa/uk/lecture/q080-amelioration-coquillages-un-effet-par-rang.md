---
numero: 80
lang: uk
titre: "Amélioration des coquillages : un seul effet améliorable par rang (C/B/A/S), pas deux SL"
date_redaction: "2026-07-04"
statut: lecture

---

# Contexte

Deux échanges du dump uk du 03-04/07 sur le **système d'amélioration des coquillages**.
1. **Dupska** demande s'il est possible (et difficile) d'améliorer les **deux SL** en même temps sur un coquillage. Réponses : **sp12enjoyer** et le modérateur **[GA] Malivel (IT)**.
2. Le lendemain, **Hata** redemande une explication complète du système d'amélioration (quel niveau d'amélioration booste quel effet), en disant n'avoir rien trouvé sur le forum. **Yuki** répond que c'est une info en jeu (screenshot), **Flawless** partage un PDF « Shell_Upgrade_System.pdf ».

## Échange (EN → FR)

**Dupska (16:32)** *(screenshot d'un coquillage)*
EN: Is it hard to upgrade both SLs when upgrading a shell, and is it even possible?
FR: C'est dur d'améliorer les deux SL en améliorant un coquillage, et est-ce que c'est possible ?

**sp12enjoyer (16:33)**
EN: You can only upgrade one of them.
FR: Tu ne peux en améliorer qu'un seul.

**[GA] Malivel (IT) (16:33)**
EN: It's not possible to upgrade 2 A effects.
FR: Pas possible d'améliorer 2 effets A.

**sp12enjoyer (16:33)**
EN: You are limited to one C, one B, one A and one S effect. Once you upgrade one, you can only keep upgrading that same one (if you don't like it, you have to use solvent or reset the shell upgrade).
FR: Tu es limité à un effet C, un B, un A et un S. Une fois que tu en améliores un, tu ne peux plus améliorer que celui-là (si ça te plaît pas, faut utiliser du solvant ou reset l'amélioration du coquillage).

---

**Hata (10:12, lendemain)**
EN: Hello everyone. Could someone explain exactly how the shell upgrade system works? At which upgrade level is a specific effect boosted, or able to be boosted? I couldn't find anything about this on the forum.
FR: Bonjour à tous. Est-ce que quelqu'un peut m'expliquer exactement comment marche le système d'amélioration des coquillages ? À quel niveau d'amélioration un effet précis est-il boosté, ou peut-il l'être ? Je n'ai rien trouvé là-dessus sur le forum.

**Yuki (10:20)** *(screenshot)*
EN: That's in-game info, do you need to know more?
FR: C'est une info en jeu, t'as besoin d'en savoir plus ?

**Flawless (10:37)** *(fichier joint : Shell_Upgrade_System.pdf, 396 Ko)*
EN: You can find some info here too.
FR: Tu peux trouver des infos ici aussi.

## Mécaniques à retenir (EN → FR)

EN: A shell holds at most one effect of each rank: one C, one B, one A, one S.
FR: Un coquillage porte au plus un effet de chaque rang : un C, un B, un A, un S.

EN: When upgrading, you can only improve ONE effect (for example just one of the SLs / one A effect): you can't upgrade both SLs / two A effects at once.
FR: À l'amélioration, on ne peut améliorer qu'UN seul effet (par ex. un seul des SL / un seul effet A) : impossible d'améliorer les deux SL / deux effets A à la fois.

EN: Once an effect is chosen for upgrading, only that one can keep being upgraded. To switch target: solvent or reset the shell upgrade.
FR: Une fois un effet choisi pour l'amélioration, seul celui-là peut continuer à être amélioré. Pour changer de cible : solvant ou reset de l'amélioration du coquillage.

EN: The "which level boosts which effect" info is visible in-game (tooltip/interface); a community PDF "Shell_Upgrade_System.pdf" also circulates (external source, not citable).
FR: L'info « quel niveau booste quel effet » est visible en jeu (tooltip/interface) ; un PDF communautaire « Shell_Upgrade_System.pdf » circule aussi (source externe, non citable).

## Points à clarifier avant d'en faire une QA

- Vérifier la terminologie FR nostar.fr : « solvant », « reset », rangs C/B/A/S des effets de coquillage.
- **PDF « Shell_Upgrade_System.pdf »** = source externe communautaire : NE PAS citer. Chercher plutôt un guide nostar.fr équivalent (voir sources forum ci-dessus) si une QA est rédigée.
- Screenshots Dupska (16:32) et Yuki (10:20) non OCRisés ici : à récupérer et ranger dans `qa/assets/` si une QA en découle.

## Conversation originale

Dupska · 16:32
How hard is it to upgrade both of the SLs when upgrading shells and is it possible?
[Image]

sp12enjoyer · 16:33
you can only upgrade one of them

[GA] Malivel (IT) · 16:33
not posible to upgrade 2 A effects

sp12enjoyer · 16:33
you are limited to one C one B one A and one S effect, once you upgrade it you can only upgrade that one again (if you dont like it you gotta use solvent or reset the shell upgrade)

---

Hata · 10:12
Hello erveryone,
Could someone please explain exactly how the shell upgrade system works?
At which upgrade level is a specific shell effect boosted, or capable of being boosted?
Unfortunately, I haven't found anything about this on the forum.
I hope someone can provide me with a breakdown of this.
Best regards

Yuki · 10:20
That's ingame info, do you need to know more?
[Image]

Flawless · 10:37
you can find some infos here too
Type de fichier joint : acrobat
Shell_Upgrade_System.pdf 396.89 KB