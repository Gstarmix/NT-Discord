---
source: discord-officiel/bug-reports
message_id: 1366686727086936166
message_date: 2025-04-29
author: Frontliner1
answered_by: Arczi, friends111
answer_message_id: 1366688054902919189
answer_excerpt: <:YEP:1227856756802060419>
confidence: medium
tags: [combat, debuff, mechanics]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-13
---
# Why can a shot still miss right after the deadly blackout debuff is applied

**Q:** It seems possible to miss an enemy for a while after applying the deadly blackout debuff, even though misses are supposed to stop shortly after application. Is this a known bug?

**A:** This is not a bug: for most skills the blackout debuff is applied by the server only after the skill itself resolves, regardless of when the cast animation or damage numbers appear on screen. This means the skill that applies the debuff can still miss normally, and any follow up attack thrown within roughly the next 0.5 seconds can also miss before the debuff is actually active. A similar confusion exists with Erenia and Zenas: their signature debuffs only set melee (Erenia) or magic (Zenas) defense power to 0, they do not grant guaranteed hits, so misses can still occur against them.