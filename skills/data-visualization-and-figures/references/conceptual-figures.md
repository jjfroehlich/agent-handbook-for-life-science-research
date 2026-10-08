# Conceptual Figures

Use this for graphical abstracts, overview figures, mechanism diagrams, pathway schematics, process diagrams, conceptual models, neural-circuit diagrams, and arrow-heavy explanatory figures.

## Use this when...

- The figure explains an idea, process, model, mechanism, or story rather than plotting raw measurements.
- The user wants a graphical abstract or overview that is clear to readers outside the immediate specialty.
- The schematic is overloaded, decorative, or unclear about what arrows and symbols mean.

## The job of this topic

Compress a scientific idea into a readable visual argument without pretending the schematic is raw evidence.

## Default workflow

1. Write the one sentence the reader should remember.
2. List essential entities, relationships, and sequence steps.
3. Remove secondary details or move them to labels, caption, or supplement.
4. Choose visual grammar from relationship type.
5. Keep arrow, line, color, and container meanings consistent.
6. Distinguish evidence, model, hypothesis, and speculation when uncertainty matters.
7. Inspect the actual figure before making exact layout or composition claims.

## Decision rules

- Sequence: use ordered flow.
- Repeating process: use a cycle.
- Hierarchy or compartment: use nested containers or grouped regions.
- Comparison: use side-by-side parallel structure.
- Direction, movement, transformation, sequence, or causality: use arrows as verbs.
- Association, grouping, or structural connection: use lines without arrowheads.
- Pathways and circuits: preserve direction, connectivity, and convention enough for the intended audience.
- Graphical abstracts: emphasize the finding or, for a methods contribution, the distinctive operation and capability it enables.

## Variants and edge cases

- Overview figure: orient the reader in the system; do not include every result.
- Mechanism model: label speculative steps as model or hypothesis.
- Pathway diagram: break into modules when edge crossings dominate.
- Broad-audience visual abstract: reduce jargon and make the primary relation visually obvious.

## Anti-patterns

- Decorative icons that encode no relationship.
- Many arrows with inconsistent meanings.
- Unlabeled symbols that require insider knowledge.
- Mixing raw data panels and speculative model elements without visual separation.
- Graphical abstracts that try to summarize every experiment.

## Diagnostic questions

- What sentence should the reader remember?
- Which arrow or relationship is most important?
- Can any element be removed without changing the message?
- Are observations, evidence, and hypotheses visually distinct?
- Would the figure still work if the caption were read after the visual scan?

## Output patterns / mini-templates

```text
Message: <one sentence>.
Keep: <essential entities and relationships>.
Remove: <secondary elements>.
Visual grammar: <sequence/cycle/containers/arrows/labels/color>.
Caveat: <known vs proposed or exact visual detail requiring inspection>.
```

## Examples

- `Overloaded graphical abstract`: collapse methods into one context cue and devote the center to the discovery or mechanism.
- `Pathway schematic with many crossings`: group steps into modules and reroute connections while retaining essential branches and feedback. A numbered flow can explain a sequence, but cannot substitute for causal edges. Disclose consequential simplification.

## When not to apply this

Do not use this for statistical plot selection unless the user is converting results into a conceptual summary.
