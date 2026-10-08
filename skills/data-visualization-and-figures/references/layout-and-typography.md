# Layout And Typography

Use this for multi-panel layout, visual hierarchy, panel order, labels, callouts, legends, axes, ticks, gridlines, negative space, salience, typography, line weights, and final-size readability.

## Use this when...

- The figure has multiple panels, crowded labels, inconsistent typography, confusing legends, or weak reading order.
- The user asks how to make a figure easier to scan or fit final size.
- The visual form is basically correct but the presentation blocks interpretation.

## The job of this topic

Guide the reader through the scientific argument with order, grouping, proportion, and legible labels.

## Default workflow

1. State the main claim and arrange panels so reading order supports it.
2. Group related panels by proximity, alignment, shared axes, labels, or enclosing structure.
3. Use salience deliberately so the most important comparison is visually prominent.
4. Put labels, legends, and callouts close to what they explain.
5. Remove decorative or redundant marks that compete with data-bearing marks.
6. Use negative space to separate conceptual groups.
7. Test text, symbols, lines, axes, legends, and annotations at final display size.

## Decision rules

- Align repeated panels and axes when comparison requires it.
- Keep panel labels consistent and place them where readers scan first.
- Prefer direct labels over distant legends when space allows.
- Use arrows only for direction, sequence, causality, or a clearly marked feature.
- Keep font family, weight, and size consistent unless hierarchy requires a deliberate contrast.
- Make every label reduce interpretation effort at final size.
- Use gridlines and ticks as context, not decoration.

## Variants and edge cases

- Manuscript figures: preserve compactness but test at final column or page width.
- Posters: increase hierarchy and distance readability; reduce small-multiple density.
- Slides: split dense manuscript figures and enlarge the key comparison.
- Dense annotations: move explanatory text to the legend or use numbered callouts.

## Anti-patterns

- Equal visual weight for primary and secondary information.
- Labels floating far from their marks.
- Legends that require memorization across panels.
- Inconsistent font sizes, symbols, or line weights across panels.
- Polishing alignment before fixing misleading chart choice or missing image scale.

## Diagnostic questions

- Where does the eye go first, second, and third?
- Does the visual order match the scientific argument?
- Which element is visually loud but scientifically minor?
- What becomes unreadable when the figure is reduced?
- Can labels, legends, and annotations be understood without hunting?

## Output patterns / mini-templates

```text
Layout priority: <change>.
Move/group: <elements>.
Why: <reading-order or comparison rationale>.
Reduce: <noise or redundant mark>.
Final-size test: <text/symbol/line/legend check>.
```

## Examples

- `Crowded legend`: replace with direct labels for key categories and move secondary details to the caption.
- `Four-panel figure with unclear order`: align panels in the order the claim is introduced. Use whitespace to separate distinct comparisons while keeping each result beside its required control.

## When not to apply this

Do not optimize layout and typography before fixing hidden uncertainty, misleading chart type, inaccessible color, or missing image metadata.
