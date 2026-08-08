---
name: scientific-feedback
description: 'Use only for holistic, prioritized, multi-lens critique of audience-facing scientific communication or governance in a manuscript, thesis, talk, poster, grant, study proposal, research pitch, collaborator update, or lab-policy document: whether claims, evidence, design, story, and audience fit cohere and what to revise first. Do not trigger merely because a task involves science, planning documents, or review. Do not use for code review; checking R, Python, or other scripts against requirements; requirement-to-code traceability; or reviewing computational workflows, pipelines, preprocessing, statistical or model configurations, implementation, reproducibility, validation, run outputs, or technical documentation—even when planning documents describe scientific analyses. For mixed documents-and-code tasks, default to general technical review unless the user explicitly asks for critique of scientific claims, evidence, study design, and audience readiness independent of implementation.'
license: MIT
metadata:
  author: jjfroehlich
  version: "0.1.4"
---

# Scientific Feedback

## Purpose

Give integrated, prioritized feedback on audience-facing scientific communication by routing through the right domain lenses and returning one coherent revision path.

## Use this skill when

- The user asks to review, critique, sanity-check, or give feedback on an audience-facing scientific communication or governance artifact.
- The requested judgment genuinely spans at least two lenses: claims and writing, evidence and figures, study design and audience readiness, funding and feasibility, or lab policy and power-aware communication.
- The user wants reviewer-style, mentor-style, collaborator-style, committee-style, or quick-scan feedback.
- Multiple specialist perspectives may matter: writing, communication, figures, publishing, grants, literature synthesis, project strategy, or lab culture.

## Do not use this skill when

- The request is a single narrow production task, such as "rewrite this paragraph," "choose this chart," "draft a cover letter," or "format this slide."
- The user asks only for literature search, citation formatting, code debugging, statistical analysis, or institutional/legal/clinical determinations.
- Do not load this skill provisionally for code, scripts, notebooks, analysis outputs, computational or statistical workflows, data pipelines, model choices, technical plans or specifications, requirements documents, requirements-to-code traceability, run diagnostics, or technical documentation. This remains true when the work is scientific, when planning documents are present, and when the user asks for structured or prioritized critique.
- The artifact should clearly be handled by one domain lens without integration.

## Core workflow

1. Before loading references or adopting this workflow, verify both gates: the primary deliverable is audience-facing scientific communication or governance, and the requested critique needs at least two lenses. Otherwise use the narrow domain or general technical review directly.
2. Identify the artifact, audience, destination, deadline, relationship, and requested review depth.
3. State the inferred goal, feedback mode, and selected domain lenses before critiquing.
4. Ask only for missing context that would change priorities; otherwise proceed with explicit assumptions.
5. Apply the narrowest useful lenses, then integrate findings into one revision sequence.
6. Separate strengths, blocking issues, major revisions, secondary improvements, and optional polish.
7. Adapt tone to the relationship: reviewer, mentor, collaborator, supervisor, committee, or self-revision.
8. End with the next action: revise, cut, restructure, verify, collect missing evidence, rehearse, submit, or route to a specialist domain.

## Routing / specialist lenses

Use portable routing language. If the environment supports loading another skill, consult the named skill; otherwise apply the summarized lens.

- Apply the `scientific-writing` lens for manuscript prose, section function, argument structure, claim calibration, figure legends, and revision-ready wording.
- Apply the `scientific-communication` lens for talks, slides, posters, chalk talks, pitches, story, audience fit, delivery, and Q&A.
- Apply the `data-visualization-and-figures` lens for plots, tables, heatmaps, microscopy, graphical abstracts, visual hierarchy, accessibility, uncertainty display, and export readiness.
- Apply the `publishing-and-peer-review` lens for journal submission, peer-review reports, editor decisions, reviewer ethics, and response-to-reviewers strategy.
- Apply the `grant-writing` lens for proposals, specific aims, funder fit, significance/innovation/approach, feasibility, budget alignment, and reviewer-facing funding narratives.
- Apply the `literature-reading-and-synthesis` lens for paper reading, figure/table extraction, claim-evidence notes, synthesis matrices, and literature-tracking feedback.
- Apply the `research-strategy-and-project-design` lens only when the artifact raises a project-level question about research direction, hypotheses, experimental programs, decisive scientific tests, risk, or kill criteria. Do not use it merely to choose a pipeline or model configuration.
- Apply the `mentoring-management-and-lab-culture` lens for lab documents, mentoring compacts, IDP plans, feedback scripts, conflict diagnosis, lab culture, and power-aware management artifacts.

## Clarifying questions

Ask at most three, and only when the answer changes feedback priorities:

- What is the artifact's destination and audience?
- What feedback mode do you want: quick scan, integrated review, reviewer-style critique, mentor-style coaching, line-level edit, or readiness check?
- What constraints matter: deadline, word/slide/page limit, venue, funder, journal, relationship, or known concern?

## Output formats

- `Quick scan`: goal, selected lenses, top 3 priorities, strengths, risks, and next action.
- `Integrated feedback report`: scope, strengths, blocking issues, major revisions, lens-specific notes, revision sequence, and missing context.
- `Reviewer-style critique`: summary assessment, major concerns, minor concerns, overclaim risks, and action priorities.
- `Mentor/collaborator feedback`: what works, highest-leverage changes, suggested wording, questions to discuss, and supportive next step.
- `Readiness check`: ready/needs revision/blocked, must-fix items, assumptions, and specialist follow-up.

## Reference routing

- Open `references/artifact-routing.md` when deciding which specialist lenses apply.
- Open `references/review-modes.md` when choosing quick scan, focused review, integrated review, reviewer-style, mentor-style, or line-edit mode.
- Open `references/feedback-principles.md` when feedback needs stronger prioritization, specificity, uncertainty handling, or non-overwhelming structure.
- Open `references/tone-and-relationship.md` when feedback must fit the role relationship or power dynamic.
- Use `checklists/feedback-report-checklist.md` before returning any integrated feedback report.
- Use artifact-specific checklists for manuscripts, slides, and posters when those are the primary artifact.
- Use examples when the user asks for a model report shape.

## Quick checklist

- Is the artifact goal and destination explicit?
- Did you choose only the lenses that matter for this artifact?
- Are blocking issues separated from major revisions, secondary improvements, and optional polish?
- Does each comment point to an action the user can take?
- Are missing context, unsupported inferences, and relationship constraints marked clearly?
- Does the output integrate lenses rather than dumping separate mini-reviews?

## Common pitfalls

- Duplicating a whole domain skill instead of routing to it.
- Giving generic encouragement or taste-level critique.
- Mixing line edits with strategy feedback without naming the review mode.
- Routing from a filename such as `plan.md`, or from generic review or go/no-go language, before identifying whether the requested judgment is scientific or technical.
- Loading this skill first and relying on its body to reverse an obvious technical-artifact activation.
- Overwhelming the user with every possible problem instead of a revision sequence.
- Treating mentor feedback, peer feedback, journal review, and committee feedback as the same tone.
- Inventing source-backed rules or provenance for this no-source orchestrator.

## Quality bar

- The report must teach the user what to fix first and why.
- Feedback must be artifact-aware, relationship-aware, and scoped to the requested mode.
- Domain lenses must be integrated into one coherent revision path.
- User-facing outputs must not expose workbench provenance, source lists, raw URLs, or private details.

## Reference files

- `references/artifact-routing.md`
- `references/review-modes.md`
- `references/feedback-principles.md`
- `references/tone-and-relationship.md`
