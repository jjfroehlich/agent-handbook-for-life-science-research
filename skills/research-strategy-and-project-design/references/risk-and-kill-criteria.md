# Risk And Kill Criteria

## Use This When

Use this playbook when the user asks what could kill a project, how to test a risky premise cheaply, or how to avoid fooling themselves with confirmatory evidence.

## The Job Of This Topic

Find the condition that must be true for the project to be worth continuing, then design the smallest credible check before expensive commitment.

## Default workflow

1. State the project as: "This is worth doing only if P."
2. Identify the evidence that would make P unlikely enough to stop, pivot, or redesign.
3. Prefer an early inexpensive check when it can actually address P. If no such check exists, compare the information and cost of the larger commitment with the alternatives.
4. Examine an avoided control or counterexample when it targets a real ambiguity; nervousness alone does not make it decisive.
5. Agree on what interpretable evidence would change the commitment. Distinguish an assay or manipulation failure, insufficient precision, and a result that challenges the prediction. Keep the scientific conclusion separate from a practical pause.

## Decision rules

- Test cheaply checkable necessary conditions before work that depends on them.
- Prefer killer experiments that change the decision, not demonstrations that merely feel productive.
- Include feared controls because ignored controls often reveal the decisive confound.
- When observation contradicts expectation, check whether the contradiction reveals a hidden assumption before discarding it as noise.
- A negative biological inference needs a working manipulation and assay, appropriate conditions, and uncertainty narrow enough to challenge the predicted effect. A failed control calls for diagnosis; a non-significant result alone does not establish absence.
- Choose review conditions with the user; do not invent a universal number of failed experiments or require a definitive scientific answer before pausing an unaffordable route.

## Variants And Edge Cases

- In computational projects, the kill test may be a counterexample search, baseline comparison, existing-data analysis, or stress test.
- In wet-lab projects, the kill test may be a pilot for noise, effect size, reagent validity, or feasibility.
- In theory-heavy projects, the kill test may be a prediction that clearly distinguishes competing explanations.

## Anti-Patterns

- Choosing tests that can only confirm enthusiasm.
- Moving to expensive scale before checking the necessary condition.
- Explaining away a valid challenging result as technical, or treating a failed assay as evidence that the biology is absent.
- Ignoring a contradiction because it threatens the preferred story.

## Diagnostic Questions

- What must be true for this project to be worth the next month?
- What observation would make the main interpretation untenable?
- Which control would the team be nervous to run?
- Can existing data, code, literature, or a pilot answer the first risk?
- What result will cause a stop or pivot decision?

## Output Patterns / Mini-Templates

```text
Only worth continuing if:
Most likely failure mode:
Cheapest decisive check:
Feared control/counterexample:
Evidence needed for an interpretable decision:
Continue, repair, pause or redirect if:
Scientific uncertainty that remains:
Review date:
```

## Examples

- Run an online or existing-data pilot before building a large new collection.
- Search for counterexamples or confounds that would torpedo the interpretation.
- Check whether a claimed effect survives a simple baseline before designing a complex model.

## When Not To Apply This

Do not frame exploratory work as failed merely because it lacks confirmatory evidence yet. First decide whether the work is in exploration mode or decision mode.
