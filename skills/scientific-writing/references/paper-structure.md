# Paper Structure

Use this when the user asks for whole-manuscript flow, section order, title or heading logic, paragraph organization, or a structural diagnosis before rewriting.

## The job of this topic

Paper structure turns a set of analyses into a readable argument. The reader should be able to identify the central contribution, see why each section exists, and follow the movement from motivation to evidence to interpretation.

## Default workflow

1. State the one main contribution or organizing question; if there are several, name the bridge that makes them one paper, chapter, or review.
2. List the section jobs: abstract summarizes the whole story, introduction motivates and narrows, methods enable reproducibility, results present findings, discussion interprets, figures provide evidence, and legends make visuals self-contained.
3. Build the evidence spine: each major result should answer a subquestion or test a prediction that advances the central contribution.
4. Check whether the current order follows reader logic rather than lab chronology.
5. Audit headings, topic sentences, figure titles, and panel order for argumentative progress; convert method labels to result-bearing labels when evidence supports that.
6. Use context-content-conclusion where it clarifies the argument: orient the reader, deliver new content and make the inference recoverable. Do not require all three moves explicitly in every paragraph or repeat a conclusion the passage already makes clear.
7. Check paragraph mechanics: topic sentence, support and necessary detail. Add a closing inference or transition when the reasoning needs one. Split competing lines of reasoning; keep related moves together when they explain one point.
8. Move details that interrupt the main story into methods, supplement, appendix, or a later explanatory paragraph.
9. Only after structure is sound, tighten sentence-level style by recovering base clauses, unpacking noun stacks, and making parallel evidence grammatically parallel.

## Decision rules

- If the paper is a list of analyses, group them under one question and order them by the logic of the claim.
- If a paragraph switches between unrelated points or misplaced section functions, split it or move the misplaced material; retain connected question, evidence and interpretation when they develop one point.
- If results are organized by when the work happened, reorder around hypotheses, predictions, questions, or claims.
- If headings are method labels, consider result-bearing headings unless that would overclaim or violate venue norms.
- If multiple related findings use different syntax, use parallel form so the reader sees conceptual differences rather than grammatical noise.
- If the introduction or discussion contains detailed methods, move the reproducibility detail to methods and keep only orientation.
- If sentence-level edits make the prose smoother but leave the reader confused about the claim, prioritize structural revision.
- If a style rule would cut necessary precision, keep the precision and improve placement, order, or base-clause clarity instead.
- If the title states a topic rather than a result, test whether a result-stating title is accurate, short, and supported.
- If a figure or table has no clear role in the argument, revise its purpose or move it to supporting material. Descriptive resources, workflows and summaries can have a main-text role without a finding-stating title.
- If the paper has a writing-process problem, separate drafting order from final reader order; it is acceptable to draft results first while presenting context first.
- If coauthor sections feel stitched together, impose a shared outline with one-sentence paragraph jobs before editing prose.

## Variants and edge cases

- Review articles may organize around a conceptual question rather than one new result.
- Tool or resource papers should make the use case and validation logic visible early.
- Thesis chapters may require broader field framing and institution-specific structure.
- Multi-author manuscripts often need a stronger shared outline because sections may otherwise reflect different local priorities.
- Methods, tool, or resource papers should expose use case and validation logic early, not only biological downstream observations.
- When the user's problem is getting started, use storyboards, figure-first drafting, timed drafting, or coauthor checkpoints as process scaffolds, then return to section and evidence checks.

## Anti-patterns

- Chronological storytelling of the project instead of reader-centered argument.
- Every result presented with equal weight.
- Important findings buried at the end of paragraphs.
- Vague topic sentences such as "We next examined..." when a result statement is possible.
- Mechanical style edits that remove nuance or change scientific meaning.
- Vague verbs such as studied, investigated, modulated, or assessed when the actual action, direction, or comparison can be named.
- Treating a productivity tactic as a substitute for deciding the claim, evidence spine, or section jobs.

## Diagnostic questions

- What is the one sentence version of the paper's contribution?
- What does each section do that no other section should do?
- Can the reader scan headings, topic sentences, and figure titles and recover the story?
- Which figure or table carries each major claim?
- Does each paragraph develop a coherent point, with connected moves and a recoverable inference where needed?
- Which details are necessary in the main text, and which belong elsewhere?
- Where does the draft over-explain, under-explain, or repeat itself?
- Which sentence edits risk changing uncertainty, comparison, or scope?

## Output patterns / mini-templates

- Structural diagnosis: `Main claim: ... Reader blockage: ... Section-level fix: ... Sentence-level fix after structure: ...`
- Paragraph job labels: `Context -> gap -> result -> evidence -> interpretation -> limitation -> transition.`
- Results unit: `Context -> approach -> result -> detail/robustness -> local conclusion.`
- Heading revision: `Method label: "Analysis of X" -> result-bearing label: "X increases under Y condition"` when evidence supports it.
- Sentence repair: recover the base clause first, then add only modifiers needed for scientific accuracy.
- Evidence spine: `Question -> Figure/table -> finding -> support -> local conclusion -> next question.`
- Manuscript triage: `Keep in main text / move to methods / move to supplement / cut / reserve for discussion.`
- Hypothesis-linked outline: `Question -> prediction -> comparison -> result -> figure/table -> interpretation boundary.`
- Sentence repair pass: `Base clause -> necessary modifiers -> comparison/quantity -> caveat -> rhythm.`
- Coauthor alignment note: `Section job: ... Required claim: ... Required evidence: ... Details to move: ...`

## Examples

Illustrative fixed facts for the first three pairs: the question is whether treatment changes cell-state composition; single-cell sequencing compares treated and control samples and shows an expanded inflammatory population, which motivates subsequent cytokine-response gene analysis. Independent assays A and B consistently show increased X under condition Y; assay A establishes direction and assay B localizes it to that cell state. These are fictional supplied inputs, not findings recovered from the sparse before sentences.

Before: `We performed assay A. We then performed assay B. Finally, we analyzed the data.`

After: `Condition Y consistently increased X across two independent assays. Assay A showed the direction of the effect, and assay B localized it to the relevant cell state.`

Before: `Analysis of cell states`

After: `Treatment enriches the inflammatory cell state`

Why it works: the revised heading tells readers what claim the section will support rather than naming only the analysis type.

Before: `First, samples were collected. Then we ran sequencing. Then we compared the groups.`

After: `To test whether treatment shifted cell-state composition, we profiled control and treated samples by single-cell sequencing. Treated samples showed an increased inflammatory population, motivating a focused comparison of cytokine-response genes.`

Before: `The measurement of differences in the expression values between the treatment and control conditions was carried out for the analysis of pathway activation.`

After: `We compared expression between treatment and control samples to estimate pathway activation.`

Why it works: the revised sentence restores actor, action, comparison, and purpose before adding modifiers.

When no findings are supplied:

Before: `We performed assay A. We then performed assay B. Finally, we analyzed the data.`

After: `We analyzed data from assays A and B.`

Needed for a claim-bearing revision: the tested question, the role of each assay and the observed finding. Do not infer agreement, direction or cell state from assay chronology.

## When not to apply this

Do not use this playbook as a substitute for venue instructions, journal formatting, or statistical review.
