---
source: discord-officiel/bug-reports
message_id: 1415617327164162048
message_date: 2025-09-11
author: Bastion
answered_by: LeTaLL
answer_message_id: 1415617585550196806
answer_excerpt: Close all nostale clients and gameforge clients from task manager if any still runing or restart pc and retry
confidence: medium
tags: [installation, gameforge, launcher]
image: ../../assets/auto-1415617327164162048.png
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-12
---
# "This folder is protected" repair loop when launching via GameForge client

**Q:** The NosTale/GameForge client shows 'This folder is protected' and gets stuck in a repair loop; restarting doesn't fix it. Which folder is protected and how can this be fixed?

**A:** First, make sure all NosTale and GameForge client processes are fully closed in Task Manager (or restart the PC) before retrying. If the message persists, it usually means NosTale is installed as a sub-folder of a Windows-protected directory (e.g. under Program Files), so the GameForge client lacks the privileges needed to repair or start it. Move or reinstall the game into a directory without special permission restrictions.

![screenshot](../../assets/auto-1415617327164162048.png)