# Risk And Kill Criteria

## Use This When

Use this playbook when the user asks what could kill a project, how to test a risky premise cheaply, or how to avoid fooling themselves with confirmatory evidence.

## The Job Of This Topic

Identify which uncertainty could change the next commitment, and whether a credible check is worth its cost. Some projects have a cheaply checkable necessary premise; others do not.

## Default workflow

1. If value genuinely depends on a necessary premise, state it as: "This is worth doing only if P." Do not force every open question into one premise.
2. Identify the evidence that would make P unlikely enough to stop, pivot, or redesign.
3. Prefer an early inexpensive check when it can actually address P. If no such check exists, compare the information and cost of the larger commitment with the alternatives.
4. Examine an avoided control or counterexample when it targets a real ambiguity; nervousness alone does not make it decisive.
5. Agree on what interpretable evidence would change the commitment. Distinguish an assay or manipulation failure, insufficient precision, and a result that challenges the prediction. Keep the scientific conclusion separate from a practical pause.

## Decision rules

- Test cheaply checkable necessary conditions before work that depends on them.
- Prefer killer experiments that change the decision, not demonstrations that merely feel productive.
- Make an avoided consequential control, counterexample or informed critique explicit. Give it priority when it can change the decision and is feasible; fear alone does not prove relevance, decisiveness or bad faith. A justified pause or stop need not wait for that experiment.
- When observation contradicts expectation, check whether the contradiction reveals a hidden assumption before discarding it as noise.
- A negative biological inference needs a working manipulation and assay, appropriate conditions, and uncertainty narrow enough to challenge the predicted effect. A failed control leaves the biological comparison unresolved; diagnosis or repair is an option if further work is worthwhile. A non-significant result alone does not establish absence, and large N or a small estimate alone does not establish practical equivalence.
- Choose review conditions with the user; do not invent a universal number of failed experiments or require a definitive scientific answer before pausing an unaffordable route.
- Scrutinize a favorable expected result too. Examine consequential bias, measurement/grouping choices and alternatives; report justified specification changes openly. Do not keep searching until a preferred configuration succeeds or assume preregistration, blinding or a large study removes every bias.

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
- Is a relevant check being avoided, and what would its outcomes change?
- Can existing data, code, literature, or a pilot answer the first risk?
- What result will cause a stop or pivot decision?

## Output Patterns / Mini-Templates

Select fields only when a shared decision record helps; do not invent a failure mode, test or threshold merely to complete the scaffold.

```text
Only worth continuing if:
Most likely failure mode:
Credible check and actual cost, or why none is affordable:
Consequential avoided check, if any:
Evidence needed for an interpretable decision:
Continue, repair, pause or redirect if:
Scientific uncertainty that remains:
Review date:
```

## Examples

- A relevant existing-data comparison or pilot can assess a necessary premise before a large collection when sampling, sensitivity and access permit it. An insensitive pilot cannot establish absence.
- A counterexample can defeat a stated conjecture; failing to find one is not proof. A prior-work search may change the contribution without proving no earlier work exists.
- A confound check is useful when it separates the claim from an actual alternative; a technically successful procedure or a sophisticated model name is not by itself an interpretable answer.

## When Not To Apply This

Do not frame exploratory work as failed merely because it lacks confirmatory evidence. Identify the actual commitment being considered; exploration can be worthwhile while still competing for finite resources.
