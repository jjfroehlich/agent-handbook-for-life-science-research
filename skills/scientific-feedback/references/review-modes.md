# Review Modes

Use this to choose quick scan, focused review, deep integrated review, reviewer-style critique, mentor-style feedback, collaborator-style feedback, readiness check, or line edit.

## Use this when...

- The user did not specify how deep the review should be.
- The artifact is long and cannot be fully line-edited in one pass.
- The relationship or destination changes how feedback should be framed.

## The job of this topic

Match the review depth and voice to the user's goal so feedback is useful rather than either too shallow or too exhaustive.

## Default workflow

1. Infer the likely mode from the prompt and artifact.
2. If mode changes the work substantially, ask one clarifying question.
3. Explain scope when needed to avoid a misleading impression of what was reviewed.
4. Apply only the detail level appropriate to the mode.
5. Offer a next-pass option when deeper review would be useful.

## Decision rules

- Quick scan: return the most consequential findings at the requested scale. A short replacement phrase can help demonstrate a repair without becoming a full line edit.
- Focused review: review the named dimension only, such as figures, claims, audience, or feasibility.
- Deep integrated review: combine multiple lenses and return a revision sequence.
- Reviewer-style critique: write major concerns, minor concerns, overclaim risks, and decision-relevant evidence.
- Mentor-style feedback: preserve agency, explain rationale, and include questions or next discussion points.
- Collaborator-style feedback: emphasize shared goals, concrete edits, and tradeoffs.
- Readiness check: return ready/needs revision/blocked with must-fix items.
- Line edit: revise wording only after structure, claim, and evidence are already in scope or stable.

## Variants and edge cases

- When the user asks "be harsh," keep the feedback direct but still actionable and bounded.
- When the user asks for "quick" feedback on a high-stakes artifact, give triage and identify what a deeper pass should check.
- When the artifact is incomplete, review the plan and risk areas rather than pretending to evaluate final readiness.
- When the user wants comments to send to someone else, tune relationship and power dynamics before wording.

## Anti-patterns

- Returning a line edit when the user asked for strategic feedback.
- Writing reviewer-style criticism when the user asked for mentor-style coaching.
- Giving a readiness verdict without checking destination constraints.
- Trying to cover every specialist lens in a quick scan.

## Diagnostic questions

- What decision will the feedback support?
- Is the user revising, submitting, rehearsing, mentoring, or deciding whether to continue?
- Does the user need a diagnosis, a rewrite, a report, or a checklist?
- How much time or revision capacity does the user have?

## Output patterns / mini-templates

```text
Mode: <quick/focused/deep/reviewer/mentor/readiness/line edit>.
Scope: <what I reviewed>.
Not covered: <what this pass does not attempt>.
Output: <prioritized findings or edited artifact>.
Next pass: <optional deeper route>.
```

## Examples

- "Can you quickly sanity-check this grant abstract?" -> quick scan through grant-writing; add a distinct second lens only when the requested judgment needs it, otherwise use the narrower skill.
- "Review this as a journal reviewer" -> reviewer-style critique with publishing-and-peer-review plus scientific-writing or figures as needed.
- "Help me give feedback to my student on this slide deck" -> mentor-style feedback with scientific-communication and tone/relationship routing.

## When not to apply this

Do not spend time on mode selection when the user has clearly requested a single concrete output.
