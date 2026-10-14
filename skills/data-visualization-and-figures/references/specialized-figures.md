# Choose a specialized view by its task

Read this for matrices, networks, genomic views, intersections, maps or multidimensional displays. Identify which ordering, transformation, filter or layout creates the visible pattern before interpreting it.

## Heatmaps: magnitude, pattern or comparison to a reference?

Name the quantity, units, transformation, limits, clipping and missing-value appearance. Explain row/column ordering and relevant clustering distance/linkage. A clustered arrangement is an analysis choice, not independent evidence of biological groups. Standardization changes the comparison: within-row relative patterns do not preserve between-row absolute magnitude. A positive ratio can have a meaningful reference at 1; concentration usually has an ordered magnitude scale. Consult `color-and-accessibility.md` before choosing the palette.

Keep common mappings for absolute comparisons across panels. Separate mappings can reveal local structure but require explicit ranges and relinquish direct color-to-color magnitude comparison. Distinguish zero, missing, unmeasured and censored values. A matrix of exact values may need numeric labels or an accompanying table; color is better for broad pattern than precise lookup.

## Networks: paths and edges are different questions

Node-link geometry helps trace neighbors and indirect routes. An ordered adjacency matrix can make dense direct-edge lookup or blocks clearer but is poor for tracing multistep paths. For directed data, explicitly state whether rows are sources and columns targets, and retain that convention throughout. Do not mirror a directed matrix as though it were undirected.

Explain edge meaning, direction, weights and absence. An absent record, an untested relationship and a measured zero need not mean the same thing. Layout proximity and apparent clusters are not extra measurements or causal proof. Disclose filtering and aggregation; weak edges may be scientifically important. A question-specific subnetwork can help if the omitted context remains recoverable. Embed measurements inside nodes only when the profiles and connectivity both remain readable. Quantitative flow diagrams need defined flows, not merely relationships.

Changed condition: direct connectivity lookup in a dense network favors a matrix; tracing a biochemical route may favor a small node-link view. Density alone does not select one universal winner.

## Genomic coordinates versus functional relationships

Keep coordinate order, track identities and relevant assembly/units recoverable. Pair an overview with detail when binning hides local features. Mark removed distances or rescaled intervals. Feature-aligned stacks reveal local patterns while discarding genomic arrangement; spatially adjacent cells in a space-filling curve can represent distant loci. Overlaid tracks can occlude values or mix colors, while a heatmap sacrifices precise magnitude reading.

Arcs can locate breakpoints without conveying full variant order or orientation. Sequence graphs can clarify rearranged connections while giving up physical distance. Inferred states and average tracks are computed summaries; keep primary variation accessible when it matters. Do not present a prospective visualization idea as an established measurement method.

## Intersections and hierarchies

State the population and whether an intersection count is exclusive to a combination or inclusive of additional sets. Simple Venn/Euler forms can serve a few easily read relations; a matrix/intersection-bar view can handle more combinations but still needs explicit counting semantics. Visual area is not quantitative unless the construction makes it so. Supplied hierarchy, inferred clustering and overlapping membership are distinct structures; describe the method when the tree is inferred.

## Multiple dimensions, space and geography

Use a scatterplot matrix or facets when the reader needs recoverable pairwise relations. PCA displays variance along linear components under the chosen centering/scaling; show explained variance and meaningful loadings where needed. Two dimensions omit variation, and separated groups in a projection do not automatically establish discrete biological classes. Parallel coordinates depend strongly on axis order and scaling.

PCA scores locate observations; loadings describe variable contributions. A variable poorly represented on the retained components cannot be interpreted reliably from its apparent two-dimensional relationship alone. Do not treat a projection's geometry as the full original distance structure.

A correlation matrix summarizes selected associations and cannot replace inspection of the bivariate patterns. Zero Pearson correlation does not exclude a strong nonlinear relationship.

Reserve 3D for genuine spatial/depth relationships that can be read through the chosen view; occlusion and projection can hide structure. Multiple views, slices or interaction can help, while perspective bars distort ordinary magnitude comparisons. A map is useful when geography matters; large regions can dominate attention. Distinguish counts from rates and choose projection/area treatment for the question. Aligned plots may compare values more precisely when location is secondary.

For warranted 3D, keep projected labels readable and inspect whether transparency obscures surfaces or creates misleading apparent intersections. Transparency is an option, not a general solution to occlusion.

Choropleths retain geography but give large regions more area; cartograms encode a quantity through area while distorting familiar shapes, and tile maps equalize visual units while sacrificing geographic precision. Choose according to the comparison. An inset can relocate a region without changing its scale or can rescale it; label which occurred rather than implying unchanged spatial relationships.

## Time and dense trajectories

Preserve actual time spacing and explain missing intervals, aggregation and phase alignment. A line implies a connection; distinguish observations, interpolation, fitted values and forecasts. For dense series, selected detail, facets or summaries with defined spread/uncertainty can help. Sparklines suit qualitative overview, not exact reading without scale context. Animation can show change but makes across-time comparison depend on memory; small multiples often make that comparison easier. Smooth transitions can imply temporal continuity that the data do not contain.
