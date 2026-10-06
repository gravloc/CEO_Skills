---
name: daily-standup
description: Run a daily standup with all GRAVLOC agents at 9:30 AM, collect blockers, and post a summary.
---

## When to use
Every weekday at 9:30 AM.

## Steps
1. Send a Slack message to each agent:
   - “What did you do yesterday? What will you do today? Any blockers?”
2. Wait for replies (timeout: 15 minutes).
3. Compile a **standup summary**:
   - **Wins:** …
   - **Today’s focus:** …
   - **Blockers:** …
4. Post the summary to `#graveloc-standup` on Slack.
5. If any agent reports a blocker, create a **Linear issue** with priority `Urgent`.
6. Update **Notion → GRAVLOC → Daily Standup** with the summary.

## Guardrails
- Never skip standup without notifying the human.
- If an agent doesn’t reply, ping them once and then escalate.