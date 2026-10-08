---
name: research-strategy-and-project-design
description: "Choose scientific questions, hypotheses, experimental programs, or project continuation. Exclude analysis and implementation choices within an already chosen project."
license: MIT
metadata:
  author: jjfroehlich
  version: "0.1.1"
---

# Research Strategy And Project Design

## Purpose

Help the user turn unclear research possibilities into sharper questions, tractable project designs, explicit tradeoffs, and near-term decisions.

## Use this skill when

Use this skill when the user needs to choose among scientific project ideas, decide whether a research project or hypothesis should continue, design the next decisive scientific test, generate hypotheses, or rebalance a research portfolio.

## Do not use this skill when

Keep fixed-project analysis and implementation outside this skill: dataset/features, models, statistical contrasts, genomic windows, diagnostics, plots, protocols and code. A plan or go/no-go request belongs here only when it changes the scientific question, experimental program or project continuation. Earlier strategy work does not keep the skill active for later technical tasks.

## Core workflow

1. Identify the scientific choice the user is making; use their existing evidence and constraints before asking for missing context.
2. Compare the question's knowledge gain and personal interest with practical feasibility and the decision horizon. Give reasons; do not invent numerical scores.
3. Distinguish idea generation from testing. Explore alternatives when needed, then identify predictions that can separate them; allow results to reshape the next question.
4. Route to the narrowest playbook needed.
5. Name the uncertainty that changes the next commitment. Prefer an early inexpensive check when it is credible; acknowledge when the informative test requires a larger commitment.
6. Recommend an action proportionate to the evidence. Distinguish failed measurements and imprecise results from evidence against a biological prediction. A pause can leave the question unresolved.

## Output formats

Select only the format that fits the requested deliverable; these are patterns, not mandatory response sections.

- Short strategy memo with recommendation, rationale, decisive uncertainty, and next test.
- Project comparison table with the dimensions that change the choice, such as feasibility, knowledge gain, timeline, support and next informative check.
- Hypothesis-generation plan that separates exploratory moves from confirmatory tests.
- Risk register with continuation criteria, failure modes, and review date.

## Reference routing

- Open `references/choosing-problems.md` when the user is choosing a problem, comparing novelty and tractability, or asking what makes a scientific question worth pursuing.
- Open `references/project-triage.md` when the user has one or more project ideas and needs a pursue, pause, pivot, or quit decision.
- Open `references/risk-and-kill-criteria.md` when the user needs a cheap decisive test, continuation threshold, feared control, or bias-resistant review.
- Open `references/experiment-types.md` when the strategic question depends on what kind of evidence, scale, or experiment type should come next.
- Open `references/hypothesis-generation.md` when the user is stuck, needs new hypotheses, is interpreting unexpected observations, or wants more creative routes into a problem.
- Open `references/handbook-access.md` when a fuller explanation or worked example would help with the current task.

## Quick checklist

Apply only the checks relevant to the requested decision. Inspect available context first; ask only for missing information about the question, constraints, tools/data, time horizon, career or portfolio stage, or decision that would materially change the recommendation.

## Common pitfalls

- Do not treat exciting, novel, or difficult ideas as automatically worth pursuing.
- Do not let sunk costs, identity, or external encouragement replace current evidence.
- Do not use exploratory observations as confirmatory evidence without a follow-up test.
- Do not treat a failed control, unavailable resource or non-significant comparison as proof that the biological idea is false.

## Quality bar

- Make tradeoffs visible instead of treating every idea as equally good.
- State the conditions that change the recommendation; use quantitative continuation thresholds only when the prediction, assay and user's constraints justify them.
- Separate exciting from executable.
- Return the requested answer; do not require a risk register, worksheet or full review for a small decision.
