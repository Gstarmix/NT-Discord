---
source: discord-officiel/eu-dragonveil
message_id: 1449140665953943703
message_date: 2025-12-12
author: Blauker
confidence: medium
tags: [crash, technical, bug]
image: ../../assets/auto-1449140665953943703.png
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-12
---
# Access violation crash (NostaleClientX.exe) when Valorant is running

**Q:** I get an Application Error (EAccessViolation in NostaleClientX.exe, access violation reading address 00000000) when Valorant is running at the same time as NosTale. What causes this and how do I fix it?

**A:** NosTale can conflict with certain other games running at the same time, such as Valorant (likely due to its kernel level anti-cheat driver), causing an access violation crash. Closing the other game resolves the issue. If you need both running, sometimes changing the order in which you launch the programs (for example starting Valorant first, then NosTale) can avoid the access violation error.

![screenshot](../../assets/auto-1449140665953943703.png)