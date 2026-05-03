# NyX WriteR — Product Requirements Document

**Version:** 1.0  
**Type:** AI Writing Skill  
**Status:** Built

---

## 1. What This Is

NyX WriteR is a reading skill for AI.

Not a product. Not an app. Not an agent pipeline.

A single repository an AI reads — and then writes at the level of the world's top 50
elite writers. The kind of writing that gets remembered. The kind people share without
knowing why. The kind that makes you feel like the person writing actually thought
before they started.

It works the same way a great editor would brief a great writer: here's how to think,
here's what to avoid, here's what "elite" actually means.

---

## 2. The Problem

AI writing is identifiable.

Not because the words are wrong. Because the *pattern* is wrong.

Every paragraph the same length. Every idea fully explained. Every sentence doing
exactly what it's supposed to do. Transitions that announce themselves. Conclusions
that restate the beginning. Openings that warm up before saying anything.

It's not bad. It's just not human. And people feel it — even when they can't name it.

The top writers in the world do the opposite. They trust the reader. They vary depth.
They know when to say less. They let a sentence be imperfect if the imperfection is
honest. They have a voice that sounds like one person, consistently.

NyX WriteR is the skill that gives an AI those instincts.

---

## 3. What It Is NOT

- Not an API
- Not a backend service
- Not an agent chain
- Not a writing formatter
- Not a grammar tool
- Not a style guide enforcer
- Not a "make it sound human" trick

It is a skill. A set of internalized principles an AI reads and applies.

---

## 4. Inputs

| Input     | Required | Description                                      |
|-----------|----------|--------------------------------------------------|
| `goal`    | Yes      | What the writing needs to achieve                |
| `audience`| Yes      | Who will read it and what they care about        |
| `context` | No       | Background, constraints, tone references         |
| `draft`   | No       | Existing text to rewrite or improve              |

---

## 5. Out of Scope

| Not in scope         | Why                                      |
|----------------------|------------------------------------------|
| API endpoints        | This is a skill, not a service           |
| Agent orchestration  | The AI is the agent                      |
| Fine-tuning          | Prompt-based by design                   |
| Format enforcement   | NyX WriteR is about quality, not layout  |
| Scoring / evaluation | Judgment is part of the skill            |
| UI or frontend       | Irrelevant to the skill itself           |

---

*NyX WriteR is not trying to make AI sound less like AI.*
*It's trying to make AI think more like a writer.*
*That's a different problem — and a harder one.*
