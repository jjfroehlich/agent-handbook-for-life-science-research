# Specialized Figures

Use this for heatmaps, networks, genomic or temporal tracks, set intersections, dense matrices, multidimensional views, and 3D plots.

## Use this when...

- The figure is too dense for ordinary plot-selection advice.
- The data have meaningful ordering, clustering, connectivity, genomic coordinates, set membership, time, or spatial dimensions.
- The user asks whether a specialized display is interpretable rather than merely impressive.

## The job of this topic

Expose the scientific structure without letting algorithmic defaults, arbitrary ordering, or visual density manufacture a pattern.

## Default workflow

1. Name the specialized structure: matrix, network, track, set intersection, time series, spatial/3D, or multidimensional projection.
2. Identify the reader task: find clusters, compare groups, locate features, follow change, inspect intersections, or understand connectivity.
3. Check whether ordering, scaling, filtering, aggregation, or faceting is doing the main interpretive work.
4. Demand labels, legends, and method notes for transformations, clustering, clipping, missing values, and thresholds.
5. Reduce complexity before polishing the graphic.
6. Inspect the actual figure before claiming that exact layout, palette, or visual pattern is successful.

## Decision rules

- Heatmaps: check color scale, range clipping, missing-value encoding, row/column order, clustering method, annotations, and legend before interpreting blocks.
- Networks: use node-link diagrams for small readable networks; use adjacency matrices, aggregation, filtering, or facets for dense networks.
- Genomic displays: preserve coordinate order, use overview plus detail when scale changes, and label tracks and feature types clearly.
- Set intersections: use matrix/UpSet-style displays when more than a few sets make Venn diagrams unreadable.
- Temporal data: preserve time order and avoid arbitrary sorting that hides sequence.
- 3D displays: use only when depth is part of the scientific structure and can be read reliably.

## Variants and edge cases

- Multidimensional projections can suggest clusters; pair them with explanation of what was reduced or lost.
- Genome browsers and track stacks may need both a high-level locator and a zoomed panel.
- Clustered heatmaps need the clustering distance, linkage, and scale context when those choices affect the conclusion.
- Dense networks often need a question-specific subnetwork rather than a complete hairball.

## Anti-patterns

- Interpreting heatmap clusters without knowing scaling and ordering.
- Using diverging palettes without a meaningful reference. All-positive ratios can still have a substantive midpoint at one.
- Treating network layout proximity as evidence when layout is algorithmic.
- Using Venn diagrams for too many sets.
- Adding 3D effects for decoration.

## Diagnostic questions

- Which transformation, order, or filter creates the visible pattern?
- Is the ordering meaningful, clustered, or arbitrary?
- Are missing values, clipping, thresholds, and normalization visible?
- Would a matrix, table, facet, or zoomed detail reveal the structure better?
- Does the specialized display still answer one clear scientific question?

## Output patterns / mini-templates

```text
Specialized structure: <heatmap/network/genome/set/time/3D>.
Interpretation risk: <ordering/scaling/filtering/density issue>.
Required disclosure: <method or legend detail>.
Better display: <matrix/facet/filter/overview-detail/table>.
Visual inspection needed: <exact pattern/palette/layout claim>.
```

## Examples

- `Clustered heatmap`: check whether rows and columns were clustered, what distance was used, and whether color limits hide extreme values.
- `Network hairball`: filter to the claim-relevant subnetwork or switch to an adjacency matrix.

## When not to apply this

Do not route ordinary group comparisons here unless the figure is genuinely dense or specialized.
