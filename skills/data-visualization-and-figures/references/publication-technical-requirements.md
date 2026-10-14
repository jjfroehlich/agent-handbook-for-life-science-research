# Prepare and verify the delivered figure

Read this for export, final sizing or a change of medium. Use the supplied destination requirements; verify current venue instructions when needed rather than treating archived recipes as current rules. When the venue is unknown, state assumptions and identify only the checks that remain material.

## Design for the actual medium

Test manuscript figures at final column/page width, posters at their reading distance and slides at projected viewing size. A slide often needs fewer simultaneous claims and larger labels than a manuscript figure. A narrated slide can rely on spoken context that a standalone figure cannot. Splitting a dense figure can preserve its comparison better than shrinking everything. Check scale bars and annotations after assembly and resizing.

Inspect the exported file itself: text, glyphs, lines, transparency, legends, image details, panel associations and clipping. A source file that looks correct does not establish a correct PDF or raster export. State which outputs were actually opened and inspected; leave unperformed checks explicit.

## Match format to content

Vectors preserve editable geometry and scale well for text, lines and diagrams. Dense plots can become unwieldy as vectors; an appropriately rasterized data layer with vector labels can be useful. Image panels remain raster evidence even inside a vector container. Check effective resolution at final size; resampling or wrapping a low-resolution image in PDF does not restore missing detail.

Lossless raster formats preserve sharp boundaries well. Lossy compression can introduce artifacts, especially around text and lines; judge the actual output and destination requirements. Embed fonts where supported and verify glyph rendering. Outlined text can preserve appearance in some workflows but loses normal text editability/searchability; retain the editable master. Verify required color mode and transparency handling rather than making RGB, CMYK or flattening universal defaults.

## Preserve a reliable revision path

Separate data transformations from styling. Keep the data/version, plotting code or editable source, relevant settings and export dimensions sufficient to regenerate or revise the figure. Automate recurring preparation where it helps. Manual finishing and drawn schematics can be legitimate when their edits are recorded and the scientific content remains traceable.

Exact jitter or other random placement additionally needs controlled random state and compatible software; analytical reproducibility does not automatically imply identical pixels. Record consequential exclusions, transformations and image processing. Never overwrite quantitative image inputs with presentation edits.

Changed condition: a recurring numerical plot benefits from scripted regeneration as data change. A carefully recorded hand-finished schematic can be appropriate for a different task. Choose tools for the work instead of requiring one software workflow or manual polishing of every figure.

Deliver the requested artifact with a concise account of consequential design choices, validation actually performed and material limitations. Export checks complement scientific review; they do not certify the analysis or the truth of the visual claim.
