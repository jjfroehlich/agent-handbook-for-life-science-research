<a id="quarto-document-content"></a> 

<a id="title-block-header"></a>

<a id="display-chapter"></a>

# Choosing a figure or table

<a id="display-comparison"></a>Choose a display for the comparison you want to make. Try alternatives while exploring the data: a pattern hidden by a group average may become visible when you plot the individual observations. [[4]](#ref-display-shoresh2012).

<a id="display-choice"></a>

## Visual glossary

<a id="display-glossary"></a>

**<a id="display-categories"></a>Amounts**

<table>
<colgroup>
<col>
<col>
<col>
</colgroup>
<tbody>
<tr>
<td><img alt="Horizontal bars with a shared baseline." src="../../assets/images/icon-bars.svg"> <span id="display-bars">Bars</span></td>
<td><img alt="Dots aligned on a common numerical axis." src="../../assets/images/icon-aligned-dots.svg"> <span id="display-dots">Dot plot</span></td>
<td><img alt="Pairs of bars grouped by category." src="../../assets/images/icon-grouped-bars.svg"> <span id="display-grouped-bars">Grouped bars</span></td>
</tr>
</tbody>
</table>

**<a id="display-distributions"></a>Distributions**

<table>
<colgroup>
<col>
<col>
<col>
</colgroup>
<tbody>
<tr>
<td><img alt="Individual observations offset to avoid overlap." src="../../assets/images/icon-points.svg"> <span id="display-points">Individual points</span></td>
<td><img alt="Adjacent bars representing counts in numerical intervals." src="../../assets/images/icon-histogram.svg"> <span id="display-histogram">Histogram</span></td>
<td><img alt="Smooth curve representing a distribution." src="../../assets/images/icon-density.svg"> <span id="display-density">Density</span></td>
</tr>
</tbody>
</table>

**Distribution summaries**

<table>
<colgroup>
<col>
<col>
<col>
</colgroup>
<tbody>
<tr>
<td><img alt="Box, median and whiskers summarizing a distribution." src="../../assets/images/icon-boxplot.svg"> <span id="display-boxplot">Boxplot</span></td>
<td><img alt="Mirrored density with width varying along the numerical axis." src="../../assets/images/icon-violin.svg"> <span id="display-violin">Violin</span></td>
<td><img alt="Monotonically rising cumulative step curve." src="../../assets/images/icon-ecdf.svg"> <span id="display-ecdf">Cumulative distribution (ECDF)</span></td>
</tr>
</tbody>
</table>

**<a id="display-matching"></a>Matching**

<table>
<colgroup>
<col>
</colgroup>
<tbody>
<tr>
<td><img alt="Lines connect corresponding observations in two conditions." src="../../assets/images/icon-connected-points.svg"> <span id="display-connected-points">Connected points</span></td>
</tr>
</tbody>
</table>

**<a id="display-relationships"></a>Relationships**

<table>
<colgroup>
<col>
<col>
<col>
</colgroup>
<tbody>
<tr>
<td><img alt="Points positioned by two numerical variables." src="../../assets/images/icon-scatterplot.svg"> <span id="display-scatter"><span id="display-paired">Scatterplot</span></span></td>
<td><img alt="Hexagonal bins colored by count." src="../../assets/images/icon-hexbin.svg"> <span id="display-hexbin">Hexbin</span></td>
<td><img alt="Scatterplot with circle area encoding another variable." src="../../assets/images/icon-bubble.svg"> <span id="display-bubble">Bubble plot</span></td>
</tr>
</tbody>
</table>

**<a id="display-time"></a>Time or dose**

<table>
<colgroup>
<col>
<col>
</colgroup>
<tbody>
<tr>
<td><img alt="Observed values joined in progression along an axis." src="../../assets/images/icon-line-plot.svg"> <span id="display-lines">Time-course lines</span></td>
<td><img alt="Three vertically aligned line panels." src="../../assets/images/icon-small-multiples.svg"> <span id="display-small-multiples">Small multiples</span></td>
</tr>
</tbody>
</table>

**<a id="display-composition"></a><a id="display-pie"></a>Composition**

<table>
<colgroup>
<col>
<col>
</colgroup>
<tbody>
<tr>
<td><img alt="Segmented bars with unequal totals." src="../../assets/images/icon-stacked-bars.svg"> <span id="display-stacked">Stacked bars</span></td>
<td><img alt="Equal-length bars subdivided into proportions." src="../../assets/images/icon-proportional-stacks.svg"> <span id="display-proportions">Proportional stacked bars</span></td>
</tr>
</tbody>
</table>

**<a id="display-matrix-lookup"></a>Matrices, networks and sets**

<table>
<colgroup>
<col>
<col>
<col>
</colgroup>
<tbody>
<tr>
<td><img alt="Matrix cells shaded by numerical value." src="../../assets/images/icon-heatmap.svg"> <span id="display-heatmap">Heatmap</span></td>
<td><img alt="Nodes connected by edges." src="../../assets/images/icon-network.svg"> <span id="display-network">Network</span></td>
<td><img alt="Two overlapping circles representing sets." src="../../assets/images/icon-venn.svg"> <span id="display-venn">Venn diagram</span></td>
</tr>
</tbody>
</table>

**Sets and genome positions**

<table>
<colgroup>
<col>
<col>
</colgroup>
<tbody>
<tr>
<td><img alt="Intersection bars aligned above a set-membership dot matrix, with set-size bars at left." src="../../assets/images/icon-upset.svg"> <span id="display-upset">UpSet</span></td>
<td><img alt="Aligned signal and feature tracks along a shared genomic coordinate." src="../../assets/images/icon-genomic-tracks.svg"> <span id="display-genomic-tracks">Genomic tracks</span></td>
</tr>
</tbody>
</table>

**Exact values**

<table>
<colgroup>
<col>
</colgroup>
<tbody>
<tr>
<td><img alt="Values arranged in labeled rows and columns." src="../../assets/images/icon-table.svg"> <span id="display-table-icon"><span id="display-tables"><span id="display-table-example">Table</span></span></span></td>
</tr>
</tbody>
</table>

<a id="display-decision-table"></a>

## Choose and compare displays

<table>
<thead>
<tr>
<th>Reader’s task</th>
<th>Useful starting choice and qualification</th>
</tr>
</thead>
<tbody>
<tr>
<td>Compare amounts</td>
<td><strong>Dots or bars</strong> make positions or lengths easy to compare. Bars need a zero baseline. If differences among observations matter to the question, show them alongside the group means.</td>
</tr>
<tr>
<td>Inspect distributions</td>
<td>Use <strong>individual points</strong> to retain observations, a <strong>histogram</strong> for counts in intervals, or an <strong>ECDF</strong> for the fraction at or below each value. Boxplots summarize the median and middle half; density curves and violins smooth the shape, so check these views against the observations.</td>
</tr>
<tr>
<td><span id="display-conditions-example">Compare matched observations</span></td>
<td><strong>Connected points</strong> show changes within matched samples that separate group summaries lose. <a href="#ref-display-weissgerber2015">[3]</a>.</td>
</tr>
<tr>
<td>Examine relationships</td>
<td>Use a <strong>scatterplot</strong> for two numerical variables. When overlapping points obscure how many observations occupy a region, try transparency or a <strong>hexbin</strong> display. A hexbin plot shows counts in bins, so individual observations can no longer be identified.</td>
</tr>
<tr>
<td>Follow time or dose</td>
<td><strong>Lines with observations</strong> emphasize progression. Position values according to their actual spacing; use aligned small multiples when several curves become difficult to follow.</td>
</tr>
<tr>
<td>Show composition</td>
<td><strong>Stacked bars</strong> show totals and their components; <strong>proportional stacked bars</strong> show each component’s fraction of the total. Middle segments begin at different positions, so separate dots or bars are often easier for comparing one component across samples.</td>
</tr>
<tr>
<td>Inspect matrices or intersections</td>
<td>A <strong>heatmap</strong> reveals patterns across a matrix, with ordering and scaling affecting what stands out. For numerous set intersections, use <strong>UpSet</strong>; simple Venn or Euler diagrams can suffice for two or three sets.</td>
</tr>
<tr>
<td>Retrieve exact values</td>
<td>Use a <strong>table</strong> with units and enough digits for the intended comparison, without implying more precision than the measurements support. A plot is usually quicker for seeing a trend or ranking; a small plot with value labels can also support exact lookup.</td>
</tr>
</tbody>
</table>

For fuller comparisons and examples, see Wong [[2]](#ref-display-wong2010), Wilke [[1, chapters 6–13 and 18]](#ref-display-wilke2019), Lex and Gehlenborg [[13]](#ref-display-lexgehlenborg2014), and Jambor [[10]](#ref-display-jambortables). The catalogs by Holtz and Healy [[11]](#ref-display-holtzhealy) and Ribecca [[12]](#ref-display-ribecca) show further display options.

<a id="display-explore"></a>

## Explore alternatives

Inspect the observations before settling on a summary. Datasets with similar means and spreads can have quite different patterns; a boxplot, for example, can hide two clusters. If the data include several treatments or sample types, examine them separately as well as together. [[4]](#ref-display-shoresh2012); [[5]](#ref-display-matejka2017).

Change histogram bin widths and density smoothing to see whether an apparent feature persists. Coarse bins merge nearby features, while fine bins can make small fluctuations prominent. Check a violin’s shape against the observations. [[1]](#ref-display-wilke2019), chapters 7–9 and 18.

<a id="display-time-example"></a>**Categories or a time course?**

The same fifteen readings appear in both displays below: one reporter culture per strain measured at 0, 1, 2, 4 and 8 hours. The grouped bars place the strains side by side at each time. In the aligned line panels, it is easier to follow Cedar’s early rise and decline and Hazel’s later rise. The horizontal spacing preserves elapsed time, including the longer interval between the final two measurements. Lines connect the recorded observations; they do not supply measurements between them. [[7]](#ref-display-streit2015); [[1]](#ref-display-wilke2019), chapters 13 and 21.

![Bars for Cedar, Hazel and Willow grouped at 0, 1, 2, 4 and 8 hours, with equal spacing between groups.](../../assets/images/display-time-bars.png)

Grouped bars treat the five observation times as categories.

![Cedar rises early then declines, Hazel rises later, and Willow remains low. Three panels use common zero-to-eight-hour and zero-to-one-hundred-fluorescence axes.](../../assets/images/display-time-lines.png)

Aligned panels show each strain on the same time and fluorescence scales.

All plotted values are illustrative; the glossary icons are schematic.

<a id="display-readability"></a>**Ordering and scales**

<a id="display-order"></a>

Sort categories by value when readers need to identify the largest and smallest amounts. Keep an established sequence, such as developmental stages, when that order helps explain the result. Put the quantities readers need to compare next to one another, using a shared axis or aligned panels. [[1]](#ref-display-wilke2019), chapters 6 and 21; [[12]](#ref-display-ribecca).

<a id="display-scales"></a>

Use the same axis scales across panels when comparing response sizes. If a smaller response becomes difficult to see, add a clearly labeled expanded view beside the full-range comparison. Giving each panel its own scale can make small and large fluctuations look alike. A linear axis uses equal distances for equal differences; a logarithmic axis uses equal distances for equal ratios, which helps compare positive values spanning orders of magnitude. [[1]](#ref-display-wilke2019), chapters 12 and 21; [[8]](#ref-display-mcinerny2015).

<a id="display-dimensions"></a>

If color identifies treatment and shape identifies genotype, try separate panels for each genotype when the symbols become difficult to distinguish. Keep treatment colors and axes consistent across panels. For spatial structures, a three-dimensional view may be needed; compare it with projections when overlap obscures the relationship. [[1]](#ref-display-wilke2019), chapters 5 and 12; [[9]](#ref-display-gehlenborg2012).

<a id="display-check"></a>

Ask a colleague to answer the intended question from the display and caption; a different answer may expose an ambiguous grouping or scale. [[6]](#ref-display-rougier2014).

<a id="display-checklist"></a>**Before settling on a display**

- Can readers find the groups being compared and see which observations are matched?

- Does the caption or legend identify what each mark and summary represents, including units and any denominator?

- Do the order and axis scales make the intended differences visible without exaggerating them?

- Does a view of the individual observations reveal anything hidden by aggregation, smoothing or overlap?

<a id="display-references"></a>

## References

1. <a id="ref-display-wilke2019"></a>[Wilke, C. O. (2019). **Fundamentals of Data Visualization.** O’Reilly Media.](https://clauswilke.com/dataviz/)

2. <a id="ref-display-wong2010"></a>[Wong, B. (2010). **Design of data figures.** *Nature Methods*, 7, 665.](https://doi.org/10.1038/nmeth0910-665)

3. <a id="ref-display-weissgerber2015"></a>[Weissgerber, T. L., Milic, N. M., Winham, S. J., & Garovic, V. D. (2015). **Beyond Bar and Line Graphs: Time for a New Data Presentation Paradigm.** *PLOS Biology*, 13(4), e1002128.](https://doi.org/10.1371/journal.pbio.1002128)

4. <a id="ref-display-shoresh2012"></a>[Shoresh, N., & Wong, B. (2012). **Data exploration.** *Nature Methods*, 9, 5.](https://doi.org/10.1038/nmeth.1829)

5. <a id="ref-display-matejka2017"></a>[Matejka, J., & Fitzmaurice, G. (2017). **Same Stats, Different Graphs: Generating Datasets with Varied Appearance and Identical Statistics through Simulated Annealing.** *Proceedings of CHI 2017*. ACM.](https://doi.org/10.1145/3025453.3025912)

6. <a id="ref-display-rougier2014"></a>[Rougier, N. P., Droettboom, M., & Bourne, P. E. (2014). **Ten Simple Rules for Better Figures.** *PLOS Computational Biology*, 10(9), e1003833.](https://doi.org/10.1371/journal.pcbi.1003833)

7. <a id="ref-display-streit2015"></a>[Streit, M., & Gehlenborg, N. (2015). **Temporal data.** *Nature Methods*, 12, 97.](https://doi.org/10.1038/nmeth.3262)

8. <a id="ref-display-mcinerny2015"></a>[McInerny, G., & Krzywinski, M. (2015). **Unentangling complex plots.** *Nature Methods*, 12, 591.](https://doi.org/10.1038/nmeth.3451)

9. <a id="ref-display-gehlenborg2012"></a>[Gehlenborg, N., & Wong, B. (2012). **Into the third dimension.** *Nature Methods*, 9, 851.](https://doi.org/10.1038/nmeth.2151)

10. <a id="ref-display-jambortables"></a>[Jambor, H. (n.d.). **How to… Tables.** *HelenaJamborWrites*. [Web guide; publication date not stated; archived version accessed May 3, 2026].](https://helenajamborwrites.netlify.app/posts/tables/tabledesign)

11. <a id="ref-display-holtzhealy"></a>[Holtz, Y., & Healy, C. (n.d.). **From Data to Viz.** [Website; accessed 17 September 2026].](https://www.data-to-viz.com/)

12. <a id="ref-display-ribecca"></a>[Ribecca, S. (n.d.). **The Data Visualisation Catalogue.** [Website; accessed 17 September 2026].](https://datavizcatalogue.com/)

13. <a id="ref-display-lexgehlenborg2014"></a>[Lex, A., & Gehlenborg, N. (2014). **Sets and intersections.** *Nature Methods*, 11, 779.](https://doi.org/10.1038/nmeth.3033)
