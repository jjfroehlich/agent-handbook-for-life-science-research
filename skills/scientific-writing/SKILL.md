---
name: scientific-writing
description: "Draft or revise manuscripts, abstracts, figure legends, thesis chapters, and scientific arguments for readers. Exclude technical documentation, grant writing, and publication-process strategy."
license: MIT
metadata:
  author: jjfroehlich
  version: "0.1.1"
---

# Scientific Writing

## Purpose

Help draft, diagnose, and revise scientific writing so the reader can see the claim, evidence, caveats, and section logic without losing scientific accuracy.

## Use this skill when

- First classify the requested artifact and output: continue only when audience-facing scientific prose or argument is primary, not merely because a technical document discusses science.
- The user provides scientific prose and asks for a rewrite, critique, outline, or readiness check.
- The artifact is an abstract, introduction, results paragraph, discussion, conclusion, figure legend, thesis chapter, author contribution statement, or acknowledgement.
- The user asks for clearer flow, a sharper gap or claim, less overclaiming, better section structure, or manuscript-ready wording.
- The request needs a concrete edited artifact, not only general advice.

## Do not use this skill when

- The request concerns computational or analysis plans, pipeline or implementation documentation, README files, code comments, object names, variable names, or terminology inside scripts without a primary audience-facing scientific argument.
- The request is mainly journal selection, submission logistics, peer-review strategy, grant writing, slide design, poster layout, or literature synthesis without a writing deliverable.
- The user asks for statistical analysis, code, figure generation, or experimental design rather than prose revision.
- Authorship questions require institutional, legal, or policy determinations beyond wording and documentation guidance.

## Core workflow

1. Match the intervention to the request. For local wording or compression, edit from the supplied prose and constraints; for structural review, establish the artifact, audience, claim, and evidence boundary. Ask only for missing context that changes the work.
2. Diagnose section or paragraph function when the problem is structural; do not require a structural diagnosis for a settled local edit.
3. Decide the intervention level before rewriting:
   - Structure: missing claim, wrong section job, chronology instead of reader logic, overloaded paragraph, or weak transition.
   - Rhetoric: missing gap, result, implication, limitation, comparison, or contribution.
   - Sentence: hidden actor, noun stack, vague verb, unstable term, overlong modifier chain, or overclaim.
4. For whole-manuscript or thesis-chapter review, trace the question, evidence, finding, conclusion, and limits. For an excerpt, check only the claims it makes.
5. Consult a reference or checklist when its section-specific guidance would improve the requested revision.
6. Preserve meaning, uncertainty, statistical direction, actor, scope, caveats, and terminology while tightening language. Add facts only from supplied evidence; flag consequential omissions or use explicit placeholders. A smoother story cannot replace a missing control or unsupported inference.
7. Return a concrete output: revised text, section outline, prioritized revision plan, checklist review, or before/after diagnosis.

## Output formats

Select only the format that fits the requested deliverable; these are patterns, not mandatory response sections.

- `Diagnosis + rewrite`: brief problem statement, revised prose, and rationale for key changes.
- `Section plan`: ordered rhetorical moves with one-sentence job for each paragraph or subsection.
- `Readiness review`: prioritized findings, required fixes and unresolved checks with their evidence limits.
- `Compression pass`: what to cut, combine, or move while preserving the claim.
- `Contribution wording`: careful authorship, contribution, or acknowledgement language with caveats.

## Reference routing

- Open `references/abstracts.md` for abstracts, summaries, graphical-abstract text, or compressed paper descriptions.
- Open `references/introductions.md` for gap, significance, aim, scope, or field-context problems.
- Open `references/results-sections.md` for results paragraphs, figure callouts, finding-first structure, or interpretation leakage.
- Open `references/discussions.md` for interpretation, limitations, implications, conclusions, and overclaim control.
- Open `references/figure-legends.md` for figure captions, panel logic, labels, statistics, and self-contained legends.
- Open `references/paper-structure.md` for whole-manuscript flow, central contribution, titles/headings, paragraph order, chronology-to-reader-logic problems, and style diagnostics.
- Open `references/thesis-writing.md` for thesis/dissertation chapters and institution-sensitive structure.
- Open `references/authorship-and-contributions.md` for contribution statements, acknowledgements, or authorship-sensitive wording.
- Open `references/handbook-access.md` when a fuller explanation or worked example would help with the current task.

## Quick checklist

Apply only the checks relevant to the requested scope and artifact. Inspect supplied context first; treat `identify` or `clarify` as analysis when the answer is already available, and ask only for missing information that could change the result.

- What is the one main contribution or question?
- Does the section do its specific job, or is it borrowing another section's job?
- Can a reader identify the gap, method or approach, evidence, interpretation, and caveats?
- Can each main result be traced to a question, figure/table, comparison, and bounded local conclusion?
- Are claims calibrated to the supplied evidence?
- Is the draft organized around reader logic rather than the order in which the work happened?
- Are important terms searchable and stable, especially in abstracts, titles, figure legends, and contribution statements?
- Does the rewrite keep the author's scientific meaning, comparison, quantity, actor, scope, and uncertainty while reducing friction?

## Common pitfalls

- Polishing vague prose before fixing the argument.
- Reordering prose around research chronology rather than reader logic.
- Turning results into discussion or discussion into a second results section.
- Replacing accurate uncertainty with confident overstatement.
- Cutting searchable method, system, comparison, or result terms during compression.
- Treating acknowledgements as hidden authorship credit or contribution statements as praise.
- Applying abstract or introduction patterns to every section.

## Quality bar

The answer should be section-specific, concrete, and conservative with evidence. It should improve reader orientation, preserve uncertainty, avoid generic writing advice, and return usable prose or a prioritized plan unless the user asked only for diagnosis.
