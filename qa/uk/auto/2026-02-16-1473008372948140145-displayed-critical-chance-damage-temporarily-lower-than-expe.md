---
source: discord-officiel/bug-reports
message_id: 1473008372948140145
message_date: 2026-02-16
author: Wuzkowy👋
answered_by: Vastar
answer_message_id: 1473353174474690653
answer_excerpt: You have party wings, the buff takes few seconds to apply on yourself when puting SP on and get the SLs
confidence: high
tags: [crit, stats, wings]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-12
---
# Displayed critical chance/damage temporarily lower than expected after using an SP

**Q:** Why does the character sheet show a lower critical chance (e.g. 37% instead of the expected 40%) right after using an SP, and then look correct again if you unequip and re-equip the weapon?

**A:** This is not a stat bug but a display timing issue: buffs from party/wings (e.g. Party Firework) take about 1 second to apply after entering SP, and during that brief window the character sheet reflects the pre-buff stats (e.g. still ~99 attack SL instead of the boosted level). If the stat window was already open when the buff applies, it may not auto-refresh, which is why unequipping and re-equipping the weapon (forcing a refresh) shows the correct, higher values.