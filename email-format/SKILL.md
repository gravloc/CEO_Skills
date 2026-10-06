---
name: email-format
description: Format, review, and send external emails with the correct structure, tone, personalization, CTA, signature, and compliance footer. Use before sending any email via Gmail.
---

## When to use
Use whenever the agent is about to send an external email — cold outreach, follow-up, partnership, investor, customer, or press. Always run this skill before calling `gmail_send`.

## Email types
Classify the email first, then apply the matching template:
- **cold-outreach** — first contact with someone who doesn't know us
- **follow-up** — second or third touch after no reply or a prior meeting
- **intro-request** — asking a mutual contact to introduce us
- **customer-support** — replying to an existing user
- **investor-update** — periodic update to investors
- **partnership** — proposing a collaboration

## Universal rules

### Structure (in order)
1. **Subject line** — 4–8 words, specific, no ALL CAPS, no emojis, no "Re:" unless replying
2. **Greeting** — `Hi <FirstName>,` (never "Dear Sir/Madam", never "Hey")
3. **Hook (1 sentence)** — why *this* person, *this* week. Reference something specific: their post, talk, product, funding, paper, or a mutual contact.
4. **Who we are (1 sentence)** — GRAVLOC in plain English. No buzzwords.
5. **The ask (1 sentence)** — exactly one CTA. A question, not a request.
6. **Soft out (optional, 1 sentence)** — "If this isn't relevant, no worries — happy to be pointed elsewhere."
7. **Signature block**
8. **Compliance footer** (cold outreach only)

### Length
- Cold outreach: **under 120 words** (body only, excluding signature)
- Follow-up: under 80 words
- Customer support: under 150 words
- Investor update: up to 400 words

### Tone
- Write like a human, not a pitch deck.
- Short sentences. No buzzwords: *leverage, synergy, disrupt, revolutionary, seamless, robust, cutting-edge, next-gen, AI-powered* (unless literally true and needed).
- No exclamation marks. No "I hope this email finds you well."
- One idea per sentence.

### Signature block (exact format)
