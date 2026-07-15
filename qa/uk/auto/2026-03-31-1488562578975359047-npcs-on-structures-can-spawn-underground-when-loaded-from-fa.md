---
source: discord-officiel/bug-reports
message_id: 1488562578975359047
message_date: 2026-03-31
author: friends111
answered_by: Vastar
answer_message_id: 1488576801419821280
answer_excerpt: Generally i've noticed NPC's placed on structures are spawned under the structure if the NPC is at a huge distance from you 🤷‍♂️ (the traveller from tart hapendam if you enter the map from the oasis portal vs when you enter map next to it from arena)
confidence: medium
tags: [npc, bug, graphics]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-13
---
# NPCs on structures can spawn underground when loaded from far away

**Q:** Why does Jerico in Sunny Meadows (and similar NPCs placed on top of structures) sometimes appear underground or inside the terrain?

**A:** This is a known client-side spawning quirk: NPCs positioned on top of a structure can render underneath/inside that structure if the player is far away when the NPC first loads. The same behavior has been observed with other NPCs, such as the traveler at Tart Hapendam appearing correctly when entering from the arena side but glitching when entering from the oasis portal. Getting closer or approaching the map from a different entry point can avoid or fix the visual glitch.