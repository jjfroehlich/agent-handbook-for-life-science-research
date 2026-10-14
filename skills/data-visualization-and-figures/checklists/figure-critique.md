# Figure Critique Checklist

Use this for a fast but rigorous review of a scientific figure.

## Triage

- Main claim: what should the reader learn?
- Figure job: comparison, distribution, relationship, composition, process/overview, exact lookup, image evidence, or publication export?
- Evidence unit: what does each point, image, panel, line, or summary represent?
- Target medium: manuscript, slide, poster, preprint, grant, report, or web?
- Missing context: what would change the recommendation?

## Checks

- Form fits task: the chart, table, image panel, schematic, or matrix matches the data and reader job.
- Raw evidence is visible when needed: observations, sample size, spread, outliers, uncertainty, and replicate structure are not hidden.
- Encoding is honest: axes, scales, baselines, transformations, clustering, color maps, and summaries do not exaggerate or conceal.
- Statistical context is clear: effect sizes, intervals, p-values, and independent units are labeled appropriately.
- Group comparison is readable: show a named center as well as observations when needed; adapt box/density layers to each group's support and label unequal `n`.
- Identification is accessible: important distinctions remain interpretable under the intended viewing conditions; inspect relevant color-vision simulations and grayscale when required.
- Restraint is deliberate: position/labels may already identify groups; extra dashes, shapes and saturated fills need a reason. Preserve settled specifications.
- Image context is present: scale, channels, insets, annotations, sample context, and analysis workflow are clear where relevant.
- Layout guides reading: panel order, alignment, grouping, labels, legends, and whitespace support the argument.
- Final size works: text, symbols, line weights, image details, and annotations remain legible.

## High-risk failure modes

- Bars hide continuous small-n data.
- A p-value or star annotation replaces effect size and uncertainty.
- A heatmap uses a diverging palette without a meaningful midpoint.
- Microscopy panels lack scale bars, channel explanations, or inset location markers.
- A network, pathway, or graphical abstract uses layout decoration as if it were evidence.
- Legends require too much memorization.
- The figure tries to support several unrelated messages.

## Response template

```text
Main job: <what the figure must let readers do>
Top priority: <problem -> fix -> rationale>
Second priority: <problem -> fix -> rationale>
Accessibility/readability check: <color, labels, final size>
Missing or unverified context: <details that would change the recommendation>
```
