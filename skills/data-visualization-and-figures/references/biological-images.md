# Make image evidence interpretable

Read this for microscopy, photographs, channels, crops, annotations or image quantification. Inspect the actual image before judging contrast, artifacts, exact placement or visibility. Do not invent specimen identity, calibration, acquisition settings or processing history.

## Decide what the image must establish

A morphology comparison, an intensity comparison and a demonstration of an analysis pipeline need different displays. Choose the scale at which the decisive feature is visible. Pair an overview with an accurately located detail when both context and small structures matter. Supply recoverable physical scale and units; a clearly applicable shared scale can serve multiple panels, but each differently resized crop needs correct scale context. Magnification alone does not survive resizing reliably.

Identify specimen, channel/target, orientation and time when they affect interpretation. Mark the inset's source region accurately. Check annotations and scale bars after resizing and export; moving an inset box changes the implied evidence. Crop and rotate without changing the represented phenotype. Pixel rotations other than multiples of 90 degrees generally interpolate; inspect the actual processing/export path and retain quantitative originals.

## Distinguish structure from intensity

Before comparing brightness, establish whether acquisition settings, calibration and preprocessing make the inputs comparable. Shared display limits cannot repair incomparable acquisition. When inputs are comparable, use a common relevant mapping for corresponding channels and disclose it. Preserve real differences rather than normalizing each panel to its own maximum.

Independent contrast ranges can reveal morphology if clearly disclosed; displayed brightness then does not establish an intensity difference. Nonlinear adjustments can affect interpretation and need explanation. Supply an intensity scale or linear reference where the question requires it. Do not turn every ideal reporting practice into a universal requirement for every image.

Changed condition: images acquired at different gains may illustrate morphology with independently disclosed ranges if signals are unsaturated and relevant features remain recoverable; contrast adjustment cannot repair acquisition damage. Intensity remains uninterpretable without calibration. Comparable images with one signal twice as large need a shared mapping if the reader is to see that difference.

## Choose channels and annotations for the feature

Grayscale often makes single-channel detail easier to inspect, while natural-color photographs or meaningful pseudocolor can serve other tasks. Color changes perceived brightness even when the underlying histogram is unchanged. A brighter hue can reveal a weak channel without making its measured signal stronger. Explain channel mappings and inspect their actual combination; separate-channel panels can make merges easier to interpret.

A white-plus-color overlay can clarify organization but can impede judging the degree of colocalization. An attractive merge is not quantitative colocalization evidence. Gamma applied after colorization can also alter hue. Inspect the output after rendering or print conversion rather than assuming a palette name guarantees readable structures.

Use pointers, outlines, brackets and labels according to what they identify. A direction arrow, a feature pointer and a region boundary have different meanings. Keep annotations off decisive structures; use an annotated companion when necessary. Explain symbols locally without multiplying colors and shapes gratuitously.

## Separate representative views from quantitative evidence

State selection and replicate context when an image represents a broader result. Quantification needs the measurement definition, sampling/independent units and relevant preprocessing, segmentation or manual selection. Measure from appropriate analysis inputs, not an assembled presentation copy.

Describe software versions, settings, manual steps and availability sufficiently to understand the result. An established workflow and a new or retrained model have different reporting needs; the latter needs applicable training provenance, validation examples and limitations. Distinguish source recommendations from current venue requirements. Large-data sharing may use faithful cropped or reduced versions when appropriate, while preserving originals and explaining what was omitted. Do not claim unavailable datasets or unknown metadata were inspected.

Use legends and accessible descriptions to identify the material, channels and consequential processing. They complement legible images; they cannot repair a structure that disappears at final size.
