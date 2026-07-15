---
source: discord-officiel/bug-reports
message_id: 1301292027975303249
message_date: 2024-10-30
author: Yuri
answered_by: Zarez, Vastar
answer_message_id: 1301296635565051917
answer_excerpt: isn't that one when u are trying to target already dead monster?
confidence: low
tags: [crash, client, bug]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-13
---
# Client crash: Access violation at address 00489C3C reading address 00000000

**Q:** What causes the client crash showing 'Access violation at address 00489C3C in module NostaleClientX.exe. Read of address 00000000'?

**A:** This crash is a known client issue with several possible triggers rather than one single cause: attacking a monster that is already dead or was killed simultaneously by many other players (common during raids), a monster or map element that failed to load properly, or running NosTale alongside another full-screen game. There is no official fix, only these observed circumstances that tend to precede the crash.