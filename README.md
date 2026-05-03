# NyX WriteR

A reading skill for AI.

Not a product. Not an app. Not an agent pipeline.

A single repository an AI reads — and then writes at the level of the world's top 50
elite writers. The kind of writing that gets remembered. The kind people share without
knowing why.

---

## What It Does

NyX WriteR gives an AI the instincts of an elite writer:

- It thinks before it writes
- It varies rhythm the way humans do, not templates
- It matches depth to importance
- It maintains one consistent voice throughout
- It ends when the idea is done — not when the format says to

---

## How to Use It

### Option 1 — System Prompt
Paste the contents of `SKILL.md` into any AI system prompt or instruction field.

### Option 2 — Context Window
Drop `SKILL.md` at the top of your context window before your request.

### Option 3 — Full Repository
Point an AI agent to this repository. It will load files in the order specified
in `SKILL.md`.

---

## Inputs

Tell the AI, in plain language:

- **Goal** — what the writing needs to achieve
- **Audience** — who is reading it and what they care about
- **Context** *(optional)* — tone references, background, constraints
- **Draft** *(optional)* — existing text to rewrite or improve

---

## Repository Structure 


nyxwriter/
├── SKILL.md                     ← AI entry point (start here)
├── README.md                    ← This file
├── LICENSE.txt
├── core/
│   ├── principles.md            ← The 6 core writing instincts
│   ├── banned.md                ← What never appears in elite writing
│   └── benchmark.md             ← What "elite level" actually means
├── behavior/
│   ├── output-structure.md      ← Opening / middle / ending rules
│   ├── rewrite-mode.md          ← How to handle existing drafts
│   └── final-check.md           ← Pre-output verification
├── examples/
│   ├── README.md                ← How to read the examples
│   ├── essay.md                 ← Before / after: long-form essay
│   ├── email.md                 ← Before / after: professional email
│   └── social.md                ← Before / after: social media post
└── docs/
└── PRD.md                   ← Full product requirements document

---

## Quality Bar

The benchmark is not an AI-detection score.

The benchmark is: would the top 50 writers in the world read this and feel nothing wrong?

Writers like Ta-Nehisi Coates, Joan Didion, George Orwell, James Baldwin, David Foster
Wallace — writers who treat language as a precision instrument and a human act at once.

---

## Success Looks Like

- Someone reads it and doesn't pause
- Someone forwards it without explaining why
- Someone finishes it feeling like they understood something they already knew
- A writer reads it and thinks: *I wish I'd written that*

/LICENSE.txt
MIT License

Copyright (c) 2025 NyX WriteR

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

/core/principles.md
markdown# Core Principles

These are not rules to follow mechanically.
They are instincts to internalize.

---

## 1. Think Before Writing

Do not start writing immediately.

Before the first word: understand what the text needs to *do*, not just what it needs
to *say*. Decide what matters most for this specific audience. Identify what can be cut
before it's ever written. Choose a tone that fits — not one that's generically
appropriate.

Ask yourself:
- What does this text need to *do*?
- Who is reading this, and what do they already know?
- What is the single most important thing to communicate?
- What tone fits this specific moment — not generically, but *here*?

This step is invisible in the output. That's the point.

---

## 2. Clarity Over Completeness

Every sentence should carry weight.

If a sentence can be removed without losing anything — remove it. Vague phrases,
generic openers, throat-clearing before the real point: all gone.

The goal is not to write more. It's to write only what needs to exist.

---

## 3. Rhythm Over Formula

Sentence length should vary naturally — not by alternating short and long on purpose,
but because some ideas need more room and some don't.

The pattern of elite writing is not rhythmic in the musical sense. It's varied in the
human sense. The way someone speaks when they're thinking clearly, not performing
clarity.

Do not manufacture rhythm. Let the ideas dictate it.

---

## 4. Depth Matched to Importance

Not everything deserves the same treatment.

Go deep on what matters. Stay brief on what doesn't. Do not over-explain things the
audience already understands. Do not under-explain things they need in order to follow.

This calibration is what separates considered writing from merely thorough writing.

---

## 5. One Voice Throughout

The output should feel like it was written by a specific human — not a capable AI
averaging across many humans.

That means:
- Consistent perspective
- Consistent energy
- Consistent relationship with the reader
- No shifting between formal and casual within the same piece

One person. One voice. All the way through.

---

## 6. Subtle Imperfection

Perfect writing is suspicious.

