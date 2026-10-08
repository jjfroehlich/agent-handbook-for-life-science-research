# Statistics And Uncertainty

Use this when a figure must show variability, sample size, independent units, repeated experiments, p-values, intervals, effect sizes, model uncertainty, overplotting, or outliers.

## Use this when...

- The user asks whether a statistical display is honest or publication-ready.
- The figure uses bars, stars, p-values, error bars, violins, box plots, or pooled observations.
- The interpretation depends on biological replicates, technical replicates, donor/sample structure, or repeated measurements.

## The job of this topic

Make the visual claim proportional to the evidence. Readers should see magnitude, uncertainty, spread, data support, and replication structure without mistaking statistical significance for practical or biological importance.

## Default workflow

1. Ask what each mark represents: biological replicate, technical replicate, cell, animal, patient, experiment, model estimate, or summary.
2. Identify the independent unit for inference before recommending a plot.
3. Separate raw observations, summaries, and model estimates.
4. Show distribution shape when it affects interpretation and sample size supports it.
5. Pair effect claims with effect size and compatible uncertainty interval.
6. Explain error bars and interval type in the caption or legend.
7. Treat p-values as secondary evidence, not the visual headline.

## Decision rules

- If `n` is small, show individual observations and avoid smooth density displays.
- If observations are paired or repeated, show the pairing or within-unit difference.
- If observations are nested, show the hierarchy and identify the unit assigned or sampled independently for the intended inference. A replicate summary or an appropriate hierarchical estimate can accompany lower-level points. Cells are not automatically independent replicates; individually assigned cells can be units in a different design.
- If the claim is an effect, show the direct contrast with its compatible uncertainty interval. Group-summary intervals describe their own estimates; their overlap alone does not establish uncertainty in the difference.
- If the claim is distributional, show shape, spread, and outliers.
- If data are overplotted, use jitter, transparency, binning, density, small multiples, or summary overlays.
- If outliers are omitted or axes are truncated, state the rule and show enough context to prevent a misleading read.

## Variants and edge cases

- Single-cell or high-throughput data: show cell-level pattern only alongside donor/sample structure when generalization depends on donors or samples.
- Violin plots: use only when enough observations support a density estimate; otherwise use points, box plots, or interval summaries.
- Model-based estimates: label the model estimate, uncertainty type, and prediction or confidence target.
- Multiple comparisons: avoid visual emphasis that makes a single p-value dominate the whole figure.

## Anti-patterns

- Stars without effect size.
- SEM bars used as if they show biological spread.
- Pooled cell counts hiding donor count.
- Tiny samples displayed as smooth distributions.
- Cropped axes, hidden outliers, or unreported transformations that exaggerate differences.

## Diagnostic questions

- What is the independent unit?
- What does each point, line, bar, or interval represent?
- Is the reader supposed to judge magnitude, variability, reliability, or all three?
- Could the same p-value support a very different biological effect?
- Are exploratory patterns visually separated from confirmatory claims?

## Output patterns / mini-templates

```text
Evidence unit: <independent unit>.
Current risk: <pooled/hidden/overstated feature>.
Display fix: <raw/summary/model display>.
Uncertainty: <interval/error bar type>.
Caption must state: <n, replicate unit, transformation, outlier rule>.
```

## Examples

- `n=4 violin`: show all four points. A median and observed range can describe them; an uncertainty interval needs a stated estimator and method. A smooth violin can imply unsupported distribution shape.
- `p < 0.05 bar figure`: show effect size and interval, show observations if possible, and make the conclusion about magnitude.
- `many cells from three donors`: show cell distribution and donor-level summaries so the reader does not confuse cell count with independent `n`.

## When not to apply this

Do not provide full statistical-methods consulting unless asked. Keep the answer on how evidence and uncertainty should be displayed.
