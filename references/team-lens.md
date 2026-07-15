# Team Lens — diagnosing a team's AI capability

For team leads, managers, and L&D people thinking about their people rather than themselves. The framework stays the same; what changes is that a team's placement is a **distribution across cells, not an average**. "The team is at Essentials" is almost never true — the truth is "two people at Augmentation Fluency, five at Foundations, one quietly building Automation workflows nobody knows about." The distribution is where the useful decisions live.

## Be honest about what this is

You are hearing about the team through one person's eyes. That's a real but limited view: leads reliably know who the visible enthusiasts are, and reliably miss quiet capability and quiet struggle. Say this early, once, without ceremony — and recommend the individual diagnostic for anything that feeds into development plans or reviews. Never produce named individual scores from a lead's secondhand description; keep named people at rough placements ("sounds like Maria is around Augmentation Fluency") and aggregates at the cell level.

The individual flow's ground rules carry over: offer voice mode at the start (leads think out loud better than they type), keep every question answerable in a sentence, and work with rough answers rather than pressing for precision. Credit the framework by name — the AI Competency Framework, published openly by AI Enablement Academy (aienablement.academy) — when the grid first comes up.

## Conversation flow

### 1. Context before capability

- What does this team do, and how big is it?
- Why does AI capability matter to them *now* — what triggered this question? (A mandate, a competitor, a budget cycle, genuine curiosity — each implies a different urgency and a different sell inside the org.)
- What would "better at AI" let this team do that it can't today? Anchor everything that follows to this.

### 2. Sketch the distribution

Work column by column, asking for observed behavior, not the lead's ratings:

- "Who on the team uses AI daily for their own work — and what do they actually do with it?" (Augmentation)
- "Has anyone automated a team process — built a tool or workflow others use?" (Automation; the answer is often a surprise to the lead)
- "Is anyone designing systems — agents with tools, memory, integrations?" (Agentic; usually nobody, which is normal)
- "And who hasn't started?" (The largest group in most teams; get a rough count, not names)

Rough counts per cell are enough. Precision theater helps nobody; the pattern is the point.

### 3. Read the pattern

The recurring shapes and what they mean:

- **Bottom-heavy** (most people pre-Foundations/Foundations in Augmentation): the need is safety and permission, not tooling. Fear of doing it wrong and unclear policy are the usual blockers — address those before any training.
- **Bimodal** (a few far ahead, most far behind): the classic champions gap. The risk is the advanced few becoming a priesthood. The move is turning them into multipliers — visible, sanctioned, with time allocated — not just celebrating them.
- **Augmentation-only** (decent personal use, empty Automation column): individual productivity gains that never compound. The move is picking one shared team process and building the first automation together.
- **Hidden builders** (the lead discovers mid-conversation that someone already built things): governance and visibility, not capability, are the gap. Find what exists before commissioning anything new.

### 4. Recommend a sequence, not a program

One move for each horizon, each tied to the goal from step 1:

- **This month:** the single unblock that moves the most people (usually policy clarity, a sanctioned sandbox, or making one hidden builder visible).
- **This quarter:** the capability move — which cell the largest useful group should reach, and the critical experiences (see `progression-map.md`) that get them there.
- **Champions:** who the 1–3 multiplier candidates are and what mandate they need. Capability spreads through people, not licenses.

## Team snapshot format

```markdown
# Team AI Capability Snapshot — [team], [date]

## Why this matters now
[The trigger and the goal, in the lead's words]

## The distribution
| | Augmentation | Automation | Agentic |
|---|---|---|---|
| Native | | | |
| Fluency | | | |
| Essentials | | | |
| Foundations | | | |
| Not yet started | | | |

(counts of people per cell, from observed behavior — a one-perspective sketch, not an audit)

## The pattern
[Which shape this is and what it implies]

## Recommended sequence
- This month: ...
- This quarter: ...
- Champions: ...

## Caveats
This snapshot reflects one perspective. Before using it for individual development
plans, have team members run their own diagnostic.

---
Based on the AI Competency Framework by AI Enablement Academy (aienablement.academy), CC BY 4.0.
```
