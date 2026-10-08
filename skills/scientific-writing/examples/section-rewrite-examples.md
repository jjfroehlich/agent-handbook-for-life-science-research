# Section Rewrite Examples

These are fictional teaching cases. Each pair has explicit fixed facts; the rewrite may use those facts but must not infer them from a sparse before sentence. In real edits, use only supplied evidence or explicit placeholders. These examples supply no facts about the user's study.

## Abstract Opening

Fixed facts: the literature supplied for this case studies tumors mainly after dissemination, leaving the transcriptional changes before metastatic transition unresolved.

Before: `Cancer progression involves many transcriptional changes, and several studies have examined this process.`

After: `Which transcriptional changes precede metastatic transition remains unclear because most studies profile tumors after dissemination.`

Why it works: the rewrite replaces generic field background with a specific unresolved problem.

Pattern: `Generic field fact -> specific unresolved problem + reason prior work is insufficient.`

## Results Paragraph

Fixed facts: treated samples have increased cytokine-response genes relative to controls; enrichment supports inflammatory signaling. No estimates or uncertainty are supplied, so quantitative detail remains unresolved.

Before: `We performed RNA-seq and found many genes changed. We then looked at pathway enrichment.`

After: `Treatment increased cytokine-response gene expression relative to controls. Pathway enrichment supported a shift toward inflammatory signaling.`

Why it works: the rewrite states the finding first, then gives the evidence type.

Pattern: `Method chronology -> finding + comparison + evidence.`

## Methods Abstract

Fixed facts: low-contrast images make touching cells hard to segment; CellMark uses boundary prediction with intensity-aware watershed refinement; three benchmark datasets show improved instance recovery and preserved cell-size estimates. This is a distinct fictional method case, not the shape-prior case in the abstract reference.

Before: `We developed a tool for image analysis and tested it on several datasets.`

After: `Segmenting densely packed cells remains difficult in low-contrast microscopy images. We developed CellMark, an image-analysis method that separates touching cells by combining boundary prediction with intensity-aware watershed refinement. Across three benchmark datasets, CellMark improved instance recovery while preserving cell-size estimates.`

Why it works: the rewrite names the unmet need, method, primary innovation, validation, and capability.

Pattern: `Tool exists -> unmet need + method name + innovation + validation + user value.`

## Introduction Gap

Fixed facts: prior literature links immune aging to chronic inflammation but leaves the timing of transcriptional changes before lost vaccine responsiveness unresolved.

Before: `Many researchers have studied immune aging, but more work is needed.`

After: `Although immune aging has been linked to chronic inflammation, it remains unclear which early transcriptional changes precede the loss of vaccine responsiveness in older adults.`

Why it works: the rewrite replaces a generic gap with what is known, what remains unknown, and the consequence.

## Discussion Overclaim

Fixed facts: the study supports a pathway role in the tested model; direct perturbation evidence in vivo is absent. Clinical transformation has not been tested.

Before: `These findings prove that this pathway controls disease progression and will transform treatment.`

After: `These findings support a role for this pathway in the model system tested here and motivate direct perturbation studies to determine whether it contributes to disease progression in vivo.`

Why it works: the rewrite preserves importance while restoring evidence boundaries.

Pattern: `Proof/transform language -> supported role + tested context + next evidence needed.`

## Figure Legend

Fixed facts: panel A contains control and treated images; panel B quantifies marker-positive cells; treatment increases marker-positive cells. Replication and statistical-test details are absent and must be supplied before finalization.

Before: `Figure 3. Quantification of cells.`

After: `Figure 3. Treatment increases marker-positive cells. (A) Representative images of control and treated samples. (B) Quantification of marker-positive cells across the indicated conditions.`

Why it works: the rewrite names the comparison and maps the panels.

## Acknowledgement

Fixed facts: the fictional person Sam advised on design and commented on a draft; permission to name them is established.

Before: `We thank Sam for helping with everything.`

