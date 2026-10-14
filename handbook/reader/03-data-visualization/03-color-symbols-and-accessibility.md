<a id="quarto-document-content"></a> 

<a id="title-block-header"></a>

<a id="color-chapter"></a>

# Color, symbols and accessibility

Color can identify groups, show how a quantity varies or draw attention to a selected observation. First decide whether color helps: labels, position and separate panels may already make the distinction clear. When color adds information, choose its role and visual strength deliberately. [[1]](#ref-color-wilke2019); [[3]](#ref-color-wongavoid2011).

<a id="color-purpose"></a>

## Decide what color should show

For a plot of one series, a single dark color is usually enough. Several groups can also share a neutral color when labeled positions separate them. Use distinct treatment colors when they help readers follow treatments within or across panels, and keep those assignments consistent. Avoid giving every bar or point a different color when its label or position already identifies it. [[9]](#ref-color-rougier2014); [[8]](#ref-color-muth2018).

To highlight one group, give it an accent color and label it. Keep the other observations visible in a subdued color. If readers should compare all groups equally, avoid making one much brighter or more saturated than the others: it can attract attention for reasons unrelated to the data. [[2]](#ref-color-wongcolor2010); [[1]](#ref-color-wilke2019).

Color is useful for finding patterns in a large matrix, but less reliable for judging small numerical differences. The same colored square can look different against light and dark surroundings. If readers need to compare a few values precisely, put them on a common axis or print the values rather than asking readers to estimate them from a color key. [[3]](#ref-color-wongavoid2011); [[5]](#ref-color-gehlenborgcolor2012).

<a id="color-scales"></a>

## Match the scale to the data

<a id="color-scale-types"></a>

### Groups, magnitudes and deviations

Use a **categorical palette** when color identifies groups without a numerical order, such as cell types or treatments. Its colors should be distinguishable without implying a ranking. A pale-to-dark progression instead suggests order and is better suited to quantities such as dose. Established palettes, including Okabe–Ito, are useful candidates, not a required visual style. A more subdued palette may suit large areas or a quiet figure, provided essential distinctions and contrast survive in the actual plot. Accessibility does not require bright, highly saturated colors. [[4]](#ref-color-wongblind2011); [[2]](#ref-color-wongcolor2010); [[1]](#ref-color-wilke2019).

Use a **sequential scale** for values that run from low to high. Lightness should progress in one direction so that the order remains visible. A perceptually balanced scale also aims to give equal numerical steps comparable visible changes; monotonic lightness alone does not ensure that balance. This can be a single-hue gradient or a multihue palette such as cividis or viridis. Consider which values should stand out against the background: dark marks are prominent on white, while light marks stand out on a dark background. [[5]](#ref-color-gehlenborgcolor2012); [[7]](#ref-color-crameri2024).

Use a **diverging scale** to distinguish values above and below a reference, such as no change or a specified target. Give the two sides different hues and make the reference neutral. No change is zero for a log fold change and one for a ratio. Set that reference explicitly; the middle of the observed range may represent a different value. [[5]](#ref-color-gehlenborgcolor2012); [[7]](#ref-color-crameri2024).

The signs of the stored numbers do not determine the palette. Ratios of 0.5 and 2 are both positive, but lie on opposite sides of no change. The same numbers as absolute concentrations may simply run from low to high. For ratios, decide whether equal additive departures or equal fold departures should have comparable emphasis. On a log₂ ratio scale, 0.5 and 2 become −1 and +1; label that transformation so readers can recover the meaning. [[5]](#ref-color-gehlenborgcolor2012); [[1]](#ref-color-wilke2019).

<a id="color-reference-example"></a>**The quantity determines the reference**

![Two stacked two-by-three heatmaps contain values 0.5, 1, 2, 0.75, 1.5 and 4. A uses a subdued diverging scale with log2 spacing and neutral ratio one. B uses cividis from zero to four micromolar. Both have labeled colorbars and identical printed cell values.](../../assets/images/color-reference-meaning.png)

Identical invented numbers represent ratios in A and concentrations in B. The ratio scale centers on one and gives twofold increases and decreases equal color strength. The concentration scale runs from low to high without implying a target concentration. Cell labels retain the original values.

<a id="color-scale-guide"></a>**Three common color encodings**

![Three labeled rows: Control, Treatment and Recovery have distinct blue, vermilion and green swatches; a sequential scale runs from dark low to light high; a diverging scale runs from blue negative through pale zero to red positive.](../../assets/images/color-scales.png)

Categories use separate colors; magnitudes follow an ordered gradient; deviations use two directions from a reference. Shown here: three Okabe–Ito colors, cividis and RdBu.

Avoid rainbow scales for ordinary quantitative data. Their uneven changes in hue and lightness can create apparent boundaries where the values change smoothly, while making other differences difficult to see. Selecting a well-designed scale is easier than constructing one by eye. [[2]](#ref-color-wongcolor2010); [[1]](#ref-color-wilke2019).

Two less common choices are useful when the data require them. A **cyclic scale** has matching ends, so angles near 0° and 360°, or phases immediately before and after a cycle boundary, look similar. A **discrete ordered scale** divides values into labeled ranges. Use it when those ranges matter; use a continuous gradient when variation within them matters. Show the boundaries of discrete ranges in the key. [[7]](#ref-color-crameri2024).

<a id="color-limits"></a>

### Set the reference and limits

Use the same color limits for panels whose values you want readers to compare. Otherwise, a color indicating a small response in one panel may indicate a much larger response in another. Within a single panel, you can show the full possible range or a narrower range that makes small differences easier to see. Show the chosen limits in the colorbar. [[5]](#ref-color-gehlenborgcolor2012).

<a id="color-range-example"></a>**Full possible range or local range?**

The same invented percentages appear twice. On the full 0–100% scale, the 42–58% values have little color contrast. On the stated 40–60% local scale, their differences are easier to see. The narrow scale uses its strongest colors for values still near 50%, so readers need the colorbar to interpret their size. Use shared limits if these values must be compared with other panels.

![Two stacked heatmaps show the same twelve reporter-positive percentages from 42 to 58. The upper panel has a 0 to 100 percent cividis colorbar and subtle color differences. The lower has a 40 to 60 percent colorbar and larger visible differences. Every cell contains the same numerical label in both panels.](../../assets/images/color-range-limits.png)

Two identical heatmaps of reporter-positive percentages. The upper colorbar spans zero to one hundred percent and the lower spans forty to sixty percent; all cells retain their printed values.

For a diverging scale, equal departures from the reference should receive comparable color strength. With values from −1 to +3, stretching both ends to equally strong colors would give −1 as much emphasis as +3. A balanced −3 to +3 scale avoids that distortion, even though part of its negative range is unused. [[7]](#ref-color-crameri2024).

<a id="color-midpoint-example"></a>**Center the scale on the biological reference**

These invented log₂ fold changes range from −1 to +3. Zero means no change. Both panels show the same values.

![Two heatmaps show identical labeled values for three genes and four conditions. The upper colorbar runs from minus one to plus three, so plus one is pale and zero appears blue. The lower colorbar runs from minus three to plus three, so zero is pale, negative values are blue and positive values are red.](../../assets/images/color-midpoint.png)

Automatic minimum-to-maximum scaling puts the pale color at +1. Centering the scale on zero correctly distinguishes decreases from increases and gives equal-sized changes comparable emphasis.

Label what the colorbar measures, including units and transformations: for example, “log₂ fold change” or “row-standardized expression.” If values beyond a limit all receive the same end color, indicate that saturation in the key. Give missing values a separate labeled appearance so they cannot be mistaken for zero or the lowest measurement. [[5]](#ref-color-gehlenborgcolor2012); [[1]](#ref-color-wilke2019).

<a id="color-symbols"></a>

## Keep series identifiable without unnecessary variation

A useful starting style for a few ordinary trajectories is solid lines, with circles where markers help show measured positions. Label lines near their ends when there is room. If the labels and paths make every series traceable, there is no need to give each one a different dash pattern and symbol as well. For dense continuous curves, markers may add clutter without information. These are starting choices, to be judged in the actual figure. [[6]](#ref-color-symbols2013); [[1]](#ref-color-wilke2019).

Use another encoding when it does a job: dashes might distinguish a forecast from observations, and shapes might distinguish a second factor or help identify overlapping groups in monochrome. Explain that meaning in the labels or key. When several curves cross, check that a reader can follow each path; an endpoint label alone may be insufficient. Try separate panels before adding increasingly complex dash and marker combinations. Refer to groups by name in the caption, rather than only as “the red line.” [[6]](#ref-color-symbols2013); [[7]](#ref-color-crameri2024); [[1]](#ref-color-wilke2019).

Choose shapes that remain distinct at the final size. Circles and squares are usually easier to distinguish than several similar polygons. Adjust their sizes so they appear equally prominent; equal numerical marker sizes do not necessarily give equal visual weight. Open circles can reveal overlapping boundaries, whereas large filled symbols can merge into a solid patch. If overlap is severe, changing symbols alone will not solve it: separate groups into panels or use a distribution display. [[6]](#ref-color-symbols2013).

Color and shape can identify the same treatment when that redundancy improves reading. They can instead encode two variables, such as treatment and genotype. Each combination then represents a different group. Separate panels for genotype can make those combinations easier to follow while retaining consistent treatment colors. In the facets below, panel titles replace the need for genotype-specific markers and dashes. [[6]](#ref-color-symbols2013); [[1]](#ref-color-wilke2019).

<a id="color-facets-example"></a>**Separate panels for each genotype**

Separate WT and KO panels make the treatment response easier to follow within each genotype. The combined view is useful for comparing genotypes directly, but readers must distinguish both colors and symbols. Both arrangements show the same invented values.

![At top, one line graph contains four reporter-signal trajectories. Blue and vermilion identify control and stimulated treatment; circle solid and square dashed styles identify WT and KO. Below, separate WT and KO panels show the same values with blue control and vermilion stimulated trajectories.](../../assets/images/color-facets.png)

A line plot with four series uses color for treatment and marker and line style for genotype. Below it, two panels labelled WT and KO show the same treatment trajectories with consistent blue and vermilion colors.

<a id="color-identification-example"></a>**Keep series identifiable without hue**

![Two stacked plots show the same Pulse and Sustained reporter signals from zero to six hours. Both use circles and solid lines with dark endpoint labels. The upper plot uses subdued blue and brown, and the lower preserves their different luminances in grayscale.](../../assets/images/color-identification.png)

The same invented reporter trajectories in subdued color and grayscale. Both use solid lines and circles; direct labels and distinct gray levels identify the two simple paths.

<a id="color-contrast"></a>

## Make marks readable on their background

A palette that works in large swatches may fail on thin lines or small points. Inspect the plot at its intended reading size. Darken pale marks, increase their size or weight, or use a more distinct shape if they disappear. Large filled areas often need less saturation than small marks; intense fills can overwhelm nearby labels and grid lines. [[2]](#ref-color-wongcolor2010); [[1]](#ref-color-wilke2019).

Check colors against the background and against neighboring marks. Yellow may be clear on a dark background but nearly invisible on white. Transparency also changes the displayed color through blending, so inspect overlapping regions as well as isolated points. Keep essential labels dark enough to read; a label need not inherit the color of the series it names. [[8]](#ref-color-muth2018); [[2]](#ref-color-wongcolor2010); [[1]](#ref-color-wilke2019).

For choosing colors for fluorescence channels and showing merged images, see [Biological images](04-biological-images.md#bioimage-chapter). [[4]](#ref-color-wongblind2011).

<a id="color-check"></a>

## Check accessibility and consistency

Inspect the finished figure under simulations of common red–green and blue–yellow color-vision deficiencies. Test whether the groups remain distinguishable, whether a quantitative gradient still has a clear order, and whether labels and small marks remain visible. If a distinction disappears, change the palette or supply it through labels, shapes or separate panels. Check the exported figure, not just the palette preview. [[4]](#ref-color-wongblind2011); [[1]](#ref-color-wilke2019).

Grayscale reveals weak contrast and whether identification depends entirely on hue. A symmetric diverging scale will often give negative and positive values similar gray levels: it preserves distance from the center but loses direction. If that direction must survive monochrome reproduction, add signed values, explicit labels or separate views. [[7]](#ref-color-crameri2024); [[1]](#ref-color-wilke2019).

Treat these checks separately. A figure can preserve contrast in grayscale yet lose a distinction under a particular color-vision deficiency; a palette can separate hues yet leave thin marks too faint against the page. Simulations help identify failures but do not establish that every reader can use the figure. Judge the needed comparisons in the finished display, including its labels and arrangement. [[4]](#ref-color-wongblind2011); [[8]](#ref-color-muth2018).

Check the figure alongside the rest of the paper. Do recurring groups keep their colors and symbols? Do comparable panels use the same scale and reference? Check that keys, direct labels and captions agree, including the labels for missing values and highlighted observations. [[8]](#ref-color-muth2018).

<a id="color-checklist"></a>**Before finalizing the colors and symbols**

- Does each encoding identify a group, show a quantity or mark a deliberate highlight?

- Would fewer hues, shapes or dash patterns make the figure easier to follow without losing a needed distinction?

- Do the palette type, reference and limits match the quantity being shown?

- Can readers distinguish the important groups without relying on hue alone?

- Are marks and labels readable at final size, including in grayscale and color-vision simulations?

- Do recurring colors and symbols mean the same thing across panels?

The teaching graphics use invented values or schematic encodings.

<a id="color-references"></a>

## References

1. <a id="ref-color-wilke2019"></a>[Wilke, C. O. (2019). **Fundamentals of Data Visualization.** O’Reilly Media.](https://clauswilke.com/dataviz/)

2. <a id="ref-color-wongcolor2010"></a>[Wong, B. (2010). **Color coding.** *Nature Methods*, 7, 573.](https://doi.org/10.1038/nmeth0810-573)

3. <a id="ref-color-wongavoid2011"></a>[Wong, B. (2011a). **Avoiding color.** *Nature Methods*, 8, 525.](https://doi.org/10.1038/nmeth.1642)

4. <a id="ref-color-wongblind2011"></a>[Wong, B. (2011b). **Color blindness.** *Nature Methods*, 8, 441.](https://doi.org/10.1038/nmeth.1618)

5. <a id="ref-color-gehlenborgcolor2012"></a>[Gehlenborg, N., & Wong, B. (2012). **Mapping quantitative data to color.** *Nature Methods*, 9, 769.](https://doi.org/10.1038/nmeth.2134)

6. <a id="ref-color-symbols2013"></a>[Krzywinski, M., & Wong, B. (2013). **Plotting symbols.** *Nature Methods*, 10, 451.](https://doi.org/10.1038/nmeth.2490)

7. <a id="ref-color-crameri2024"></a>[Crameri, F., Shephard, G. E., & Heron, P. J. (2024). **Choosing Suitable Color Palettes for Accessible and Accurate Science Figures.** *Current Protocols*, 4, e1126.](https://doi.org/10.1002/cpz1.1126)

8. <a id="ref-color-muth2018"></a>[Muth, L. C. (2018, May 29). **What to consider when choosing colors for data visualization.** Datawrapper Blog. Accessed September 18, 2026.](https://www.datawrapper.de/blog/colors)

9. <a id="ref-color-rougier2014"></a>[Rougier, N. P., Droettboom, M., & Bourne, P. E. (2014). **Ten Simple Rules for Better Figures.** *PLOS Computational Biology*, 10(9), e1003833.](https://doi.org/10.1371/journal.pcbi.1003833)
