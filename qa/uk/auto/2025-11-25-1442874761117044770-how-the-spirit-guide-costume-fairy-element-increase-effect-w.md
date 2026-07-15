---
source: discord-officiel/bug-reports
message_id: 1442874761117044770
message_date: 2025-11-25
author: Sizumi(+99)
answered_by: mitchi
answer_message_id: 1442885428322500649
answer_excerpt: To clear up the effect "On attack there is a X% chance of increasing your equipped fairy's element by Y" once and for all, I will talk about the fixed version: - It will stack with Tropical Wings, Chance and Value - It works when fighting monsters and attacking them, it's not pas
confidence: high
tags: [fairy, costume, element]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-12
---
# How the Spirit Guide Costume fairy-element-increase effect works

**Q:** Does the fairy element increase option on the Spirit Guide Costume actually apply, and how does it work?

**A:** In its current (fixed) version, the effect "On attack, X% chance to increase your equipped fairy's element by Y" stacks with Tropical Wings, Chance and Value. It only triggers during combat when you actually attack a monster, not passively on every server tick, and when it triggers all monsters present receive the extra elemental damage. Previously there was a visual bug showing an incorrect increase in the character window, and the bonus was only being applied to some monsters instead of all of them when triggered.