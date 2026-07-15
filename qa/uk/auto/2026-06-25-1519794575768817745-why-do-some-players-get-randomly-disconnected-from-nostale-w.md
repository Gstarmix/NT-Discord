---
source: discord-officiel/bug-reports
message_id: 1519794575768817745
message_date: 2026-06-25
author: Araanek
confidence: low
tags: [connection, vpn, disconnect]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-12
---
# Why do some players get randomly disconnected from NosTale while other games work fine?

**Q:** I keep getting disconnected from NosTale even though my internet connection is stable and I never have lag or disconnects in other games. Could this be a provider-side issue?

**A:** This can happen if Gameforge's anti-cheat/network protection flags your ISP as suspicious, for example if that provider also offers or mixes traffic with VPN services. If NosTale blacklists known VPN exit points, being routed through infrastructure shared with VPN traffic can trigger disconnects on NosTale specifically, even though other games (which don't apply the same filtering) work fine.