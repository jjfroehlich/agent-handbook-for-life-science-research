# Biological Images

Use this for microscopy, photographs, electron microscopy, clinical images, image panels, overlays, insets, scale bars, channels, stains, annotations, and quantified image displays.

## Use this when...

- The figure uses images as evidence rather than only decoration.
- The user asks about scale bars, insets, annotation hierarchy, channel identity, overlays, representative images, or image-analysis reporting.
- The biological claim depends on what can be seen in the image.

## The job of this topic

Make image evidence interpretable by exposing scale, identity, channel meaning, annotation logic, selection context, and analysis workflow.

## Default workflow

1. Identify image type and specimen: organism, tissue, cell type, structure, stain/channel, and acquisition context if supplied.
2. Inspect the actual image before judging contrast, artifact, exact annotation placement, scale-bar adequacy, or visual quality.
3. Check scale: use scale bars or dimensions with units where interpretation requires them.
4. Check insets: mark source regions, state the magnification relationship, and keep crop boundaries clear.
5. Check channel/color mapping: explain each channel color and biological target; ensure merged views remain interpretable.
6. Check annotations: arrows, outlines, labels, and symbols should identify features without covering evidence.
7. If images are quantified, separate representative-image display from analysis workflow and replicate reporting.

## Decision rules

- Scale information is required when size, morphology, distance, or localization matters.
- Magnification alone is weaker than a scale bar or explicit dimension at final display size.
- Insets need both source-region markers and their own scale context.
- Channels need both color identity and biological target identity.
- Dense annotations should move outside the image, use callouts, or provide annotated and unannotated versions.
- Quantified image claims need acquisition, preprocessing, segmentation or selection criteria, measurement definition, replicate structure, statistics, and software/data availability where relevant.

## Variants and edge cases

- Multi-channel fluorescence: use single-channel panels plus a merged panel when readers must judge channel-specific signal.
- Representative images: state the sampling or replicate context when the image supports a general claim.
- Photographs: include orientation, specimen identity, and scale/object reference where they affect interpretation.
- Intensity comparisons: use shared display ranges and processing for corresponding channels, with acquisition and measurements that make intensities comparable. Independently adjusted ranges can reveal structure, but displayed brightness then cannot establish an intensity difference; disclose those adjustments.
- Nonlinear or consequential processing: identify it, retain the analysis inputs and provide a linear display when needed to interpret the adjustment. Do not measure from an assembled presentation copy.

## Anti-patterns

- Missing scale bars or units.
- Insets without parent-location boxes.
- Channel colors unexplained in the legend.
- Arrows or labels covering the feature they identify.
- Representative images used as the only support for a quantitative claim.

## Diagnostic questions

- Can a reader tell what organism, tissue, cell, or object is shown?
- Are all compared panels interpretable at compatible scales?
- Does the legend explain channels, stains, annotations, insets, and sample context?
- Would the image still work in grayscale or for common color-vision deficiencies?
- Does quantification rely on image-processing choices that need disclosure?

## Output patterns / mini-templates

```text
Image-panel issue: <scale/inset/channel/annotation/workflow>.
Fix: <specific change>.
Legend addition: <required explanatory text>.
Visual inspection needed: <contrast/artifact/exact placement claim, if not inspected>.
Risk if unfixed: <interpretive failure>.
```

## Examples

- `Inset with no box`: add a rectangle on the parent panel and label the inset scale.
- `Merged fluorescence only`: add single-channel panels if the reader must judge channel-specific signal.
- `Representative image plus quantification`: report how images were selected, segmented, measured, and summarized.

## When not to apply this

Do not give acquisition-protocol advice unless asked; keep the answer on figure interpretation, presentation, and reporting.
