# Abstracts

Use this when the user is drafting, compressing, diagnosing, or revising an abstract or brief paper summary.

## The job of this topic

An abstract is a standalone miniature argument. It must orient the reader, identify the problem or gap, state what was done, report the central result, and explain why the result matters within the available word limit.

## Default workflow

1. Identify venue constraints: word limit, structured headings, audience breadth, and whether the abstract is for a research, methods, review, or thesis artifact.
2. Extract the paper's core claim in one sentence before editing.
3. Label each sentence by move: broad problem, needed context, specific gap or aim, approach, central result or method capability, evidence, and so what.
4. Decide which move is currently missing, duplicated, or overgrown. Do not edit sentence by sentence until the move map is visible.
5. Cut generic field openings, unnecessary citations, duplicated background, routine method detail, and unsupported implications.
6. Preserve searchable specificity: method names, key system terms, validation evidence, and concrete result language should not be cut just to make the abstract shorter.
7. Rewrite for reader sequence: problem before approach, approach before result, result before implication.
8. Run the recoverability test: a reader should be able to infer why the work was needed, what was done, what changed, and why the change matters.
9. Recheck that every claim in the abstract is supported by the draft or supplied evidence.

## Decision rules

- If the first sentence could introduce many papers, replace it with a sharper problem, tension, or knowledge gap.
- If the abstract names the method but not what it enables, add the capability or validation result.
- If the abstract is for a methods, tool, dataset, or resource paper, give more space to the unmet need, primary innovation, capability, validation, and use case than to downstream biological findings.
- If the abstract lists result bullets in project order, select the highest-level finding and make the method-result relationship reconstructable.
- If the abstract reports results without a setup, add the minimum context needed to understand why the result matters.
- If the abstract ends with broad impact language, tie it to the actual evidence or reduce the claim.
- If the venue requires structured headings, keep the headings but still make each section complete a rhetorical move.
- If a brevity pass removes searchable detail, cut lower-value background before cutting the method name, system, comparison, or central result.
- If the abstract is only 80-100 words, keep the problem, contribution, one evidence anchor, and implication; remove methodological decoration first.
- If the abstract is a Nature-style summary paragraph, use a broad-to-specific-to-broad arc: accessible context, precise problem, main result, relation to prior knowledge, and broader perspective.

## Variants and edge cases

- Methods abstracts should foreground the unmet methodological need, the capability introduced, validation evidence, and the scientific use case.
- Very short abstracts still need a complete spare story: problem, contribution, evidence, implication.
- Broad summary paragraphs can use a broad-to-specific-to-broad arc: accessible field context, precise problem, main result, comparison to prior knowledge, and broader perspective.
- Broad-audience abstracts need less jargon and more context, but they still need a specific result or contribution.
- Conference abstracts may compress methods and limitations, but should not omit the main result.
- Thesis abstracts can include more scope and chapter-level framing than a paper abstract, but should still avoid a table-of-contents tone.

## Anti-patterns

- Opening with a textbook definition instead of the paper's problem.
- Spending most of the word budget on background.
- Ending with "may have implications" without naming the supported implication.
- Listing techniques without saying what they revealed.
- Introducing abbreviations or jargon that are not needed inside the abstract.
- Treating the abstract as a table of contents instead of a compressed argument.

## Diagnostic questions

- Can a reader answer Why, What gap, How, What found, and So what?
- Can the study logic be reconstructed from the abstract alone?
- Which sentence contains the main result or contribution?
- Does every sentence earn its word budget?
- Are limitations or uncertainty represented without burying the result?
- Would the abstract still make sense without the title?

## Output patterns / mini-templates

- Research abstract: `Broad problem. Needed context. Specific gap or question. Approach in one sentence. Central result with direction or magnitude when available. Interpretation or implication bounded by evidence.`
- Methods abstract: `Unmet need. Method name and primary innovation. What the method/tool/resource does. Validation or benchmark. What it enables users to ask or measure. Boundary or availability detail if relevant.`
- Compression note: `Cut [background/method detail/duplicated implication]; combine [context + gap]; preserve [main result + caveat].`
- Diagnostic map: `Move present? Problem [yes/no]. Gap [yes/no]. Approach [yes/no]. Result/capability [yes/no]. Evidence [yes/no]. So what [yes/no].`
- Searchability pass: `Preserve [method/system/comparison/result term]; cut [generic setup/citation phrase/duplicated caveat].`
- Sentence-label review: `S1 [context/problem]; S2 [gap]; S3 [approach]; S4-S5 [selected findings]; final [bounded implication].`

## Examples

Each pair below is a fictional teaching case. Use the fixed facts stated for that pair; the sparse before sentences alone do not establish the added gap, design or outcome. If equivalent facts are absent from a user's material, preserve the known text and mark missing details.

Fixed facts: cell-type resolution of early developmental enhancer changes is unresolved; the study profiles enhancer-linked transcription across staged samples and finds recurrent regulatory shifts at early lineage transitions.

Before: `Many studies have investigated gene regulation in development. We used sequencing to examine enhancer activity.`

After: `How enhancer activity changes across early development remains difficult to resolve at cell-type resolution. We profiled enhancer-linked transcription across staged samples and found that early lineage transitions are marked by a small set of recurrent regulatory shifts.`

Fixed facts: CellMark combines local intensity cues with shape priors to segment touching cells; three benchmark datasets show improved instance recovery and preserved cell-size estimates in dense microscopy images.

Before: `Here we present a new computational method and show that it works better than existing tools.`

After: `Accurately separating touching cells remains a bottleneck in dense microscopy images. We developed CellMark, a boundary-aware segmentation method that combines local intensity cues with shape priors. Across three benchmark datasets, CellMark improved instance recovery while preserving cell-size estimates, enabling more reliable quantification in crowded tissues.`

Fixed facts: the unresolved question concerns transcriptional changes before age-related loss of vaccine responsiveness; immune-cell transcriptomes were profiled before and after vaccination in younger and older adults; a pre-existing inflammatory program predicted weaker response. The design supports association.

Before: `This study investigated immune aging using transcriptomics and found many changes.`

After: `Which transcriptional changes precede age-related loss of vaccine responsiveness remains unclear. We profiled immune-cell transcriptomes before and after vaccination in younger and older adults and found that a pre-existing inflammatory program predicted weaker response. These results identify an early molecular state associated with reduced vaccine responsiveness in aging.`

## When not to apply this

Do not use this as the main playbook for full introductions, discussions, or figure legends; route those sections to their own reference files.
