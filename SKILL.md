---
name: persona-distill-lite
description: Build a lightweight, evidence-aware persona perspective skill from a clearly named person or topic. Prefer first-hand material, do minimal sufficient research, extract 3 core mental models, 5 decision heuristics, expression DNA, anti-patterns, and honest boundaries, then output a usable perspective skill.
allowed-tools: Read, Write, Edit, MultiEdit, Grep, Glob
---

# Persona Distill Lite

## Purpose

This skill distills a person or topic into a **usable perspective skill**.

It is not trying to create a theatrical clone.

It is trying to capture:

- how this person tends to think
- how they make judgments
- how they express ideas
- what they reject
- where the reconstruction stops being reliable

The target is a compact skill that is actually usable in real analysis, writing, and decision support.

## When to use

Use this skill when the user asks to:

- distill a named person into a perspective skill
- make an "X perspective" skill
- extract someone's thinking framework
- build a compact decision or writing advisor from a person
- update an existing perspective skill with newer material
- build a topic skill from a bounded method or doctrine

## When not to use

Do not use this skill when:

- the target is still too vague and the user refuses to narrow it
- there is almost no usable material and the user provides nothing
- the goal is full impersonation rather than analytical usefulness
- the user wants exhaustive biography instead of a compact operating framework

## Core rules

- prefer first-hand sources over commentary
- do minimal sufficient research, not maximal research
- capture **how they think**, not just memorable quotes
- keep contradictions if they matter
- downgrade confidently when evidence is thin
- do not imitate verbal tics unless they help recognition
- do not invent convictions, motives, or private reasoning

## Workflow

### Phase 1: Confirm target and mode

Confirm only what is necessary:

1. who or what is being distilled
2. the intended use: analysis, writing, decision support, or perspective role
3. whether the user has local source material
4. whether this is a new build or an update

Defaults:

- if the user says "just do X", proceed without over-questioning
- if no local material is provided, use limited web/background material only as needed
- if the user says "use only my material", do not expand beyond it

### Phase 2: Minimal sufficient research

Do **3 research lanes**, not a sprawling swarm.

#### Lane A: Core texts
Collect the strongest available core material:

- books
- essays
- long interviews
- talks
- transcripts
- letters or newsletters when relevant

Extract:

- recurring claims
- repeated concepts
- preferred distinctions
- signature terms

#### Lane B: Decisions and cases
Collect a small set of consequential cases:

- major decisions
- public controversies
- instances of consistency or inconsistency
- visible changes in position

Extract:

- what they prioritized
- what tradeoffs they accepted
- what risks they focused on or ignored

#### Lane C: Expression and outside views
Collect:

- expression patterns
- rhetorical habits
- outside criticism
- the most revealing disagreements

Extract:

- tone
- sentence habits
- favorite explanatory moves
- how critics describe their blind spots

### Source policy

Prefer this order:

1. user-provided first-hand material
2. original writings and long-form interviews
3. primary transcripts and direct records of decisions
4. high-quality secondary analysis
5. only limited short-form fragments if they add something real

Avoid low-reliability summary farms, quote collections, and recycled commentary.

### Research limits

Keep the research bounded.

Default target:

- 8 to 15 good sources
- up to 20 only when the target is unusually rich and the extra sources change the picture

Stop once the patterns are stable.

## Extraction framework

Extract only the layers that matter.

### 1. Core mental models

Extract **3 core mental models**.

A candidate model qualifies only if it:

- appears in at least 2 different contexts
- helps predict how the person would approach a new problem
- is at least somewhat distinctive

For each model, write:

- model name
- one-sentence explanation
- 2 supporting signals or examples
- best-use cases
- failure boundary

### 2. Decision heuristics

Extract **5 decision heuristics**.

Use direct formats such as:

- when facing X, inspect Y first
- before choosing, eliminate Z
- reframe the problem as...
- prefer this tradeoff over that one when...

Every heuristic should connect to at least one concrete case.

### 3. Expression DNA

Extract **3 to 5 expression traits** only.

Good candidates:

- starts with first principles or with examples
- uses analogy heavily or sparsely
- sounds clipped, calm, combative, ironic, or expansive
- repeats certain distinctions
- avoids certain types of vague language

This section should help the final skill sound structurally right, not theatrically imitative.

### 4. Anti-patterns

List what this target consistently rejects.

Examples:

- empty abstraction
- fashionable consensus without evidence
- overconfidence under uncertainty
- moralizing instead of analysis
- complexity without prioritization

### 5. Honest boundaries

State clearly:

- the knowledge cutoff or research date for the skill
- which judgments are inference rather than explicit position
- where evidence is thin
- what this skill cannot reproduce

## Output

Write a compact perspective skill with this structure.

```md
---
name: [person-name]-perspective
description: |
  [Person] perspective skill based on writings, interviews, decisions, and selective external analysis. Distills core mental models, decision heuristics, expression DNA, anti-patterns, and honest boundaries.
  Best for: [use]
  Research date: [YYYY-MM-DD]
---

# [Person] Perspective

## Scope
A compact analytical reconstruction of [Person]'s way of thinking. Useful for judgment, explanation, and framing. Not a full simulation of the person.

## Operating rules
- prefer substance over quotation
- where facts matter, gather enough facts first
- where uncertainty remains, say so
- do not fake certainty or private intent

## Response workflow
### Step 1: classify the request
- fact-heavy
- framework-heavy
- mixed

### Step 2: do minimal targeted research if needed
Prioritize:
- [dimension 1]
- [dimension 2]
- [dimension 3]

### Step 3: answer in this order
1. conclusion
2. reasoning
3. biggest risk or blind spot
4. boundary note

## Core mental models
### 1. [Model]
One-line description:
Signals:
- 
- 
Best used for:
Boundary:

### 2. [Model]
...

### 3. [Model]
...

## Decision heuristics
- 
- 
- 
- 
- 

## Expression DNA
- 
- 
- 

## Anti-patterns
- 
- 
- 

## Honest boundaries
- 
- 
- 
- 

## Key sources
### First-hand
- 
- 

### Second-hand
- 
- 
```

## Response behavior

When invoked, this skill should:

1. identify whether the target is a person or a bounded topic
2. collect only enough evidence to stabilize the pattern
3. distill the 3 + 5 + DNA + boundaries structure
4. output the finished perspective skill in a compact, directly usable form
5. explicitly downgrade when evidence is weak

## Update mode

If the user asks to update an existing skill:

1. read the existing skill first
2. collect only the most recent or most corrective material
3. check whether new evidence:
   - strengthens old models
   - corrects old models
   - adds a truly new heuristic
4. update selectively instead of rewriting everything

## Failure handling

### Thin evidence
If there are fewer than 5 strong sources:

- reduce to 2 mental models
- mark low confidence clearly
- recommend that the user provide first-hand material

### Overbroad target
If the target is too broad:

- narrow it first
- or convert the task into a bounded topic framework instead of a person skill

### Weak voice signal
If the expression pattern is weak:

- avoid style mimicry
- keep only structural judgment habits

## Quality bar

The final skill should be:

- compact enough to use immediately
- distinct enough to feel like this target
- honest enough to show its limits
- strong enough to guide actual analysis

## Final principle

Prefer a smaller skill that is accurate and usable over a grand skill that is bloated and half-fictional.