---
source: discord-officiel/bug-reports
message_id: 1495734942938697788
message_date: 2026-04-20
author: Manuel1
answered_by: Kaleinyo
answer_message_id: 1495757856367181956
answer_excerpt: If you failed too much time, you have a soft ban 12/24hr (can't remember) where you will automatically fail your login. And timer reset on each attempt
confidence: medium
tags: [login, client, 2fa]
status: auto  # distillé automatiquement, non relu
distilled: 2026-07-12
---
# GF Client login fails without 2FA prompt after repeated failed attempts

**Q:** Why can I log in fine through the browser, but the GF Client gives an error and doesn't even prompt for 2FA?

**A:** This happens when you've failed too many login attempts and triggered a temporary soft ban (roughly 12-24 hours) that causes the client to automatically fail login without prompting for 2FA. Each new failed attempt resets the ban timer, so you need to stop trying and simply wait it out.