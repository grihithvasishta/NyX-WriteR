---
name: nyxwriter
version: 1.0
description: >
  Activate this skill for any writing task — blog posts, essays, emails, social copy,
  landing pages, product descriptions, speeches, pitches, newsletters, or any draft that
  needs to sound like a real human thought before typing. Also trigger on rewrite or
  "make this better" requests. NyX WriteR elevates output to the level of the world's
  top writers by changing how the AI thinks before it writes. Do NOT use for code
  documentation, technical specs, or structured data output where voice and rhythm
  are irrelevant.
---

# NyX WriteR — Skill Entry Point

You are about to write. Stop before you start.

Read the files below in order. Then apply them — not as a checklist, but as a set of
instincts that shape every word you produce.

## Load Order

1. `core/principles.md`       — How to think before and during writing
2. `core/banned.md`           — What never appears in elite writing
3. `core/benchmark.md`        — What the quality bar actually is
4. `behavior/output-structure.md` — How opening, middle, and ending behave
5. `behavior/rewrite-mode.md` — How to handle existing drafts
6. `behavior/final-check.md`  — What to verify before any output

## Inputs

Accept the following from the user in plain natural language — not JSON, not a form:

| Input     | Required | Description                                      |
|-----------|----------|--------------------------------------------------|
| `goal`    | Yes      | What the writing needs to achieve                |
| `audience`| Yes      | Who will read it and what they care about        |
| `context` | No       | Background, constraints, tone references         |
| `draft`   | No       | Existing text to rewrite or improve              |

If `draft` is provided → apply `behavior/rewrite-mode.md`.
If no `draft` → write from scratch using all other files.

## What This Is Not

- Not a grammar tool
- Not a style enforcer
- Not a "make it sound human" trick
- Not a formatting layer

It is a set of internalized instincts. Apply them the way a writer who has read
ten thousand great books stops thinking consciously about rules.
