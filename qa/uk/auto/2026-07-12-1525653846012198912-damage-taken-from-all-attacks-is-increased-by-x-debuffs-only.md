---
source: discord-officiel/bug-reports
message_id: 1525653846012198912
message_date: 2026-07-12
author: kocoten72
answered_by: Vastar
answer_message_id: 1525806525036236810
answer_excerpt: it is intended that the "damage taken from x attacks is increased by x%" is only affecting physical damage The decision on why this one is used here and why the other one is used there is not something for me, Prism and Jophiel decide what buffs/items/etc get what effects, so fee
confidence: high
tags: [debuff, pvp, pve]
image: ../../assets/auto-1525653846012198912.png
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-13
---
# "Damage taken from all attacks is increased by X%" debuffs only apply to physical damage

**Q:** Is it intentional that "damage taken from all attacks is increased by X%" effects (found on many debuffs, including PvE-oriented ones like Lumi's pet skill) do not actually increase damage taken from elemental attacks, unlike similar effects that include a "100% chance" clause, which do work correctly against both physical and elemental damage?

**A:** Yes, this is intended behavior: despite the wording, the "damage taken from all attacks is increased by X%" effect only affects physical damage, not elemental damage. This makes it largely ineffective in PvE (where elemental damage dominates) even on effects meant for PvE use, such as the pet skill Lumi. Variants of the text that add a "100% chance" clause do not have this limitation and correctly increase damage from both physical and elemental sources. The discrepancy between how similar-sounding effects are assigned to items/skills is a design decision made by the balance team, not a technical bug.

![screenshot](../../assets/auto-1525653846012198912.png)