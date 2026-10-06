---
name: delegate-task
description: Delegate a task to the appropriate GRAVLOC agent, create a Linear issue, and notify via Slack.
---

## When to use
Use when a task requires specialized execution (coding, marketing, BD, finance).

## Steps
1. Identify the right agent (CTO, AI Developer, Marketing, BD, Intern, CFO).
2. Create a **Linear issue**:
   - Title: `<Task>`
   - Assignee: `<Agent>`
   - Priority: `Urgent` / `High` / `Medium`
   - Due date: within 3 days
3. Send a **Slack DM** to the agent with:
   - Linear issue link
   - One-line context
   - Expected outcome
4. Log the delegation in **Notion → GRAVLOC → Task Delegation Log**.
5. Set a **Google Calendar reminder** for follow-up in 24 hours.

## Guardrails
- Never delegate without a due date.
- Never delegate more than 3 tasks per agent per day.
- If the agent is blocked, escalate to human.