After: `We thank Sam for advice on experimental design and comments on an earlier manuscript draft.`

Why it works: the rewrite names concrete support without implying authorship eligibility.

## Sentence Base Clause

Fixed facts: normalized expression was compared across treatment groups to estimate pathway activity differences.

Before: `The implementation of the comparison of the normalized expression measurements across the treatment groups was performed to determine pathway activity differences.`

After: `We compared normalized expression across treatment groups to estimate pathway activity differences.`

Why it works: the rewrite recovers the actor and action, removes noun stacking, and preserves the scientific comparison.

Pattern: `Nominalization stack -> actor + verb + object + purpose.`

## Limitation Boundary

Fixed facts: an observed association comes from one cohort; no independent population validation is supplied.

Before: `A limitation is that we only used one cohort, so the findings need more study.`

After: `Because the analysis used one cohort, the results support the association in this sampling frame but do not establish whether the same pattern generalizes across populations.`

Why it works: the rewrite turns a vague apology into a boundary on interpretation.

Pattern: `Weakness list -> design boundary + supported claim + unsupported stronger claim.`

## Reader-Logic Reorder

Fixed facts: the question is whether treatment changes cell-state composition; quality-filtered single-cell profiles show an expanded inflammatory population in treated samples; cytokine-response analysis followed to examine that finding.

Before: `We collected samples, performed sequencing, filtered the data, and compared treated and untreated cells.`

After: `To test whether treatment changed cell-state composition, we compared single-cell profiles from treated and untreated samples after quality filtering. Treated samples showed an expanded inflammatory population, which motivated a focused analysis of cytokine-response genes.`

Why it works: the rewrite presents the question and finding rather than the order of work.

Pattern: `Work chronology -> question + minimal method + finding + next reason.`

## Hypothesis-Linked Result

Fixed facts: the pre-specified hypothesis predicts reduced migration in mutant cells; mutant cells cover less area than controls during the imaging interval. This assay supports a local migration phenotype, not an identified mechanism.

Before: `We measured migration in the mutant cells and then compared the images.`

After: `We predicted that mutant cells would migrate less than controls. Mutant cells covered a smaller area during the imaging interval, consistent with reduced migration under these assay conditions.`

Why it works: the rewrite connects hypothesis, prediction, comparison, result, and evidence boundary.

Pattern: `Hypothesis -> prediction -> comparison -> result -> bounded local conclusion.`

## Thesis Conclusion

Fixed facts: three chapters establish that early regulatory changes precede stable cell-state commitment in one model; primary tissue was not tested. The supplied local format permits a synthesis conclusion.

Before: `In conclusion, this thesis found several results and more work is needed.`

After: `Together, the three chapters show that early regulatory changes precede stable cell-state commitment in this model. The thesis contributes a staged view of this transition, while leaving open whether the same sequence occurs in primary tissue.`

Why it works: the rewrite synthesizes across chapters, states the contribution, and marks the evidence boundary.

Pattern: `Result list -> thesis-level answer + contribution + boundary.`

## Contribution Statement

Fixed facts: A.B. performed image analysis and reviewed the manuscript; C.D. supervised and edited the manuscript. The vague before sentence alone does not establish these roles.

Before: `A.B. helped with the project and C.D. supervised everything.`

After: `A.B. performed the image analysis and reviewed the manuscript. C.D. supervised the project and edited the manuscript.`

Why it works: the rewrite documents concrete roles instead of vague status.

Pattern: `Vague help/status -> concrete contribution verbs.`

## Missing Findings

Fixed facts: assays A and B were performed and their data analyzed. No tested question, effect direction or agreement is supplied.

Before: `We performed assay A. We then performed assay B. Finally, we analyzed the data.`

After: `We analyzed data from assays A and B.`

Revision note: `A finding-first paragraph needs [tested question], [observed result] and [which assay supports it].` Keep these as placeholders until evidence is available.
