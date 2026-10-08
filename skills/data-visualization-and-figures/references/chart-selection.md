# Chart Selection

Use this when the user asks what plot, table, or visual form to use, or when a proposed figure may not fit the data or reader task.

## Use this when...

- The user is choosing between bars, dots, lines, box plots, violin plots, histograms, scatter plots, tables, matrices, or small multiples.
- The current figure may hide raw observations, spread, sample size, pairing, or exact lookup needs.
- The figure uses a default chart and the scientific task is not yet clear.

## The job of this topic

Choose the simplest honest display that lets the reader do the scientific job: compare groups, inspect distributions, see relationships, follow change, judge composition, inspect exact values, or recognize a raw data pattern.

## Default workflow

1. State the figure job in one sentence.
2. Identify the data structure: categorical, continuous, paired, nested, time series, matrix, spatial, network, hierarchy, or exact lookup.
3. Decide whether the reader needs raw observations, uncertainty, sample size, distribution shape, or exact values.
4. Choose position/length encodings before area, angle, volume, color-only, or decorative shapes.
5. If the display is dense, facet, aggregate, bin, sort, or use a table/matrix instead of crowding one panel.
6. Name what the recommended display reveals and what it still hides.

## Decision rules

- Amounts or counts: bars or dots can support comparison. For continuous measurements, show observations or distributions when their spread, sample size or pairing affects the claim; summary points and intervals can accompany them.
- Continuous distributions: use dot/strip, box, violin, histogram, density, empirical cumulative, or ridgeline forms according to sample size and task.
- Small samples: show the individual observations; avoid smooth density shapes that imply unsupported information.
- Paired, repeated, or nested observations: connect pairs, show within-unit differences, group points by replicate, or facet by independent unit.
- Relationships: use scatter, line, residual, or binned displays with clear scales and uncertainty where needed.
- Composition: use stacked bars for part-to-whole comparisons; internal segments lack a common baseline. Grouped bars can compare amounts across factors without implying composition. Prefer aligned lengths or positions to pies for precise comparisons.
- Exact lookup: use a table or annotated matrix rather than forcing a plot.
- Multiple categories: sort, group, or facet before adding many colors or symbols.

## Variants and edge cases

- A table is better when exact values, many attributes, units, or lookup are the job.
- A plot is better when pattern, trend, rank, distribution, or relative magnitude is the job.
- If both exact values and patterns matter, use a small table plus a plot or a table with restrained visual cues.
- Do not use the same plot type for exploratory and publication figures without checking whether the final reader task changed.

## Anti-patterns

- Mean-only bars or lines for continuous small-n data.
- Summary statistics shown as if they prove the visual pattern.
- Pie or area encodings for small quantitative differences.
- Default chart choice with no stated reader task.
- Long legends created because too many categories were forced into one panel.

## Diagnostic questions

- What should the reader compare first?
- Does the figure need exact values or pattern perception?
- Are observations, uncertainty, sample size, and outliers visible enough?
- Are categories ordered by the task or by accident?
- Would a table, matrix, facet, or supplement serve the job better?

## Output patterns / mini-templates

```text
Current form: <chart/table>.
Figure job: <comparison/distribution/relationship/etc.>.
Main risk: <hidden or misleading feature>.
Recommended form: <specific display>.
Why: <data property and reader task>.
Caveat: <context still needed>.
```

## Examples

- `n=4 per group with bars`: show all four points per group and add a compatible summary interval if useful.
- `Pooled repeated measures`: connect paired observations or show independent-unit summaries instead of treating every point as independent.
- `Large exact results table`: keep the table for lookup, but sort rows by the comparison and move secondary columns to supplement.

## When not to apply this

Do not use this as a plotting-code guide. If the user only asks for syntax, answer the code question and offer design review separately.
