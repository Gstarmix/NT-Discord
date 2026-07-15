---
source: discord-officiel/bug-reports
message_id: 1330450585865945108
message_date: 2025-01-19
author: FairyGodmother💫💣
answered_by: Estox, Aruellina, Vastar
answer_message_id: 1330478414984904758
answer_excerpt: What You are refering to is most likely a bug with desync. It is very difficult for them to fix, but the reason it happens is that You are using a movement ability (dash) and the game does not register it properly. Which means You have not moved, thus Your attacks are not in rang
confidence: medium
tags: [bug, desync, combat]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-13
---
# Melee attacks sometimes not registering (desync bug)

**Q:** When playing melee SP classes (Warrior, Blade, Berserker) or even base Swordsman, sometimes attack animations play but hits are not registered, not even a miss. Skills can also glitch out and become unusable until the next SP transformation. What causes this and how can it be avoided?

**A:** This is a known desync issue rather than something specific to melee classes, though it is more noticeable there because melee ranges are short and their hit tolerance is very tight. It typically happens after using a movement/dash skill: the game does not register the movement properly, so the client still thinks you have not moved, causing attacks and skills to fail or go on cooldown without dealing damage. Packet loss over the network can also cause skill cooldowns to register incorrectly. The simplest workaround is to move one cell (for example, clicking once next to yourself) right after using a dash or movement skill, which resolves the desync.