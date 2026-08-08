---
name: research-strategy-and-project-design
description: "Use only when the primary decision is which scientific question, hypothesis, project direction, experimental program, or portfolio bet to pursue, pause, pivot, or stop. Do not use for technical implementation or analysis-design strategy—even if called a strategy, next step, pivot, or go/no-go—unless it materially changes the scientific question, program, portfolio, or whether the project continues. Trigger for candidate ideas, stuck directions, unexpected observations requiring new hypotheses, novelty/feasibility tradeoffs, decisive scientific uncertainties, de-risking experiments, project kill criteria, and project-level decisions. Exclude scripts, pipelines, preprocessing, model or statistical configurations, run diagnostics, analysis units, windows, thresholds, contrasts, estimands, controls, and result presentation. Prefer scientific-feedback for holistic audience-facing research-plan critique."
license: MIT
metadata:
  author: jjfroehlich
  version: "0.1.4"
---

# Research Strategy And Project Design

## Purpose

Help the user turn unclear research possibilities into sharper questions, tractable project designs, explicit tradeoffs, and near-term decisions.

## Use this skill when

Use this skill when the user needs to choose among scientific project ideas, decide whether a research project or hypothesis should continue, design the next decisive scientific test, generate hypotheses, or rebalance a research portfolio.

## Do not use this skill when

Do not use it for protocol details, scripts, pipelines, preprocessing, statistical or model configuration, run diagnostics, analysis units, windows, thresholds, contrasts, estimands, controls, result presentation, manuscript polishing, grant packaging, or personnel management unless the decision materially changes the scientific question, experimental program, or whether the project itself should continue. Do not infer project strategy from generic next-step or go/no-go wording or from the fact that an analysis choice affects scientific results.

## Core workflow

1. Identify the object and level of the decision. Continue only when it concerns a scientific question, hypothesis, project direction, experimental program, or research portfolio rather than a technical implementation choice.
2. Clarify the candidate question, expected knowledge gain, feasibility, current evidence, constraints, and decision horizon.
3. Separate idea generation from idea selection: explore broadly first, then test rigorously.
4. Route to the narrowest playbook needed.
5. Name the decisive uncertainty and the cheapest credible way to reduce it.
6. Recommend a next action, stop/go review, or comparison table rather than giving only abstract advice.

## Output formats

- Short strategy memo with recommendation, rationale, decisive uncertainty, and next test.
- Project comparison table with feasibility, expected knowledge gain, timeline, stage fit, kill test, and stop/go recommendation.
- Hypothesis-generation plan that separates exploratory moves from confirmatory tests.
- Risk register with continuation criteria, failure modes, and review date.

## Reference routing

- Open `references/choosing-problems.md` when the user is choosing a problem, comparing novelty and tractability, or asking what makes a scientific question worth pursuing.
- Open `references/project-triage.md` when the user has one or more project ideas and needs a pursue, pause, pivot, or quit decision.
- Open `references/risk-and-kill-criteria.md` when the user needs a cheap decisive test, continuation threshold, feared control, or bias-resistant review.
- Open `references/experiment-types.md` when the strategic question depends on what kind of evidence, scale, or experiment type should come next.
- Open `references/hypothesis-generation.md` when the user is stuck, needs new hypotheses, is interpreting unexpected observations, or wants more creative routes into a problem.

## Quick checklist

Before answering, check whether the user has supplied enough context about the question, field constraints, available tools/data, time horizon, career or portfolio stage, and what decision the advice must support. If not, ask only for the missing inputs that would change the recommendation.

## Common pitfalls

- Do not treat exciting, novel, or difficult ideas as automatically worth pursuing.
- Do not let sunk costs, identity, or external encouragement replace current evidence.
- Do not use exploratory observations as confirmatory evidence without a follow-up test.
- Do not relabel pipeline, preprocessing, model-selection, statistical-contrast, estimand, analysis-window, control-definition, or software-architecture decisions as research strategy merely because they affect scientific conclusions or involve tradeoffs or continuation language.
- Do not expose source provenance, bibliographies, or internal normalization notes in user-facing answers.

## Quality bar

- Make tradeoffs visible instead of treating every idea as equally good.
- State feasibility checks and kill criteria explicitly.
- Separate exciting from executable.
- End with a next decision or test.
