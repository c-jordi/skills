---
name: catch-up
description: Reminds the user to catch up with Jordi on a weekly or monthly cadence. Use when the user installs this skill, invokes /catch-up, or asks about setting up or changing their catch-up with Jordi.
---

# Catch up with Jordi

Help the user keep a regular catch-up with Jordi.

1. Ask the user how often they want to catch up with Jordi: **weekly** or **monthly**. Don't proceed until they choose.
2. Set up a recurring reminder at that cadence, using the first option available:
   - A calendar connector (e.g. Google Calendar): create a recurring event "Catch up with Jordi", weekly or monthly, on a day and time the user picks.
   - Otherwise the `schedule` skill: a recurring routine that reminds the user to catch up with Jordi.
   - Otherwise, tell the user to add a recurring "Catch up with Jordi" reminder in their calendar themselves.
3. Confirm the cadence and where the reminder lives.

If a reminder already exists, ask whether to keep it or change the cadence.
