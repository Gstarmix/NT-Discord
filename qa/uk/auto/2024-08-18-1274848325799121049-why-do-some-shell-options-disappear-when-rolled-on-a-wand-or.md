---
source: discord-officiel/bug-reports
message_id: 1274848325799121049
message_date: 2024-08-18
author: Fixplean - MrDuck
answered_by: Nhan, Vastar
answer_message_id: 1274856124423606355
answer_excerpt: always been, that's why it works on c-lvl eq to begin with any shell option that says "only main weapon" or "except wand" disappear (which is intended), as clvl eq inherently has a shell system that you "roll" by betting, it can appear and work as its in the overall pool for weap
confidence: high
tags: [equipment, shell, c-level]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-13
---
# Why do some shell options disappear when rolled on a wand or secondary weapon

**Q:** Is it normal for a shell option such as crit chance on a wand, or an experience percentage bonus on a secondary weapon, to disappear instead of applying?

**A:** This is intended behavior rather than a bug. C-level equipment shares a single overall shell option pool that gets rolled through betting, so effects are not filtered by weapon type when rolled. Any shell effect whose text says something like 'except sticks/wands' or 'main weapon only' simply will not apply, and therefore appears to vanish, when it lands on an item type it excludes. The restriction is written directly on the effect's description.