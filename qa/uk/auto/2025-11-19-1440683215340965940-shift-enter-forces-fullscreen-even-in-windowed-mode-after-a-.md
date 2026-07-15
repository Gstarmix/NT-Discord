---
source: discord-officiel/bug-reports
message_id: 1440683215340965940
message_date: 2025-11-19
author: Moon
answered_by: Vastar
answer_message_id: 1440683871120261190
answer_excerpt: You probably changed the screen bit from the nt.config, try changing it
confidence: medium
tags: [client, fullscreen, config]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-12
---
# Shift+Enter forces fullscreen even in windowed mode after a client update

**Q:** Since a recent maintenance, pressing Shift+Enter always switches to fullscreen even when windowed mode is set, whereas before it didn't. Is there a way to stop this behavior?

**A:** This is likely related to the screen bit setting in the client's nt.config file. Changing that value in nt.config reportedly stops Shift+Enter from forcing fullscreen mode.