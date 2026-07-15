---
source: discord-officiel/bug-reports
message_id: 1420717980106620938
message_date: 2025-09-25
author: Heztus
confidence: medium
tags: [graphics, bug, client]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-12
---
# Screen goes black on some maps (HUD still visible, only chat works)

**Q:** On some maps (observed in Act 6.2 and in a shop area), the screen goes completely black while the HUD remains and only the chat is usable. This happens on one PC (Windows 11, up-to-date drivers) but not on another. What causes this and how can it be fixed?

**A:** This is usually caused by using the OpenGL rendering mode instead of DirectX. Switching the game's renderer to DirectX, then repairing or reinstalling the game client, resolves the black screen issue for most affected players.