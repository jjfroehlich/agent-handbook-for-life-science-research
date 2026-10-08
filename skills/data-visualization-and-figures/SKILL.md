---
name: data-visualization-and-figures
description: "Choose or critique how scientific evidence is displayed. Exclude plotting-code fixes and implementation of settled visual specifications."
license: MIT
metadata:
  author: jjfroehlich
  version: "0.1.1"
---

# Data Visualization And Figures

## Purpose

Help the agent make scientific figures honest, readable, accessible, and ready for their medium by matching the visual form to the evidence and reader task.

## Use this skill when

- The primary task requires figure critique, chart choice, plot redesign, table redesign, graphical abstract planning, or publication-ready visual judgment.
- The artifact includes distributions, p-values, effect sizes, intervals, small samples, repeated experiments, heatmaps, networks, genomic views, set intersections, or dense multi-panel displays.
- The request involves microscopy, photographs, image overlays, scale bars, insets, channels, annotations, layout, labels, typography, color, accessibility, posters, slides, or manuscript export.
- A mixed code-and-figure request still requires unresolved visual-design judgment, such as choosing scales, encodings, facet structure, page composition, or uncertainty display; the presence of plotting code alone is insufficient.

## Do not use this skill when

- The task is plotting syntax, debugging, code organization, report plumbing or rerunning an unchanged analysis without a visual-design decision.
- The user asks to implement a decision-complete set of visual specifications mechanically and does not want those choices reconsidered or evaluated.
- The user wants statistical analysis design with no visual artifact or visual decision.
- The request is prose-only writing feedback with no figure, table, diagram, or visual-output concern.

## Core workflow

1. Check that the current request requires choosing or judging a visual display; reassess when the task changes.
2. Name the figure job: comparison, distribution, relationship, composition, process/overview, exact lookup, image evidence, or publication export.
3. Identify missing context that changes the recommendation: data type, `n`, independent unit, audience, medium, venue constraints, legend, or actual figure/image.
4. Inspect the actual figure before making exact layout, palette, microscopy, or graphical-abstract claims; if it is unavailable, state the recommendation as conditional.
5. Route to the narrowest reference file, then diagnose the highest-risk failure before polishing style.
6. Give the requested recommendation or critique, explaining the consequential change and why it helps the reader. Prioritize findings when several compete; distinguish inspected findings from assumptions and unperformed checks. Use the supplied context and ask only for missing details that could change the result.

## Reference routing

- Open `references/chart-selection.md` for chart family, raw-pattern visibility, bar/line alternatives, tables, and ordinary plot selection.
- Open `references/statistics-and-uncertainty.md` for effect sizes, intervals, p-values, replicate structure, overplotting, outliers, and small-n displays.
- Open `references/color-and-accessibility.md` for palettes, grayscale/color-vision checks, redundant encodings, and semantic color use.
- Open `references/specialized-figures.md` for heatmaps, networks, genome tracks, set intersections, temporal/dense data, matrices, and 3D displays.
- Open `references/biological-images.md` for microscopy, image panels, scale bars, channels, insets, annotations, and image-analysis workflow reporting.
- Open `references/layout-and-typography.md` for multi-panel hierarchy, labels, legends, axes, callouts, salience, spacing, typography, and final-size readability.
- Open `references/conceptual-figures.md` for graphical abstracts, overview figures, mechanism diagrams, pathways, neural-circuit diagrams, arrows, and schematic grammar.
- Open `references/publication-technical-requirements.md` for manuscript, poster, slide, preprint, raster/vector, font, resolution, color-mode, and venue-specific checks.
- Open `references/handbook-access.md` when a fuller explanation or worked example would help with the current task. Inspect the actual image or rendered HTML when judging visual appearance.

## Output formats

Select only the format that fits the requested deliverable; these are patterns, not mandatory response sections.

- `Figure critique`: prioritize evidence-job mismatch, hidden data or inference risks before cosmetic changes; include only relevant accessibility, layout and export findings.
- `Redesign plan`: recommended form, encodings, layout changes, caveats, and required context.
- `Publication-readiness pass`: ready/needs revision/blocked status with must-fix items and venue assumptions.
- `Before/after guidance`: concise contrast between the current design and the stronger alternative.

## Quick checklist

Apply only the checks relevant to the requested scope and artifact. Inspect supplied context first; treat `identify` or `clarify` as analysis when the answer is already available, and ask only for missing information that could change the result.

- Does the visual form match the scientific task and data structure?
- Are raw observations, sample size, spread, uncertainty, independent units, and outliers visible when they affect interpretation?
- Does color encode meaning accessibly, with redundant cues where needed?
- Are image scale, channel identity, annotations, and analysis workflow clear when images support the claim?
- Do layout, labels, axes, typography, and export settings work at final size?

## Common pitfalls

- Recommending a prettier chart before naming the figure job.
- Confusing source-code layout with visual layout, or report-generation structure with page composition.
- Hiding continuous or small-n data behind mean-only bars or lines.
- Treating p values, stars, or summary statistics as the visual evidence.
- Using diverging heatmap colors without a meaningful midpoint.
- Inferring image scale, channel meaning, palette accuracy, or exact layout quality without inspecting the actual figure.
- Guessing current journal requirements instead of asking for or checking the venue instructions.

## Quality bar

- Give specific, executable figure advice, not taste-level comments.
- Separate confirmed visual findings from conditional guidance and missing context.
- Treat accessibility, uncertainty, replicate structure, and final-size legibility as core checks.
