# Figure Review Examples

These fictional cases show how to turn a description into useful advice. No image was supplied; visual appearance remains uninspected.

## Weak feedback

```text
This plot is cluttered. Use nicer colors and make the labels bigger.
```

Why it fails: it gives taste-level advice without naming the data task, the misleading element, or the specific revision.

## Completed critique: paired cultures

Input: Four independently grown cultures were each split into vehicle and treatment aliquots. Six cells were measured per aliquot. A mean-only bar chart pools the cells and labels each condition `n=24`. The question is whether treatment changes the response across cultures.

Response: The chart hides the four matched comparisons and makes 24 cells look like 24 independent treatment replicates. Show the cell observations grouped by culture, with each culture's vehicle and treatment summaries connected. Add a separate display of the four within-culture differences if treatment magnitude is the main claim. Any interval on the overall contrast must respect the paired design and identify its method; cell-level spread is a different quantity.

The legend should state four independent cultures, six cells per aliquot, the split-culture pairing, the summary and any interval definition. These changes expose whether the effect is consistent across cultures. I would inspect the assembled figure at final width before judging whether the cell layer or connecting lines obscure one another.

Why it works: the redesign follows the supplied assignment and inference target, preserves both measurement levels and distinguishes variability from uncertainty of the contrast.

## Completed critique: a positive ratio heatmap

Input: A heatmap contains treated/control ratios from 0.5 to 2.0. White is assigned to ratio 1, and blue and red denote lower and higher responses. Samples are clustered, but the intended task is to compare treatment groups.

Response: A diverging palette is appropriate in principle: one is a meaningful no-change reference even though every value is positive. Label the ratio scale and reference explicitly. Decide whether equal fold changes should receive equivalent color departures; if using log ratios, identify that transformation. The current description does not establish whether the actual shades or small cells are readable.

For the treatment comparison, retain visible group annotations or arrange samples by treatment. Keep clustering when similarity is itself the question, and disclose its scale, distance and method. Do not interpret a colored block as an independent biological result without checking those choices. If readers need exact ratios, provide printed values or a table alongside the pattern display.

## Common transformations

- Mean-only bar chart with continuous small-n data -> observations, an appropriate descriptive summary, and a direct-contrast interval when the claim needs it.
- P-value-focused result -> effect estimate plus uncertainty interval, with p-value secondary.
- Red/green fluorescence merge -> accessible channel colors, single-channel panels if needed, and explicit channel legend.
- Dense multi-panel figure -> one reading order, aligned panels, direct labels, and secondary material moved to caption or supplement.
- Heatmap with arbitrary diverging palette -> palette chosen from data semantics and a labeled color scale.
- Network hairball -> filtered subnetwork, adjacency matrix, grouped layout, or supplemental interactive view.

## Bad assistant traps

- Giving plotting-code advice when the user asked for design critique.
- Saying "make it cleaner" without specifying what to remove.
- Treating accessibility as optional polish.
- Inferring image scale, channel identity, replicate structure, exact palette performance, or layout quality without the actual figure.
- Guessing venue specifications instead of stating assumptions and required checks.
