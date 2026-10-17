# Results Sections

Use this when the user is revising results text, figure callouts, finding-first paragraphs, subsection order, or text that drifts into discussion.

## The job of this topic

Results sections present what was found and how the evidence supports it. Orient the reader to the question, finding and necessary evidence. In separate sections, keep broader implications in Discussion; local explanation and inference limits can belong beside the result. Follow the actual venue or thesis requirements. In a combined Results/Discussion, make the transition from observation to interpretation visible.

## Default workflow

1. Identify the result, hypothesis, prediction, or figure each paragraph is supposed to convey.
2. Put the finding or question near the paragraph opening.
3. Name the comparison, direction, magnitude or qualitative pattern, system, evidence type, sample or replicate context, and figure/table location when available.
4. Supply question or context, minimal approach, result, supporting detail and local conclusion where needed. Skip established context; one figure need not equal one paragraph, and not every paragraph needs every component.
5. Include only methodological detail needed to interpret the result; leave reproducibility detail in Methods.
6. Give null, negative, conflicting or inconclusive findings the weight they deserve for the question and claim. Retain contrary evidence even when it complicates the preferred story; distinguish an uncertain estimate from evidence of negligible change.
7. Move broad implications, speculation and future work to Discussion when they interrupt reporting. Retain limitations needed to understand the measurement, comparison or uncertainty, including those that constrain the reported finding.
8. Check that figure references appear near the relevant claim and in a useful order.

## Decision rules

- If the paragraph starts with irrelevant method chronology, orient it to the question or supported finding; retain setup needed to understand a complex or inconclusive comparison.
- If the result is vague, add direction, comparator, effect size, sample context, or qualitative pattern from the supplied material.
- If the paragraph makes a broad implication, place it according to the section's job. Retain supported local explanation or a limit needed to interpret this comparison; do not mechanically remove all interpretation.
- If a figure is cited without explaining what panel supports, add panel-specific orientation.
- If multiple results compete in one paragraph, split by finding or combine under a stronger topic sentence.
- If chronology obscures the scientific logic, recover the question and reorder accordingly. Chronological order can work when it explains a real dependency.
- If a statistical result lacks direction or comparator, add the missing comparison from the supplied material or flag it as needed.
- If the paragraph contains only technique names, recover the tested question and the finding each technique supports.
- If the paragraph cites a figure before telling the reader what to look for, add a finding or orientation phrase before the citation.
- If a result was expected from a hypothesis or prediction, show that link explicitly before reporting the evidence.
- If a paragraph contains values without a takeaway, add a local conclusion that does not drift into broad discussion.

## Variants and edge cases

- Exploratory results can be presented as patterns without causal language.
- Negative or null results still need the tested comparison and interpretation boundary.
- Complex multi-panel figures may need a short orientation sentence before the finding.
- Methods-heavy results need enough local explanation to make the finding assessable. A methods paper can integrate development and results where its format permits; keep full reproducibility details accessible.
- If binding instructions require reporting-only Results, relocate supported interpretation as required. Moving an unsupported mechanism or calibration explanation to Discussion does not make it supported.

## Anti-patterns

- "We next performed..." repeated as the main paragraph structure.
- Hiding the finding after a long method setup.
- Reporting only statistical significance without biological direction or meaning.
- Using causal verbs when the design supports association only.
- Repeating generic limitations in every paragraph, or removing a local limitation that changes what the result supports.

## Diagnostic questions

- What is the finding in this paragraph?
- What question, hypothesis, or prediction does it answer?
- What comparison or condition produced it?
- Which figure, table, or evidence supports it?
- Are direction, magnitude or pattern, uncertainty, and sample context clear enough from the supplied material?
- Does the paragraph state enough detail to understand the result without overloading the reader?
- Which sentences are necessary local explanation, and which make broader claims that belong elsewhere under this format?

## Output patterns / mini-templates

- Results paragraph: `To test/ask [question], we [minimal method]. [Finding] was [direction/pattern] in [condition]. This pattern was supported by [evidence/figure], indicating [local interpretation only if needed].`
- Hypothesis-linked result: `If [hypothesis], we expected [prediction]. In [comparison], [result direction/pattern] was observed ([evidence/figure]), supporting/refining/not supporting [local claim].`
- Results edit note: `Move [broad implication] to Discussion; keep [finding + evidence] in Results.`
- Figure-linked unit: `[Finding]. In Fig. [panel], [visual/evidence type] shows [comparison or pattern]. [Robustness/control/detail] supports [local conclusion].`
- Inconclusive-result unit: `We tested whether [question]. The estimate was [effect] with [uncertainty] under [conditions]. These data leave [scientifically relevant possibilities] unresolved.` State negligible change only when the design and analysis support that inference.
- Numeric-support prompt: `Add direction, comparator, estimate or magnitude, uncertainty/statistical support, and figure/table reference if supplied.`

## Examples

Illustrative fixed facts for the imaging pair: marker expression increased after treatment, the largest change occurred in late-stage cells, and Fig. 2B shows that comparison. The rewrite requires these facts in addition to the before sentence.

Before: `We performed imaging and then quantified marker expression.`

After: `Marker expression increased after treatment, with the largest change in the late-stage cells shown in Fig. 2B.`

Illustrative fixed facts for the RNA-seq pair: treated samples have increased cytokine-response gene expression relative to controls, and enrichment identifies interferon-associated programs. These findings are supplied for the example; no numerical estimates are available.

Before: `RNA-seq was performed, and several genes were differentially expressed. Pathway analysis was then conducted.`

After: `Treatment shifted the transcriptional response toward inflammatory signaling. Differential expression analysis identified increased cytokine-response genes in treated samples, and pathway enrichment concentrated these changes in interferon-associated programs.`

Without those fixed facts, retain the available result: `RNA-seq identified differentially expressed genes, which we then examined by pathway analysis.` Flag direction, comparator and enrichment outcome as missing rather than inventing them.

## When not to apply this

For a broader conclusion, study-wide limitations or field implications, consult `discussions.md`. Keep measurement and inference limits needed to understand the reported finding alongside it.
