# Artifact Routing

Use this when a feedback request could involve more than one specialist lens or when the artifact type is ambiguous.

## Use this when...

- The user says "review this," "critique this," "sanity-check this," or "give feedback" without naming the exact kind of feedback.
- The artifact combines writing, figures, presentation, publication, funding, strategy, literature, or lab-management concerns.
- You need to decide whether to use this orchestrator or hand off to one narrower domain lens.

## The job of this topic

Route the artifact to the fewest domain lenses that explain the main feedback risks, then integrate those lenses into one revision path.

## Default workflow

1. Reapply a hard pre-routing gate to the current user turn, even when this orchestrator was appropriate earlier: the primary deliverable must be audience-facing scientific communication or governance, and the requested critique must need at least two lenses.
2. Do not activate or retain this orchestrator for code, scripts, notebooks, data-flow or missing-value diagnosis, analysis outputs, computational or statistical workflows, data pipelines, model choices, technical plans or specifications, requirements documents, requirements-to-code traceability, run diagnostics, or technical documentation. The filename, prior task context, or presence of a planning document does not change this rule.
3. For an in-scope request, identify the artifact and destination: journal, funder, talk, committee, lab meeting, collaborator, mentor, trainee, or public audience.
4. Select primary and secondary lenses; do not apply every lens just because it is available.
5. State the chosen lenses in the response before detailed critique.
6. Produce one integrated priority list rather than separate disconnected reviews.

## Decision rules

- Manuscript or thesis prose: apply the scientific-writing lens first; add figure, publishing, or strategy lenses only if the artifact needs them.
- Slides, talks, posters, and pitches: apply the scientific-communication lens first; add figure and writing lenses for visuals or wording.
- Plots, tables, microscopy, graphical abstracts, or figure packages: apply the data-visualization-and-figures lens first.
- Submission packages, peer-review reports, editorial decisions, and response letters: apply the publishing-and-peer-review lens.
- Grants, fellowships, specific aims, and funding narratives: apply the grant-writing lens.
- Paper notes, journal-club prep, synthesis matrices, and reading workflows: apply the literature-reading-and-synthesis lens.
- Audience-facing study proposals being reviewed across scientific question, evidence, feasibility, and communication: apply the research-strategy-and-project-design lens plus the relevant communication or writing lens.
- Software implementation plans, computational analysis workflows, pipeline documentation, model-selection reports, requirements documents, requirements-to-code crosswalks, and completed-run diagnostics: use general technical, code, statistical, or data-analysis review. Do not route them here or to research strategy merely because the user asks what to do next.
- Lab handbooks, mentoring compacts, feedback scripts, IDPs, conflict notes, and culture documents: apply the mentoring-management-and-lab-culture lens.

## Variants and edge cases

- A manuscript with figures needs writing plus figure lenses, but publication-process advice only if submission or review is part of the ask.
- A grant with aims, figures, and feasibility needs grant-writing as primary, with writing, figures, and research-strategy as secondary lenses.
- A poster needs scientific-communication as primary; use data visualization only for figure readability or evidence display.
- A trainee feedback script about a manuscript may need mentoring-management for the relationship and scientific-writing for the artifact.
- A Markdown plan can be a scientific study plan or a software implementation plan; route from the requested judgment and content, not the extension or filename.
- Planning documents mapped directly onto an R, Python, or other script are technical review even when the documents specify scientific-analysis requirements.
- Results and output directories remain technical analysis inputs unless the current request explicitly asks to turn them into, or assess them as, an audience-facing scientific argument or artifact across multiple lenses.

## Anti-patterns

- Applying all lenses and overwhelming the user.
- Treating a mixed artifact as a single-domain task when the main risk crosses domains.
- Routing based on file type only, ignoring audience and destination.
- Treating technical tradeoffs as project strategy because the request uses words such as "pivot," "go/no-go," or "going forward."
- Claiming that another skill was called when you only applied its lens manually.

## Diagnostic questions

- What is the artifact and where is it going?
- What kind of feedback did the user ask for: content, structure, strategy, visual design, readiness, tone, or process?
- Which issue would make the artifact fail if left unfixed?
- Which specialist lens would change the top priority?
- Is a narrower domain skill sufficient?

## Output patterns / mini-templates

```text
Scope: <artifact, audience, destination>.
Selected lenses: <primary lens>, <secondary lens if needed>.
Why these lenses: <one-line routing rationale>.
Priority order: <blocking issue -> major revision -> secondary polish>.
```

## Examples

- "Review my results section and Figure 3" -> scientific-writing plus data-visualization-and-figures.
- "Is my specific aims page compelling?" -> grant-writing plus scientific-writing.
- "Critique this poster before the conference" -> scientific-communication plus data-visualization-and-figures.
- "Review whether this study plan connects the biological question, evidence, and decisive experiment" -> research-strategy-and-project-design plus scientific-writing when presentation also matters.
- "Review `plan.md` for pipeline stages, code organization, and model choices" -> general technical review, not this orchestrator.
- "Map these two scientific-analysis planning documents onto the R script and identify implementation gaps" -> general technical or code review, not this orchestrator.

## When not to apply this

Do not use the orchestrator when the user asks a narrow, single-domain task, or when the artifact is primarily a technical work product and the scientific artifact is not itself under review.
