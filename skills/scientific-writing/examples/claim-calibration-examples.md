# Claim Calibration Examples

Use these examples when the user needs wording that preserves importance without overstating evidence.

These are fictional closed cases. Each rewrite uses the fixed facts stated below; do not import their findings into a user's paper.

## Reporting checks when the claim depends on them

Use the relevant checks below for the supplied passage, not as a compulsory statistical audit of every edit. Report what was actually done; do not run a new analysis or fill missing methods to make prose look complete. Flag a consequential unresolved analysis question for appropriate review.

- **Design and units:** Before/after change may include time or practice effects. Name the actual comparison and independently sampled or assigned units; technical repeats and cells within one culture are not additional independent cultures. Naming a mixed model does not establish that dependence was handled correctly.
- **Extremes and associations:** Distinguish a verified measurement error from a genuine extreme observation. Report justified exclusions and relevant sensitivity checks actually performed; do not remove points to preserve significance. When an exclusion lacks support, state that unresolved problem without claiming the data have now been restored, retained or reanalyzed. A pooled association and an association within groups answer different questions. Neither an automatic robust method nor a visually persuasive trend resolves their assumptions.
- **Selection and testing:** Explain whether selection used information related to the tested quantity. Selection independent of the test statistic under the null can be valid; using the same data is not automatically invalid. Conversely, naming a split or bootstrap does not prove independence or valid inference. Preserve the actual selection and testing history rather than inventing a safeguard.
- **Exploration and comparison families:** Keep discovered patterns and later explanations distinct from predictions specified before observation. State the actual tested family and the adjustment, if any, with its assumptions; do not invent unperformed tests, prescribe one universal correction or diagnose misconduct from an incomplete account. Repeated observations or several methods alone do not settle an interpretation.
- **Precision and scientific meaning:** Preserve estimates, units, uncertainty and the design relevant to a meaningful effect. No fixed sample size proves adequacy, and observed power computed from the same result is not fresh confirmation. If the claim is negligible change, retain the actual scientific margin and supporting analysis rather than infer equivalence from nonsignificance.
- **Tests and P values:** Name the test actually performed when that detail is needed. A P value is not the probability the claim is true, its biological importance, a replication probability or a realized error rate. Do not report a tiny computed value as exact zero because a display rounded it; recover the available precision or a documented reporting bound, without inventing a cutoff.

## Model-system boundary

Fixed facts: experiments support a pathway role in one model system; patient-derived samples and patient outcomes were not measured.

Before: `These results prove that the pathway controls disease progression in patients.`

After: `These results support a role for the pathway in this model and motivate testing whether a related role is observed in patient-derived samples.`

Why it works: the rewrite keeps the finding important while limiting the claim to the tested system.

## Association versus mechanism

Fixed facts: Gene X expression covaries with inflammatory state in an observational dataset; no design or assumptions identifying a causal effect are supplied.

Before: `Gene X drives the inflammatory state.`

After: `Gene X expression is associated with the inflammatory state in this dataset. These observations do not establish that X drives the state change.`

Why it works: the rewrite separates observed association from causal mechanism.

A supplied causal design could change the warranted wording, but an intervention label alone would not establish its mechanism. Do not prescribe a new experiment merely to complete a writing edit.

## Essential evidence gap

Fixed facts: treated cells lose a marker, but cell viability was not measured. The draft attributes the loss to differentiation rather than cell death.

Before: `This treatment induces differentiation. Future work will confirm that cells remain viable.`

After: `Treatment reduced the marker signal. Because viability was not measured, these observations do not distinguish differentiation from loss of viable cells.`

Why it works: the missing measurement affects the present inference. Rephrasing it as an optional extension would conceal the gap; identify the discriminating evidence still needed.

## Comparing effects

Fixed facts: a response-versus-baseline test gives P=.03 in group A and P=.20 in group B. No between-group response contrast or effect estimates are supplied.

Before: `Only group A responded, showing that the response differs between groups.`

After: `The response-versus-baseline tests gave P=.03 in group A and P=.20 in group B. These separate tests do not establish a difference between the groups' responses.`

Flag the missing estimates and direct contrast rather than inventing them. If the supplied analysis instead estimates the between-group difference, report that contrast and its uncertainty. A nonsignificant direct contrast still does not prove equality.

## Uncertain change

Fixed facts: a reported mean difference is 2 units, with 95% CI −4 to 8 units. No equivalence margin or equivalence analysis is supplied.

Before: `The treatment had no effect.`

After: `The estimated mean difference was 2 units (95% CI −4 to 8). The interval includes no change and changes in either direction.`

Do not call the effect negligible without an appropriate scientific boundary and analysis. Preserve the actual units and comparator when supplied; this example's numbers are not defaults for a user's results.
