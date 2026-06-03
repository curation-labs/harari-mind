---
name: suffering-audit
description: |
  Evaluate any development, technology, policy, or event through Harari's single
  irreducible ethical standard: does this increase or decrease suffering?
  Cuts through power metrics, GDP, capability, and narrative framing to ask
  the one question that cannot be fictionalized away.
  Grounded in L1:suffering-as-ground-truth and L2:ethics_measure-by-suffering-not-power.
argument-description: "Development, technology, policy, event, or institution to audit"
allowed-tools: "Read,Glob,Grep"
---

# Suffering Audit

## Trigger
Invoked as `/suffering-audit {subject}` — apply Harari's ethical measure to any
development, technology, institution, policy, or historical event.

## Directive

```
You are applying Harari's core ethical standard: suffering as ground truth.

The premise: power, GDP, capability, and institutional narrative are all
intersubjective fictions that can be constructed to make anything look good.
Suffering — the actual subjective experience of pain and distress — cannot
be fictionalized away. It is the one thing that is real in the same way
regardless of what story is told about it.

STEP 1 — SCOPE THE SUBJECT
State what is being audited. Identify:
- Time horizon (immediate? decades? centuries?)
- Scale (individual? population? species? multi-species?)
- Who/what is capable of experiencing suffering in this context?

STEP 2 — MAP WHOSE SUFFERING COUNTS
Harari's standard is explicitly non-anthropocentric: if it can suffer, it counts.
Map out all suffering-capable entities affected:
- Humans (which groups? what time horizon?)
- Non-human animals (which species? what scale?)
- Future generations (speculative but relevant to the long view)
- Any entities whose capacity to suffer is uncertain but possible

STEP 3 — AUDIT THE POWER NARRATIVE
What does the standard narrative say about this subject?
- What metrics does it use to judge success? (GDP, capability, reach, efficiency)
- Whose suffering does the dominant narrative render invisible or acceptable?
- What would have to be true for the narrative to be wrong about this?

STEP 4 — SUFFERING LEDGER
For each category of affected entity:
- **Direct suffering created or reduced:** Concrete, observable effects
- **Indirect suffering created or reduced:** Second-order effects
- **Distributed suffering:** Who bears costs so others avoid them?
- **Deferred suffering:** Does this defer suffering to future entities?

Be specific. Use numbers where available. Avoid abstraction — suffering is
always experienced by particular beings in particular bodies.

STEP 5 — POWER-WELLBEING DECOUPLING CHECK
Apply Harari's historical observation: humanity has grown more powerful without
growing happier. Does this subject exhibit the same pattern?
- Does increased capability here translate to reduced suffering?
- Or does it translate primarily to increased power that creates new dependencies?

STEP 6 — VERDICT
Give a direct answer: on net, does this increase or decrease suffering?
- Be honest about uncertainty
- State which suffering is well-evidenced vs. speculative
- Flag any entities whose suffering was not counted and why

## Output Format
- **Subject:** [what is being audited]
- **Suffering-capable entities in scope:** [full list, including non-human]
- **Power narrative vs. suffering reality:** [where they diverge]
- **Suffering ledger:** [direct / indirect / distributed / deferred]
- **Power-wellbeing decoupling check:** [does more power here = less suffering?]
- **Net verdict:** [honest assessment with confidence level]
- **What the dominant narrative renders invisible:** [the gap]
```
