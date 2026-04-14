# Examples

## 1. Named person

Request:

```text
/persona-distill-lite Charlie Munger
```

Expected behavior:

- identify the target as a named person
- gather a bounded set of strong first-hand and high-quality secondary sources
- extract 3 core mental models
- extract 5 decision heuristics
- describe expression DNA without caricature
- generate a compact `charlie-munger-perspective` skill

## 2. User-provided materials first

Request:

```text
/persona-distill-lite Peter Thiel
Use only the interview transcripts and notes I uploaded.
```

Expected behavior:

- avoid outside expansion
- use the uploaded material as the dominant evidence base
- note where evidence is thin
- generate a smaller but honest perspective skill

## 3. Update mode

Request:

```text
/persona-distill-lite update Nassim Taleb
```

Expected behavior:

- read the existing Taleb skill first
- collect only newer or corrective material
- update selected models, heuristics, and source notes
- avoid rewriting the whole file unless the old version is structurally wrong

## 4. Topic instead of person

Request:

```text
/persona-distill-lite product minimalism
```

Expected behavior:

- treat the target as a bounded topic framework rather than a person simulation
- narrow the scope if necessary
- extract recurring principles, tradeoffs, and anti-patterns
- output a compact framework skill rather than a persona skill

## 5. Thin-evidence case

Request:

```text
/persona-distill-lite obscure founder X
```

Expected behavior:

- detect weak evidence
- shrink the output to 2 mental models if needed
- make confidence limits explicit
- ask for first-hand material only if doing so would materially improve the result

## 6. Writing support angle

Request:

```text
/persona-distill-lite Joan Didion
I want a writing advisor, not full role-play.
```

Expected behavior:

- prioritize judgment structure, sentence discipline, and observational habits
- avoid theatrical imitation
- produce a skill that is useful for editing and framing rather than cosplay

## 7. Decision support angle

Request:

```text
/persona-distill-lite Munger
I want a decision advisor for business and investing.
```

Expected behavior:

- emphasize core models and heuristics over voice
- build response workflow around fact gathering, tradeoff inspection, incentives, and downside analysis
- keep the final skill compact and operational