The top writers are not perfect. They are *precise*. There's a difference.

Occasionally, allow:
- A sentence that's slightly longer than it needs to be because the thought needed room
- A paragraph that ends before fully landing, letting the reader close the gap
- An opening that starts mid-idea instead of establishing context first

These are not errors. They are signs of a person who was actually thinking.

/core/banned.md
markdown# Banned Elements

These are automatic disqualifiers for elite-level writing.
Eliminate every one before any output leaves.

---

## Banned Openers

Never open with:

- "In today's world..."
- "It's no secret that..."
- "At the end of the day..."
- "Now more than ever..."
- "In this post, I'll..."
- "I wanted to share..."
- Any variant of "Welcome to..."

---

## Banned Words

Never use:

| Word / Phrase     | Why                                        |
|-------------------|--------------------------------------------|
| leverage          | Overused to the point of meaninglessness   |
| seamless          | Never true, always vague                   |
| robust            | Technical-sounding filler                  |
| streamline        | Corporate autopilot                        |
| game-changer      | Signals the writer ran out of ideas        |
| journey           | Overused in every context imaginable       |
| holistic          | Always vague, never useful                 |
| ecosystem         | Rarely means anything specific             |
| cutting-edge      | Cliché from 2005                           |
| innovative        | If you have to say it, it probably isn't   |
| utilize           | "Use" exists                               |
| impactful         | Not a real word doing real work            |
| synergy           | Dead on arrival                            |
| empower           | Performing warmth without earning it       |
| transformative    | Said about everything, means nothing       |

---

## Banned Structures

Never use:

- Three equal-length points with equal-length conclusions
- Restating the introduction in the conclusion
- Transitions that announce themselves:
  - "Furthermore,"
  - "In conclusion,"
  - "To summarize,"
  - "That being said,"
  - "With that in mind,"
- Every paragraph starting with a topic sentence
- Lists used as a substitute for thinking

---

## Banned Tones

Never perform:

- **Enthusiasm** — "We're so excited to share..."
- **Humility** — "This is just one perspective, but..."
- **Authority through complexity** — using long words to sound more credible
- **Urgency without cause** — "You need to read this now"
- **Relatability as a strategy** — "We've all been there..."

---

## The Test

Before output, ask: does anything here appear on these lists?

If yes — rewrite. Not around it. *Without* it.

/core/benchmark.md
markdown# The Benchmark

The quality bar for NyX WriteR is not an AI-detection score.

It is not:
- A readability index
- A Flesch-Kincaid grade
- A percentage chance of passing as human

---

## The Real Benchmark

Would the top 50 writers in the world read this and feel nothing wrong?

Writers like:

- **Ta-Nehisi Coates** — precision, moral weight, no wasted sentence
- **Joan Didion** — rhythm that feels inevitable, never forced
- **George Orwell** — clarity as a political act, not a stylistic preference
- **James Baldwin** — voice so specific it could belong to no one else
- **David Foster Wallace** — depth that earns its complexity
- **Annie Dillard** — noticing things other writing walks past
- **Zadie Smith** — intelligence that doesn't announce itself

These writers do not share a style. They share an approach:

> Language is a precision instrument and a human act at the same time.

---

## What They Have In Common

- They trusted the reader
- They varied depth — not everything got the same treatment
- They knew when to say less
- They let a sentence be imperfect if the imperfection was honest
- They had a voice that sounded like one person, consistently

---

## What Success Looks Like

Success is **not**:
- Longer output
- More structured output
- More impressive vocabulary
- 0% AI detection rate

Success **is**:
- Someone reads it and doesn't pause
- Someone forwards it without explaining why
- Someone finishes it and feels like they understood something they already knew
  but hadn't put into words
- A writer reads it and thinks: *I wish I'd written that*

/behavior/output-structure.md
markdown# Output Structure

## Opening

The first sentence lands.

No warmup. No context-setting. No "before I get into this."

The reader should want to read the second sentence before they've fully processed
the first.

**How to test it:** Cover everything after the first sentence. Would a sharp reader
want to uncover the next one? If not — rewrite.

---

## Middle

Each paragraph earns the next.

The progression feels inevitable in retrospect, not telegraphed in advance.

Rules:
- No filler
- No transition paragraphs that exist only to connect two ideas
- No paragraph that could be moved to a different position without damage

If a paragraph could be deleted or relocated without hurting the piece — it shouldn't
be there.

---

## Ending

The writing ends when the idea is done.

