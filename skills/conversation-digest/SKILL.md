---
name: conversation-digest
description: Digest a long chat or email thread into decisions, open questions, commitments, key numbers and a suggested next message. Use when the user pastes or references a conversation and asks to summarize it, catch up, check what was agreed, or prepare a reply.
---

# Conversation digest

Turn a long conversation into something a busy person can act on in one minute. Stay faithful to the text; quote short phrases when exactness matters.

## Steps

1. Read the entire thread in order before writing anything. Note who the participants are and their roles.
2. Extract decisions: what was agreed, by whom, and when (message date if available).
3. Extract open questions and unanswered requests, and who is expected to answer.
4. Extract commitments: who promised what, with deadlines.
5. Collect every number that matters (prices, quantities, dates, volumes). If the same item appears with different values at different points, flag the conflict and show both with their message dates. Do not silently pick one.
6. Note tone or risk signals (frustration, urgency, hints the other side may be losing interest), briefly and without speculation.
7. Suggest a next message: short, answering the open items first, consistent with the numbers already agreed. Offer it as a draft, never as sent.

## Output format

Headings in order: One-line summary, Decisions, Open questions, Commitments, Numbers and dates (with conflicts), Signals, Draft next message.

## Rules

- Never add facts that are not in the thread.
- If the thread is long, process it in chunks but produce one merged digest.
- Keep the digest under about 300 words unless the user asks for more.
