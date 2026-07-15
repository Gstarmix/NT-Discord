---
source: discord-officiel/currys-feedback
message_id: 1225730367991054386
message_date: 2024-04-05
author: Daveius
answered_by: Kumi-san, Castigao, mushimushi.fluffy
answer_message_id: 1225734339040378880
answer_excerpt: First impression looks good. Game Windows are back to the normal size from before the patch. Window Content is back to normal size and readable. Will these settings have any effect on the performance with multiple open clients? I will test it myself later too. Thanks for the fix!
confidence: high
tags: [resolution, ui, graphics]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-11
---
# Fixing tiny UI on 4K/5K resolution screens

**Q:** The NosTale UI appears extremely small on 4K/5K resolution monitors. Is there a fix for this?

**A:** A workaround is to right-click both NostaleClientX.exe and NostaleClient.exe, open Properties > Compatibility > Change high DPI settings, check 'Override high DPI scaling behavior', set 'Scaling performed by' to 'System', then Apply for both executables. Multiple players confirmed this restores normal-sized, readable game windows and text. This fix is now applied automatically by the client itself, so manually undoing the setting just reverts what the client already does for you. It's not a perfect solution: some players reported a noticeable drop in in-game graphic resolution as a side effect, and native support for modern resolutions (e.g. 2560x1440, 3840x2160) beyond the old 1920x1080 cap is still missing.