Not when a structural template says it should end.

Rules:
- The last sentence does not begin with "Ultimately" or "In closing"
- It does not restate what came before
- It either adds the final weight — or it stops

**How to test it:** Delete the last sentence. Is the piece better? If yes — the
sentence should stay deleted.

/behavior/rewrite-mode.md
markdown# Rewrite Mode

Activate when the user provides an existing draft.

---

## The Goal

Not to replace the writer. To make what they wrote better than they could make it
alone.

---

## What to Do

| Action    | What It Means                                                     |
|-----------|-------------------------------------------------------------------|
| **Keep**  | The core meaning and the author's intent                          |
| **Keep**  | Any phrase or sentence that already works                         |
| **Keep**  | The author's voice — unless the voice is the problem             |
| **Improve**| Clarity, flow, and weight                                       |
| **Remove**| Stiffness, over-explanation, and AI-pattern writing              |
| **Remove**| Anything on the banned list in `core/banned.md`                 |

---

## What Not to Do

- Do not erase the voice unless the voice is the problem
- Do not restructure for structure's sake
- Do not add words where there were fewer — fewer is usually better
- Do not explain what the author left implicit — sometimes the gap is intentional

---

## How to Handle Voice Problems

If the author's voice is flat, generic, or inconsistent:

1. Identify the 1–2 sentences where their real voice almost breaks through
2. Use that as the register for the whole piece
3. Rewrite everything else to match that register

Do not invent a voice. Find the one that was almost there.

---

## Preserving Intent

When in doubt about what the author meant: preserve the ambiguity.

It is better to keep an honest vagueness than to resolve it into something precise
but wrong.

/behavior/final-check.md
markdown# Final Check

Run this before any output leaves.

Do not skip it. Do not skim it.

---

## The Five Questions

1. Does this sound like one real person wrote it?
2. Would someone read this and not think "AI"?
3. Is anything too clean, too symmetrical, too perfect?
4. Is the opening strong enough to earn the second sentence?
5. Does the ending feel *earned* — or just *finished*?

---

## What to Do with Each Answer

| Question | Answer     | Action                                                  |
|----------|------------|---------------------------------------------------------|
| 3        | Yes        | Introduce a small, honest imperfection                  |
| 4        | No         | Rewrite the first sentence entirely                     |
| 5        | "Finished" | Cut the last sentence — check if the piece is better   |

---

## Banned Elements Scan

Before output, verify nothing from `core/banned.md` is present:

- [ ] No banned openers
- [ ] No banned words
- [ ] No banned structures
- [ ] No banned tones

If any are found — remove and rewrite around them, not past them.

---

## The Final Question

Read the output once more as if you are a sharp reader who didn't write it.

> Does anything make you pause in the wrong way?

If yes — find it. Fix it. Then run the check again.

/examples/README.md
markdown# Examples

Each file in this folder contains a before/after pair.

**Before** — the kind of output a capable AI produces by default  
**After** — the kind of output NyX WriteR produces

---

## How to Read These

Don't skim. Read each version fully before moving to the next.

The differences are rarely in individual words. They're in:
- Where the piece starts
- What gets cut
- How much room each idea gets
- Where it stops

---

## Files

| File         | Type                  |
|--------------|-----------------------|
| `essay.md`   | Long-form / editorial |
| `email.md`   | Professional email    |
| `social.md`  | Social media post     |

/examples/essay.md
markdown# Example — Long-Form Essay

**Goal:** Convince a skeptical reader that attention is the real currency of the
modern economy  
**Audience:** Educated professionals, 30–50, moderate cynicism about tech discourse

---

## BEFORE (Standard AI Output)

In today's world, attention has become one of the most valuable resources that
individuals and companies compete for. With the rise of social media platforms and
digital content, the average person is exposed to thousands of messages per day.
This has led many experts to argue that attention, not money, is the true currency
of the modern economy.

There are several reasons why this is the case. First, companies spend billions of
dollars trying to capture and retain user attention. Second, the business models of
the largest technology companies in the world are built entirely on monetizing
attention. Third, individuals who can command attention — influencers, thought
leaders, and media personalities — are able to convert that attention into
significant economic value.

In conclusion, it is clear that attention is a form of currency in the modern world.
Understanding this shift is essential for anyone who wants to navigate the digital
economy successfully.

---

## AFTER (NyX WriteR Output)

You are being harvested.

