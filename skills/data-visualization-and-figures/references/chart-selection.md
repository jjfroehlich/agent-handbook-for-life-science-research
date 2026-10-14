# Choose a display for the comparison

Read this when the chart family or reader task is unresolved. Begin with the operation: compare amounts, judge a distribution, follow change, inspect a relationship, understand composition or look up exact values. Identify the data structure and what one mark represents. Then compare plausible designs on the same data.

If the task needs one value rather than a relationship, a contextualized number can be sufficient. Include its units, population and denominator where applicable. A chart becomes useful when readers need a comparison, distribution or trend; do not remove those relationships merely to produce a striking number.

## Match the operation

| Reader task | Useful candidates | What to watch |
|---|---|---|
| Compare amounts or counts | Aligned dots or bars | Length bars need an honest baseline; position plots have different constraints. |
| Compare continuous groups | Points, boxplots, violins, estimate/interval displays | Center, shape, sample size and uncertainty are different information. Choose layers deliberately. |
| Follow time or another ordered coordinate | Lines, points, small multiples | Preserve actual spacing; connections must have meaning. |
| Inspect association | Scatterplot, binned counts/density, residual display | Overlap can hide frequency; correlation and layout do not establish causality. |
| Compare shares or totals | Aligned bars, stacks, a simple pie, hierarchy display | Denominators and additive quantities matter; internal stack segments lack common baselines. |
| Retrieve exact values | Table, annotated matrix | Keep units, precision and row tracking readable. |

Aligned position and length usually support more precise magnitude comparisons than area, angle or volume. That does not make every other encoding invalid: a few broad shares can work in a simple pie, and spatial structure can justify a map. Scale circle size by area when area represents amount. Do not add depth merely to decorate quantities.

## Continuous data need more than a mean-only bar

The same mean and spread can conceal different distributions, pairings or clusters. Show those features when they change the interpretation. A useful starting candidate for group distributions combines a light violin, a narrow box and visible observations. Decide each layer's contribution, rather than always drawing three layers or always reducing to dots. A tiny group can retain its points and a descriptive center while a larger group retains density and quartiles. For large groups, a readable summary/distribution may be preferable to every point. Consult `statistics-and-uncertainty.md` for units, weighting and interval meaning.

Histograms expose counts and depend on bin boundaries and widths. Density curves depend on smoothing. Unequal-width histograms require correct area normalization; height alone otherwise misrepresents counts. Avoid opaque overlapping distributions when separate panels or outlines make comparison easier. Ridgelines can expose shifts or modes across many ordered groups, at the cost of exact density comparison and potential overlap.

An empirical cumulative distribution is useful for fractions below a threshold or quantiles without choosing bins. It may need explanation for unfamiliar readers. A Q–Q plot compares quantiles against a stated reference distribution or another sample; specify reference parameters and line convention. Agreement is diagnostic, not proof of a generating model. Apparent straight tails on log–log axes do not prove a power law.

## Preserve the question while simplifying

Sorting can reveal rank when categories have no meaningful order. Retain time, dose, anatomical or other substantive order. Faceting can reduce overlap, but consumes space and makes some within-panel comparisons harder. Aggregation can clarify a trend while concealing unusual observations; name what was aggregated and keep important detail recoverable. Do not silently discard outliers or weak network edges for a cleaner picture.

For compositions, distinguish totals, component amounts and fractions. Stacks require additive parts; medians or uncertain group means do not automatically form a meaningful whole. Proportion curves conceal changing totals, and equal-area densities conceal prevalence. State the denominator. Mosaics cross-classify groups; treemaps show nesting. Overlapping membership is not a partition. Nested rings can double-count categories, and crossing ribbons can obscure transitions. Prefer simple aligned displays when hierarchy itself is not the question.

Word clouds give longer words more visual area as well as encoding frequency through size. Circular bars add radial geometry to length judgments. If precise rank or magnitude matters, aligned bars or lollipops avoid these extra influences; decorative variety alone does not justify them.

## Exploration and explanation have different jobs

Explore several views when searching for structure. For the final figure, choose the view that supports the stated comparison and retain evidence that could change the conclusion. A compelling sequence is not evidence of mechanism. An overall comparison and a comparison conditional on a subgroup can answer different questions; do not switch silently between them.

Changed condition: exact values across many attributes favor a table. If the reader instead needs to see a dose response, a plot can make the relationship apparent; a compact table can remain available for lookup. Explain the consequential choice and its tradeoff without forcing a full design report into a small request.
