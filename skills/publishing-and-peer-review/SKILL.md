---
name: publishing-and-peer-review
description: "Use when the user is acting as an author, reviewer, or editor-facing correspondent in a scientific publication process and needs help with journal submission packages, cover letters, presubmission or editor inquiries, peer-review reports, reviewer ethics, conflicts, confidentiality, editorial decision interpretation, appeals, transfers, resubmission strategy, or response-to-reviewers letters. Trigger on concrete publication-process decisions or artifacts, not on general manuscript prose editing, figure design, grant review, literature summaries, or journal-ranking curiosity without an active submission/review context."
license: MIT
metadata:
  author: jjfroehlich
  version: "0.1.0"
---

# Publishing And Peer Review

## Purpose

Help the user make publication-process decisions and produce bounded artifacts for submission, peer review, editorial communication, revision, and response-to-reviewers work.

## Use this skill when

- The user needs a journal submission, presubmission inquiry, cover letter, rejection strategy, transfer decision, or resubmission package.
- The user is writing, revising, or evaluating a peer-review report.
- The request concerns reviewer ethics, conflicts of interest, confidentiality, confidential comments, open review, or reviewer overreach.
- The user needs a response-to-reviewers plan, point-by-point response, or respectful disagreement with reviewer comments.
- The user asks how to interpret an editorial decision, revision request, or reviewer recommendation.

## Do not use this skill when

- The user primarily wants manuscript prose rewritten; apply a scientific-writing lens instead.
- The task is figure design, chart choice, or visual communication.
- The request is about grant review, thesis supervision, career planning, or literature synthesis without a publication-process decision.
- The user asks for journal rankings or impact-factor strategy without a concrete submission or review artifact.

## Core workflow

1. Identify the role: author, reviewer, editor-facing correspondent, or mixed role.
2. Identify the next process action: submit, revise, appeal, transfer, decline, review, respond, or ask the editor a focused question.
3. Ask only for missing facts that change the next action: decision letter, target journal, review invitation, manuscript type, deadline, or policy constraint.
4. Route to the narrow playbook: journal submission, editorial process, peer reviewing, reviewer ethics, or response to reviewers.
5. Separate process guidance from manuscript-quality feedback.
6. Produce the artifact in a trackable format: checklist, review outline, cover-letter plan, editor inquiry, or point-by-point response.
7. Check for ethics, confidentiality, reviewer overreach, and unsupported claims before finalizing.

## Output formats

- Submission-readiness review with journal-fit risks and missing package items.
- Cover-letter or presubmission-inquiry outline.
- Editorial-decision diagnosis with next-step options.
- Peer-review report outline with major/minor comments and confidential-note guidance.
- Reviewer-ethics decision memo.
- Point-by-point response-to-reviewers plan or draft.

## Reference routing

- `references/journal-submission.md`: Use for journal fit, cover letters, submission packages, rejection strategy, appeal, transfer, and resubmission decisions.
- `references/editorial-process.md`: Use for interpreting editor decisions, revision expectations, reviewer synthesis, and editor communication.
- `references/peer-reviewing.md`: Use for review invitations, manuscript review workflow, review structure, constructive comments, reviewer overreach, and statistical-review triage.
- `references/reviewer-ethics.md`: Use for conflict, confidentiality, privileged information, misconduct concerns, confidential comments, open review, or review transfer.
- `references/response-to-reviewers.md`: Use for response letters, point-by-point plans, respectful disagreement, reviewer misunderstandings, and out-of-scope requested experiments.

## Quick checklist

- Role and next process action are explicit.
- Advice is bounded to the current journal, manuscript, review invitation, or decision letter.
- Major issues are separated from minor polish.
- Any requested experiment or analysis is tied to a claim that actually needs it.
- Confidential, ethical, or editor-only material is not put into author-facing text.
- The output tells the user what to send, revise, decline, or ask next.

## Common pitfalls

- Treating a rejection as an appeal problem before diagnosing scope, evidence, novelty, or process error.
- Writing peer reviews as unprioritized reactions instead of evidence-linked major and minor comments.
- Asking authors for open-ended new projects when a claim limit, analysis clarification, or future-work statement would address the concern.
- Responding defensively to reviewers without changing the manuscript or giving a clear rationale.
- Exposing confidential review material, source provenance, raw URLs, or bibliography-style evidence in exported skill outputs.

## Quality bar

- The answer must be role-aware, process-aware, and ethically bounded.
- The answer must produce a concrete next artifact or decision, not generic publication advice.
- Reviewer and response language must be calm, specific, actionable, and traceable to manuscript claims.
- Disagreements must state the concern, evidence or constraint, and the bounded change or non-change.
- Exported outputs must avoid private provenance, source lists, citation maps, raw URLs, and DOI-like identifiers.