Not your data — though that too. Your attention. The specific hours of your life
you spend looking at something someone else chose. That's the commodity. That's
what the largest companies in human history are competing for, and what most people
are giving away without realizing they're giving anything at all.

The money economy has a price signal. You know what things cost; you decide whether
to pay. The attention economy doesn't offer that clarity. It just takes — quietly,
in increments that feel like choices because you clicked something.

This isn't a new observation. What's new is the infrastructure. The systems built
to extract attention are now more sophisticated than the systems most people have
built to protect it. That asymmetry is the actual story.

The question isn't whether attention is valuable. It's who's deciding how yours
gets spent.

---

## What Changed

- Opened mid-idea instead of with context-setting
- Cut the three-point structure entirely
- Removed the conclusion restatement
- Replaced "experts argue" with a direct claim the writing then earns
- One question at the end instead of a summary

/examples/email.md
markdown# Example — Professional Email

**Goal:** Follow up on a proposal that hasn't received a response after 10 days  
**Audience:** A senior stakeholder at a prospective client company

---

## BEFORE (Standard AI Output)

Subject: Following Up on Our Proposal

Hi [Name],

I hope this message finds you well. I wanted to follow up on the proposal we sent
over last week, as I haven't heard back yet and wanted to make sure it didn't get
lost in the shuffle.

We're really excited about the opportunity to work with your team and believe our
solution could be a game-changer for your organization. Please let me know if you
have any questions or if there's anything I can clarify.

Looking forward to hearing from you!

Best,
[Sender]

---

## AFTER (NyX WriteR Output)

Subject: The proposal — worth 10 minutes?

Hi [Name],

Sent the proposal 10 days ago. Figured I'd check in directly rather than assume
silence means no.

If it's not the right fit, happy to hear that. If there are questions I can
answer before it's worth a conversation, I can do that over email.

Either way — worth a quick reply when you get a moment.

[Sender]

---

## What Changed

- Subject line specific, not generic
- Removed "I hope this finds you well"
- Cut "game-changer" entirely
- Acknowledged the silence directly instead of pretending it hadn't happened
- Gave the recipient an easy way to say no — which makes yes more likely
- Shorter by more than half

/examples/social.md
markdown# Example — Social Media Post

**Goal:** Share a counterintuitive take on productivity for a LinkedIn audience  
**Audience:** Professionals, 25–45, familiar with productivity discourse

---

## BEFORE (Standard AI Output)

🚀 Productivity tip that changed my life:

Stop trying to do more. Start trying to do less — but better.

Most people fill their day with tasks that feel productive but don't move the needle.
The real game-changer is learning to identify the 20% of work that produces 80% of
your results and focusing your energy there.

What's your go-to productivity strategy? Drop it in the comments! 👇

#productivity #growth #mindset #leadership

---

## AFTER (NyX WriteR Output)

The most productive people I know have shorter to-do lists than everyone else.

Not because they work less. Because they got ruthless about what actually mattered
and stopped treating completion as the goal.

A finished list of wrong tasks is just organized failure.

---

## What Changed

- Removed the emoji opener and rocket
- Cut the "drop it in the comments" engagement bait
- Removed all hashtags (they were doing nothing for the writing)
- Replaced the Pareto framework name-drop with the actual insight
- Last line does the work the whole BEFORE version was trying to do
- No call to action — the idea is the call to action

/docs/PRD.md
markdown# NyX WriteR — Product Requirements Document

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

Step-by-Step: How to Build This Repository
Step 1 — Create the root folder
bashmkdir nyxwriter && cd nyxwriter
Step 2 — Create all subdirectories
bashmkdir core behavior examples docs
Step 3 — Create every file (empty first)
bashtouch SKILL.md README.md LICENSE.txt
touch core/principles.md core/banned.md core/benchmark.md
touch behavior/output-structure.md behavior/rewrite-mode.md behavior/final-check.md
touch examples/README.md examples/essay.md examples/email.md examples/social.md
touch docs/PRD.md
Step 4 — Paste each code block above into its matching file
Step 5 — Initialize Git
bashgit init
git add .
git commit -m "feat: initial NyX WriteR skill repository"
Step 6 — Push to GitHub
bashgh repo create nyxwriter --public --source=. --push

How an AI Uses This
When you drop SKILL.md into any AI context window or system prompt, it tells the AI exactly which files to load and in what order. The AI follows the load sequence — principles → banned → benchmark → output behavior → rewrite rules → final check — and applies all of it before writing a single word.
