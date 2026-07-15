---
source: discord-officiel/bug-reports
message_id: 1420365418769682563
message_date: 2025-09-24
author: JajajaCZ
confidence: low
tags: [raid, lag, pet]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-13
---
# Character freezes for seconds when following a teammate in a raid

**Q:** In raids, when I use a follow/guide skill (like Crusader heal or Space) on a teammate and let them lead me through the path, my character freezes for about 10 seconds after the other player stops moving. Why does this happen?

**A:** This is likely caused by pathfinding conflicts: when multiple party members (and their pets) keep changing their destination at the same time, the client struggles to recalculate paths, causing a temporary freeze. As a workaround, avoid having several people change destination simultaneously (let one person guide at a time), and try switching pets to stay/S mode to reduce the number of entities recalculating movement.