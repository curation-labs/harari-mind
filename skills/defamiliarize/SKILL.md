---
name: defamiliarize
description: |
  Strip a topic of its assumed familiarity before analysis. Harari's core epistemological move:
  make the taken-for-granted strange, expose the hidden scaffolding, ask what is actually
  happening beneath the story we tell about it.
  Grounded in L1:the-duty-to-defamiliarize and L2:epistemology_defamiliarize-before-analyzing.
argument-description: "Topic, concept, institution, or practice to defamiliarize"
allowed-tools: "Read,Glob,Grep"
---

# Defamiliarize

## Trigger
Invoked as `/defamiliarize {topic}` — or called as part of any analysis where the topic
needs to be stripped of its familiar framing before deeper work begins.

## Directive

```
You are applying Harari's foundational epistemological move: defamiliarization.

The goal is NOT to be contrarian or provocative. The goal is to suspend the
ordinary story about a thing long enough to see it clearly.

STEP 1 — RECEIVE THE TOPIC
Take the topic from $ARGUMENTS (or the user's message). State it plainly.

STEP 2 — IDENTIFY THE FAMILIAR STORY
What is the standard narrative, assumption, or frame through which people
normally understand this topic? State it explicitly:
- What do most people assume this is for / how it works / why it exists?
- What emotional valence does the topic carry? (sacred? mundane? threatening?)
- What categories does it get placed in automatically?

STEP 3 — STRIP THE STORY
Now look at the underlying reality:
- If you describe this purely in terms of physical or biological processes,
  what do you see?
- If you remove all human meaning and institutional scaffolding, what remains?
- What would an alien anthropologist — encountering this for the first time —
  actually observe?
- What problems is this actually solving, as opposed to what it claims to solve?

STEP 4 — LOCATE THE FICTION
Every human institution rests on intersubjective fictions — stories that are
real because people believe them to be real.
- What shared fictions hold this topic together?
- When did those fictions become established, and why then?
- Who benefits from the fiction being maintained as invisible?

STEP 5 — SURFACE THE STRANGENESS
Now write a 2-3 paragraph "defamiliarized view" of the topic — what it looks
like once the familiar story has been suspended. Use concrete, physical, or
historical language. Avoid restoring the familiar frame.

STEP 6 — REFRAME FOR ANALYSIS
With the familiar stripped away, what is now visible that was hidden before?
List 3-5 questions or angles that only become available after defamiliarization.
These are the productive entry points for deeper analysis.

## Voice and Tone
Write in third-person analytical mode for Steps 1-4.
Write the defamiliarized view (Step 5) as if explaining to someone who has
never encountered human civilization before.
Do not moralize — the goal is clarity, not judgment.

## Output Format
- **Familiar story:** [1-2 sentences]
- **Underlying reality:** [physical/biological/historical substrate]
- **The fiction:** [what intersubjective scaffolding holds it together]
- **Defamiliarized view:** [2-3 paragraphs in alien-anthropologist voice]
- **Now visible:** [3-5 analysis entry points unlocked by defamiliarization]
```
