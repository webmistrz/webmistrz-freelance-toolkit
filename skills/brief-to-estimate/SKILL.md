---
name: brief-to-estimate
description: Turn a client brief, spec or list of wishes into a scoped estimate with work items, hour ranges, assumptions, risks and clarifying questions. Use when the user asks to estimate, scope, price or risk-check a request, project brief or technical specification.
---

# Brief to estimate

Produce an honest, structured estimate from an unstructured brief. Never invent facts the brief does not contain; mark them as assumptions.

## Steps

1. Read the whole brief. Restate the goal in one sentence. If two readings are plausible, state both and pick one explicitly as the working assumption.
2. Split the work into items small enough to estimate (roughly 2 to 24 hours each). Group them by area (design, frontend, backend, integrations, content, testing, deployment).
3. For each item give a range (optimistic to pessimistic hours) and one line on what drives the uncertainty. Do not give a single falsely precise number.
4. Add the usual hidden work as separate lines when relevant: setup, revisions, QA, deployment, documentation, communication overhead.
5. List assumptions (anything you decided because the brief was silent).
6. List risks: vague requirements, third-party dependencies, missing assets or access, unclear ownership of decisions, scope that tends to grow. Give each a likelihood (low/medium/high) and what it would add to the estimate.
7. List out-of-scope items explicitly, including things the client may reasonably expect.
8. Write 3 to 7 clarifying questions, ordered by how much each answer changes the estimate.
9. Give a total range, and a suggested fixed-price figure only if the user asks for one. If they do, state the buffer used.

## Output format

Use these headings in order: Goal, Work items (table: item, hours low, hours high, driver), Assumptions, Risks, Out of scope, Questions for the client, Total.

## Rules

- Keep numbers consistent: the totals must equal the sums of the table.
- If the brief is too thin to estimate, say so and return only the questions.
- Do not include client names or personal data in the output unless the user supplied them and asked for them.
