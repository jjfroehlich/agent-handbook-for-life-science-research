# Specific Aims

## Use this when...

Use this when the user is drafting or revising aims, aim dependencies, a specific aims page, aim overview figures, or aim-level approach blocks.

## The job of this topic

Make the aims cognitively manageable, visibly connected to the premise, independently valuable where possible, and supported by enough feasibility evidence to survive reviewer skepticism.

## Default workflow

1. State the objective and active premise before listing aims.
2. Add an early overview figure or verbal map that shows the relationship among aims.
3. Check whether each aim answers a distinct part of the central question.
4. Identify dependencies and what happens if an enabling step fails. Independent aims may reduce fragility; sequential development can be appropriate when qualification criteria, decision gates, and remaining useful outputs are clear.
5. For the aims being reviewed, identify rationale, plan, available evidence, interpretable outcomes, and consequential risks. Name an alternative only if it is credible and supplied, or label it as a proposal to verify.
6. Group crowded projects so a reviewer can follow their relationships. Use the scheme's expected aims, objectives, work packages, or milestones; three goals can be a useful drafting default, not a ceiling.

## Decision rules

- If aim 2 needs aim 1, assess whether the dependency suits the funded purpose. Show evidence or a planned qualification gate and explain what remains possible if the gate is not met; restructure when the resulting risk is unjustified.
- If a reviewer cannot follow the parts, clarify their grouping and sequence rather than mechanically reducing their number.
- If the overview figure is decorative, replace it with a figure that shows logic, dependencies, and expected outputs.
- If an aim is already mostly complete, recast completed work as preliminary evidence rather than funded future work.

## Variants and edge cases

- The three-aim rule is a reviewer-cognition heuristic, not a universal eligibility requirement.
- Some mechanisms expect work packages, objectives, or milestones instead of "Aim 1/Aim 2/Aim 3"; preserve the logic under the required labels.
- A method-development call can fund unresolved technical capability. State what must be developed, how it will be assessed, and how time and resources support that work.

## Anti-patterns

- Hidden dependencies with no evidence, qualification plan, or decision gate.
- Aims that are topic labels rather than testable or buildable advances.
- Aims overview figures that are visually polished but do not explain the project.
- Listing methods without rationale, outcomes, or alternatives.

## Diagnostic questions

- Can the reviewer explain how the aims fit together after reading the overview?
- What useful work remains if an enabling aim partially fails?
- Which feasibility claim supports each aim?
- What result would change the next decision?
- What credible alternative, qualification gate, or scope decision follows if the preferred experiment fails?

## Output patterns / mini-templates

Aim feasibility row:

```text
Aim:
Question or objective:
Rationale:
Core plan:
Preliminary evidence or enabling resource:
Interpretable outcomes:
Main risk:
Backup or alternative:
Reviewer concern reduced:
```

Approach block:

```text
Rationale -> overall plan -> specific example/preliminary data -> outcomes -> potential issue -> workaround
```

## Examples

Weak aim relationship: Aim 2 depends entirely on an untested result from Aim 1.

Possible revision: if an existing dataset, pilot-supported candidate, or orthogonal method is actually available and suitable, explain how it supports Aim 2. Otherwise preserve the unresolved dependency and propose a qualification gate or scope change; do not invent a backup.

## When not to apply this

Do not force independent aims if the mechanism explicitly asks for sequential milestones; instead make the dependency, decision gates, and fallback paths explicit.
