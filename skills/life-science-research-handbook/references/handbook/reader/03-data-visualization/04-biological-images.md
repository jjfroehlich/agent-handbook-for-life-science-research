<a id="quarto-document-content"></a> 

<a id="title-block-header"></a>

<a id="bioimage-chapter"></a>

# Biological images

Show images in which readers can inspect the feature you discuss, alongside its measurements when available. Prepare the figure from copies and preserve the images used for analysis.

<a id="bioimage-select"></a>

## Select and frame images

Choose fields from the images used in the analysis that reflect the reported result. When a phenotype varies substantially, show several examples spanning that variation rather than one especially striking cell. Place them beside the corresponding quantitative results. [[2]](#ref-bioimage-schmied2024), image formatting.

A tissue overview shows how structures are arranged; a closer view can reveal cell shape or where a marker lies within a cell. If readers need both, pair the overview with an enlarged region. Check that the feature remains visible at the figure’s final size before deciding how many images fit in a panel. [[1]](#ref-bioimage-jamborimages2021), Figure 3.

<a id="bioimage-crop"></a>

### Crop without losing context

Crop empty margins or irrelevant regions, but retain neighboring structures that affect the interpretation. Mark the exact enlarged region on the overview and place the detail beside it. An inset within the overview saves space only when it does not cover relevant data. Use a visible gap between separate images so their edges cannot be mistaken for a continuous field. [[1]](#ref-bioimage-jamborimages2021), Figure 3; [[2]](#ref-bioimage-schmied2024), Figure 4a–c.

Keep the image’s proportions when resizing. If rotating images makes anatomical comparisons easier, use a consistent orientation and label it. Rotation by an arbitrary angle resamples pixels in many image editors; make measurements on the analysis images before preparing rotated copies for the figure. [[2]](#ref-bioimage-schmied2024), image formatting.

<a id="bioimage-scale"></a>

### Calibrate each view

Add a scale bar with its length and unit. Use the image’s spatial calibration; an objective label such as “40×” does not specify the size of a feature in a resized figure. Put the bar where it contrasts with the background without covering the feature of interest. When no suitable area exists, place it just outside the image. [[1]](#ref-bioimage-jamborimages2021), Figure 4; [[2]](#ref-bioimage-schmied2024), image annotation.

<a id="bioimage-scale-example"></a>An enlarged crop needs its own scale indication. Keep a scale bar attached to its image when resizing, or regenerate it from the final calibration. [[1]](#ref-bioimage-jamborimages2021); [[2]](#ref-bioimage-schmied2024).

<a id="bioimage-channels"></a>

## Show channels

For a single fluorescence channel, start with grayscale. Dark blue or red against black can hide fine structures that are readily visible in grayscale. An inverted grayscale display can help with thin structures on a light page; keep the choice consistent across comparable panels. [[3]](#ref-bioimage-plucinska2017a); [[1]](#ref-bioimage-jamborimages2021), Figures 5–6.

<a id="bioimage-visibility-example"></a>**The same structures under different color mappings**

![A published comparison repeats the same actin-labeled cells in nine color mappings. White on black and inverted grayscale retain fine structures; dark blue and red on black make them harder to see. The right half shows corresponding grayscale visibility previews.](../../assets/images/bioimage-visibility.png)

Actin in Dictyostelium discoideum expressing LifeAct-GFP, shown with several color mappings and corresponding grayscale previews. All views have the same spatial scale; the source’s scale bar is 40 µm.

Figure 6 reproduced unchanged from [Jambor and colleagues (2021)](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3001161), © the authors, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Compare the fine extensions around the cells, rather than only their bright centers.

<a id="bioimage-overlays"></a>

### Combine an overlay with separate channels

Use a merged image to show where labeled structures lie relative to one another. Include separate grayscale channels when overlap or unequal brightness makes either component difficult to inspect. Keep the field, crop and orientation identical across the component images and merge. Label channels with their markers or targets, and use those labels consistently throughout the figure. [[4]](#ref-bioimage-plucinska2017b); [[1]](#ref-bioimage-jamborimages2021), Figures 7–8.

Choose display colors for visibility rather than to match fluorophore names. Cyan and magenta are useful starting choices for two channels; assess the actual merge under color-vision simulations. A palette that separates bright objects may still hide a weak channel. Separate grayscale panels let readers inspect that channel without relying on the composite color. [[4]](#ref-bioimage-plucinska2017b); [[1]](#ref-bioimage-jamborimages2021).

Keep colors assigned to the same targets across conditions. Do not compare the abundance of two targets from their apparent brightness in different colors: color mapping, staining and acquisition affect that appearance. If you make a claim about how much two markers overlap, show how overlap was measured. The color of a merge alone does not establish its extent. [[4]](#ref-bioimage-plucinska2017b); [[2]](#ref-bioimage-schmied2024), image colors and channels.

<a id="bioimage-range"></a>

## Intensity ranges and processing

Choose the displayed minimum and maximum while inspecting both the image and its intensity histogram. A range that is too wide can make real structures nearly invisible. A range that is too narrow clips dim pixels to black or bright pixels to white, concealing differences within those regions. Start with a linear mapping and retain the features needed for the comparison. [[2]](#ref-bioimage-schmied2024), Figure 4d.

For images intended to compare signal intensity, use the same display range and processing for the corresponding channel across conditions. Automatic contrast applied separately to each image can make a weak signal look as bright as a strong one. Check how the images were acquired and analyzed too: identical display settings cannot correct differences introduced during acquisition or analysis. [[2]](#ref-bioimage-schmied2024), image colors and channels.

<a id="bioimage-intensity-example"></a>**Shared and independent intensity ranges**

![A synthetic calibration pattern is shown as two intensity transforms. With a shared 0 to 1 arbitrary-unit range, the panels retain their different displayed brightness. With independent ranges, both panels show similar contrast, so structure is easier to inspect but brightness cannot be compared.](../../assets/images/bioimage-intensity-ranges.png)

Synthetic calibration pattern shown with a shared 0–1 a.u. display range (top) and independently stretched ranges (bottom). The pattern is not microscopy data.

Independent stretching makes both patterns look alike despite their different intensity ranges. It helps inspect their structure but removes the brightness comparison.

When the purpose is to compare structure and the images differ greatly in brightness, separately adjusted views may reveal details that a common range hides. Identify those adjustments in the caption, and use the quantitative measurements to compare intensity. Keep each view’s range visible when the numerical intensity scale is important. [[2]](#ref-bioimage-schmied2024), Figure 2 and image colors and channels.

<a id="bioimage-processing"></a>

### Make transformations visible

Gamma adjustment and other nonlinear mappings change the relative display of weak and strong intensities. If one is needed to reveal structure, identify it and provide a linearly mapped comparison. Include a labeled intensity scale for pseudocolor or nonlinear displays. [[2]](#ref-bioimage-schmied2024), Figures 2 and 4g.

Filtering, deconvolution and learned image restoration can also change the appearance of structures. Identify these operations in the caption and describe their settings in Methods. Preserve the input images so readers can inspect them before restoration. State which processing was used for measurements and which adjustments were made only for display. [[2]](#ref-bioimage-schmied2024), image colors and channels; image-analysis workflows.

<a id="bioimage-quantification"></a>

## Connect images to measurements

When a result comes from image analysis, show an example input image. If segmentation determines which objects or regions were measured, add outlines or masks showing those boundaries. Keep an unobstructed image alongside a dense overlay. Include difficult cases when errors, such as merging neighboring objects, could change the counts or measurements. [[2]](#ref-bioimage-schmied2024), image formatting and image-analysis workflows; [[1]](#ref-bioimage-jamborimages2021), Figure 11.

<a id="bioimage-segmentation-example"></a>**Example: inspect the segmentation before counting**

![Four panels show the S-BIAD634 normal_39 fluorescence source image, the same image with supplied expert instance boundaries, a crop with label 31 outlined, and source-pixel areas for 66 supplied instances. The displayed annotation was not independently revalidated for this handbook.](../../assets/images/bioimage-segmentation.png)

A real fluorescence image, its supplied expert instance boundaries, a labeled boundary crop, and the source-pixel areas of the supplied instances.

The crop shows two touching nuclei assigned separate labels in the supplied expert annotation. The red outline identifies the nucleus represented by the red point in the area plot (1,260 source pixels²). The 66 areas are calculated from the original mask; this example uses the supplied annotation without an independent accuracy assessment.

Adapted from the CC0 S-BIAD634 BioImage Archive dataset, An annotated fluorescence image dataset for training nuclear segmentation methods, by Taschner-Mandl and colleagues (2023); raw image and supplied expert annotation normal_39. [S-BIAD634](https://www.ebi.ac.uk/biostudies/BioImages/studies/S-BIAD634) is released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).

In the accompanying quantitative plot, preserve the grouping of cells or fields within samples. Many cells from one culture do not show how the finding varies between cultures. The chapter on [observations and uncertainty](02-showing-observations-and-uncertainty.md#uncertainty-chapter) explains how to display this grouping and choose summaries. [[5]](#ref-bioimage-lord2020).

<a id="bioimage-labels"></a>

### Labels and annotations

Use a few arrows, outlines or direct labels to identify the structures relevant to the comparison. Place labels beside small features rather than on top of them. Distinguish annotation types by shape or line style when they have different meanings; color alone can be difficult to distinguish against a multicolored image. If numerous labels obscure the image, provide a separate annotated copy. [[1]](#ref-bioimage-jamborimages2021), Figures 10–13 and Table 1.

For a time series, put elapsed time on each frame and keep the framing and scale consistent. Label the anatomical orientation of a section and identify any projection, so readers know which view of the specimen they are seeing. [[2]](#ref-bioimage-schmied2024), image annotation and Figure 5.

**In the caption**, identify the specimen and tissue, markers or stains, channel colors, scale and annotations. Explain any inset or projection. State whether images have separate intensity adjustments and identify processing that changes their appearance, as described above. Put acquisition and analysis details in Methods, including the software, version, parameters and manual selections needed to reproduce the workflow. [[1]](#ref-bioimage-jamborimages2021), section 7; [[2]](#ref-bioimage-schmied2024), image-analysis workflows.

<a id="bioimage-record"></a>

## Verify the image figure

Keep the original images and metadata, the analysis inputs and outputs, and the assembled figure as separate files. Record which source image produced each panel and which crop, channel mapping and adjustments were applied. Share the images used in figures and quantification through an appropriate repository where possible, together with the workflow and example inputs and outputs. [[2]](#ref-bioimage-schmied2024), image availability and image-analysis workflows.

Inspect the exported figure at publication size. Check that the crop markers still point to the correct regions, scale bars remain attached to their images, weak structures are visible and annotations do not cover the evidence. [[1]](#ref-bioimage-jamborimages2021), sections 1–6.

<a id="bioimage-checklist"></a>**Final image check**

- The selected fields show the reported phenotype and its variation.

- Crops retain necessary context; enlarged regions and physical scales are clear.

- Each channel is identifiable, and the merge does not hide essential structures.

- Images used for intensity comparisons share display ranges; separate or nonlinear adjustments are disclosed.

- Readers can see the input image and the objects or regions used for image-derived measurements.

- The exported panels can be traced to preserved images and processing records.

<a id="bioimage-references"></a>

## References

1. <a id="ref-bioimage-jamborimages2021"></a>[Jambor, H., and colleagues (2021). **Creating clear and informative image-based figures for scientific publications.** *PLOS Biology*, 19(3), e3001161.](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3001161)

2. <a id="ref-bioimage-schmied2024"></a>[Schmied, C., and colleagues (2024). **Community-developed checklists for publishing images and image analyses.** *Nature Methods*, 21(2), 170–181.](https://doi.org/10.1038/s41592-023-01987-9)

3. <a id="ref-bioimage-plucinska2017a"></a>[Plucinska, G. (2017a, March 1). **Microscopic images [1].** *Data in the spotlight*. Blog post.](https://www.gabrielaplucinska.com/blog/2017/8/15/microscopic-images-1)

4. <a id="ref-bioimage-plucinska2017b"></a>[Plucinska, G. (2017b, March 12). **Microscopic images [2].** *Data in the spotlight*. Blog post.](https://www.gabrielaplucinska.com/blog/2017/8/15/microscopic-images-2)

5. <a id="ref-bioimage-lord2020"></a>[Lord, S. J., Velle, K. B., Mullins, R. D., & Fritz-Laylin, L. K. (2020). **SuperPlots: Communicating reproducibility and variability in cell biology.** *Journal of Cell Biology*, 219(6), e202001064.](https://doi.org/10.1083/jcb.202001064)

6. <a id="ref-bioimage-sbiad634"></a>[Taschner-Mandl, S., and colleagues (2023, March 7). **An annotated fluorescence image dataset for training nuclear segmentation methods.** BioImage Archive, S-BIAD634. Dataset.](https://www.ebi.ac.uk/biostudies/BioImages/studies/S-BIAD634)
