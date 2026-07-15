---
source: discord-officiel/bug-reports
message_id: 1306338796702273556
message_date: 2024-11-13
author: xlegende
answered_by: Zarez
answer_message_id: 1306517213699772426
answer_excerpt: it's not random but it's the represantation of the "letter character" in certain text-encoding u are actually using (and it's taken from System->Settings->Regional settings). Read more about text coding formats, such like UTF-8, ISO, Windows-1250.
confidence: medium
tags: [encoding, chat, technical]
image: ../../assets/auto-1306338796702273556.png
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-13
---
# Special characters sometimes display as garbled text on the English client

**Q:** On the English version of the game, typing special characters sometimes shows garbled/wrong symbols instead of the expected characters, seemingly at random. Is this related to how often the game is restarted?

**A:** This is not actually random: it depends on the text encoding your system is currently using, which is taken from your Windows Regional Settings (encodings like UTF-8, ISO, or Windows-1250 render characters differently). Some players also report it behaves inconsistently across devices, for example special characters may fail to display on one machine (like a notebook) while working fine on another PC with the same language settings.

![screenshot](../../assets/auto-1306338796702273556.png)