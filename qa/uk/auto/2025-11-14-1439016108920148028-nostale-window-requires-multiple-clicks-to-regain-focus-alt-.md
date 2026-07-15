---
source: discord-officiel/bug-reports
message_id: 1439016108920148028
message_date: 2025-11-14
author: SzyszkaGaming
answered_by: Schmelzcookie, Vastar
answer_message_id: 1439022738663805050
answer_excerpt: Sounds like the same problem VanDijk had. Disable your Discord overlay for Nostale
confidence: medium
tags: [bug, discord-overlay, window-focus]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-12
---
# NosTale window requires multiple clicks to regain focus (alt-tab/window switch)

**Q:** When switching to a NosTale window (e.g. alt-tabbing between two NosTale accounts), the window doesn't become active on the first click — it takes 3-4 clicks before input reaches it. Changing resolution with Shift+Enter or switching the graphics engine in ntconfig didn't help. What's causing this?

**A:** This is a known issue related to the Discord overlay. Disabling the Discord overlay for the NosTale process resolves the focus/click problem.