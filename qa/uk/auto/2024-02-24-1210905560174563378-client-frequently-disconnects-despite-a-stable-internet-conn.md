---
source: discord-officiel/bug-reports
message_id: 1210905560174563378
message_date: 2024-02-24
author: MajkelBagietka
answered_by: Bemol, Vastar
answer_message_id: 1210997203284529193
answer_excerpt: Nostale has very old code and probably game doesn't make any effort in order to reconnect you during any packet loss like in other games. Those little hiccups (lost packets) which wouldnt matter in most of the internet games in nostale lead to disconnect. So yes your connection m
confidence: medium
tags: [connection, client]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-13
---
# Client frequently disconnects despite a stable internet connection

**Q:** My internet connection is stable, but the NosTale client keeps kicking me out repeatedly, even after uninstalling, reinstalling and repairing the client multiple times. What can be done about this?

**A:** This is a known limitation of NosTale's old netcode: it does not attempt to reconnect after packet loss, so even a very brief connection hiccup that other modern games would tolerate causes a disconnect in NosTale. There is currently no automatic reconnect feature. Suggested workarounds are trying a different connection (for example a mobile hotspot) or having your hardware and network checked for small intermittent issues.