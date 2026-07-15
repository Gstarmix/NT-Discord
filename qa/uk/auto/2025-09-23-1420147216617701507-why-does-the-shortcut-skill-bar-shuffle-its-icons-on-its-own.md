---
source: discord-officiel/bug-reports
message_id: 1420147216617701507
message_date: 2025-09-23
author: Kirito | Marcel
answered_by: LeTaLL, Nino
answer_message_id: 1420147451066847332
answer_excerpt: if you take stuff out of bazar it breaks until you use a skill
confidence: medium
tags: [ui, bazaar]
image: ../../assets/auto-1420147216617701507.png
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-12
---
# Why does the shortcut/skill bar shuffle its icons on its own?

**Q:** Why does the shortcut bar sometimes rearrange itself unexpectedly, seemingly after the game window has been in the background for a while or after taking something out of the bazaar?

**A:** Known issue: taking an item out of the bazaar can break/shuffle the shortcut bar. This happens because any acquired equipment-type item (weapon, hat, accessory, costume, C45 weapon, etc.) shares its inventory slot type with items already placed in the shortcut bar, so those bar slots get swapped to something else. Potions and other non-equipment items in the bar are unaffected. Using any skill, or doing a self-buff, afterward restores the bar to normal.

![screenshot](../../assets/auto-1420147216617701507.png)