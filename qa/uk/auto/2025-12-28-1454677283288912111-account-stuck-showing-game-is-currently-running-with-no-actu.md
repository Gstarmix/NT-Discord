---
source: discord-officiel/bug-reports
message_id: 1454677283288912111
message_date: 2025-12-28
author: Swipsi
answered_by: Frostblade, Vastar
answer_message_id: 1454869954645201072
answer_excerpt: There are several reasons that can happen. Even discord itself can cause this because discord just injects him into the NosTale Rendering to Show his weird ass ingame Layout
confidence: medium
tags: [client, login, bug]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-12
---
# Account stuck showing "game is currently running" with no actual process

**Q:** I can't log in on some accounts because they show "game is currently running," even though Task Manager shows no NosTale process for that account, so I can't manually terminate it. How long does it take to clear, and how can I fix it?

**A:** This is a recurring known issue with several possible causes — even Discord's overlay injecting into the NosTale renderer can trigger it — and no single root cause has been identified despite past fixes. Workaround: if Task Manager shows no NosTale process running, close the GameForge Client and kill any remaining related process via Task Manager; this clears the stuck login state just as effectively as killing the NosTale process directly.