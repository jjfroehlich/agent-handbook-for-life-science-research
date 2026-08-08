---
name: literature-reading-and-synthesis
description: "Use only when active reading or synthesis of scientific literature is the primary requested work or deliverable. Do not use for computational-analysis, pipeline, model-architecture, fine-tuning, or implementation strategy merely because the user asks to consult relevant literature or wants evidence-backed recommendations. Trigger for reading strategy, claim/evidence extraction, figure unpacking, cross-paper comparison, synthesis matrices, literature tracking, reusable evidence notes, or journal-club/project-decision readiness requiring renewed examination of papers, figures, tables, or notes. Do not trigger when literature is background or a completed review is supplied only to update plans, workflows, scripts, manuscripts, or documentation. Also exclude dataset/download provenance, citation-manager mechanics, literature search alone, simple one-paper summaries, citation formatting, grant writing, peer review, and slide design unless active literature synthesis is primary."
license: MIT
metadata:
  author: jjfroehlich
  version: "0.1.3"
---

# Literature Reading And Synthesis

## Purpose

Help users read scientific papers actively, extract claims and evidence without flattening them, maintain a sustainable literature-tracking routine, and turn notes into synthesis artifacts.

## Use this skill when

- First classify the requested work: continue only when the user needs renewed reading, evidence extraction, comparison, or synthesis of literature sources.
- The user needs a reading plan for one or more papers.
- The user asks how to unpack figures, tables, methods, claims, or limitations.
- The user wants a synthesis matrix, comparison table, or reusable note template.
- The user is setting up or debugging a literature-alert or reading queue.
- The user needs presentation, journal-club, or project-decision readiness from papers.

## Do not use this skill when

- A completed literature review is only an input to downstream plan, code, pipeline, manuscript, or documentation updates.
- Relevant papers are only supporting evidence for a computational-analysis, pipeline, model-architecture, fine-tuning, or implementation strategy.
- The task is to trace dataset URLs, downloads, schemas, or pipeline provenance without interpreting the scientific literature.
- The user only asks for a factual summary of one paper and does not need a method.
- The task is mainly manuscript drafting, grant writing, or peer review rather than reading/synthesis.
- The request is citation formatting or citation-manager mechanics.

## Core workflow

1. Clarify the goal: orient, skim, present, compare, decide, track, or synthesize.
2. Route to the right playbook: paper reading, claim extraction, literature tracking, or synthesis matrices.
3. Pick the appropriate depth: quick triage, targeted section read, figure/evidence read, or high-stakes deep read.
4. Separate motivation, approach, results, interpretation, limitations, and next steps.
5. For figures and tables, decode the evidence before writing the take-home.
6. Convert the read into a concrete output: reading plan, extraction table, figure note, tracking queue, or synthesis matrix.
7. State caveats when advice is about habit design, dated source lists, or unsupported citation-manager mechanics.

## Output formats

- Reading-depth plan.
- Six-question paper note.
- Figure/table unpacking note.
- Claim and evidence extraction table.
- Literature alert portfolio.
- Weekly literature triage queue.
- Synthesis matrix.
- Build-on-it note with next research action.

## Reference routing

- Open `references/paper-reading-workflow.md` for reading goals, article-type routing, section intent, deep-read passes, and presentation readiness.
- Open `references/claim-extraction.md` for six-question extraction, figure/table unpacking, claim appraisal, and critique discipline.
- Open `references/literature-tracking.md` for alert streams, source portfolios, query tuning, weekly triage, and backlog pruning.
- Open `references/synthesis-matrices.md` for matrix fields, field-source maps, build-on-it notes, and comparison outputs.
- Use checklists for quick execution once the relevant reference route is clear.
- Use examples when the user asks for a template, worked pattern, or concrete artifact.

## Quick checklist

- What is the user's reading goal and deadline?
- Is this quick triage, targeted reading, or high-stakes deep reading?
- What article type is it?
- Which claims, figures, methods, limitations, and next steps must be separated?
- Does the output need a paper note, figure note, tracking queue, or synthesis matrix?
- Are citation-manager mechanics being requested without source-backed guidance?

## Common pitfalls

- Reading every paper at the same depth.
- Copying the abstract instead of extracting claims and evidence.
- Accepting figure take-homes before decoding the display.
- Treating publication as proof.
- Building an alert stream too large to process.
- Turning a synthesis matrix into a miscellaneous notes field.

## Quality bar

- The answer must name the reading/tracking goal and choose a matching depth.
- Claims, evidence, interpretation, limitations, and next actions must be distinct.
- Figure and table advice must include concrete evidence-decoding steps.
- Literature tracking advice must be sustainable and volume-aware.
- Outputs must be reusable by the user after the conversation.
