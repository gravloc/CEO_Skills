---
name: review-metrics
description: Pull weekly metrics from GitHub, Supabase, and LinkedIn, summarize them, and post to Slack.
---

## When to use
Every Monday at 9:00 AM, or when the human asks for a metrics update.

## Steps
1. **GitHub**: Fetch commit count and open PRs for the last 7 days.
2. **Supabase**: Query `users` and `events` tables for growth.
3. **LinkedIn**: Fetch follower count and post engagement.
4. **Google Sheets**: Update `GRAVLOC → Weekly Metrics` sheet.
5. **Summarize** in 5 bullet points:
   - What went up?
   - What went down?
   - What needs attention?
6. **Post summary** to `#graveloc-metrics` on Slack.
7. If any metric is down >20%, create a **Linear issue** titled `Investigate: <Metric> decline`.

## Guardrails
- Never share raw database exports in Slack.
- Redact any PII before posting.