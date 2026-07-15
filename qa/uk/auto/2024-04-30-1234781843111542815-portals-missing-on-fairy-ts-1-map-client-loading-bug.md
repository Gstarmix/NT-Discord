---
source: discord-officiel/bug-reports
message_id: 1234781843111542815
message_date: 2024-04-30
author: Elodin
confidence: medium
tags: [bug, map, client]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-13
---
# Portals missing on Fairy TS-1 map (client loading bug)

**Q:** On the Fairy TS-1 map, portals sometimes fail to appear at all, even though the rest of the map loads normally. Is this a known bug?

**A:** Yes, this is a known client-side issue: when the client's map loading breaks, portals are typically the only thing missing while everything else looks fine. A client restart fixes it, and staying off your mount while changing maps reduces the chance of it happening again.