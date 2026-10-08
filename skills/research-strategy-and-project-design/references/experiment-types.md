# Experiment Types

## Use This When

Use this playbook when the user is deciding what kind of experiment, evidence, or measurement strategy should come next.

## The Job Of This Topic

Match the research claim to the evidence type that can test it, while making blind spots visible.

## Default workflow

1. Name the claim the project wants to make.
2. Identify the scale and evidence type currently available.
3. Ask what the current approach cannot see.
4. Decide whether the next step should be exploratory, confirmatory, mechanistic, comparative, perturbational, theoretical, or integrative.
5. Choose a complementary evidence source only if it changes the decision or interpretation.

## Decision rules

- Treat each method as partial: every evidence type has a scale, resolution, and blind spot.
- When it helps expose a missing inference, distinguish perturbation (changing a component), visualization (observing location or behavior), substitution (using a measurable proxy for a component), characterization (measuring properties), reconstitution (assembling components) and simulation (exploring a model). Use this as a coverage aid, not a requirement to perform all six.
- Check proxy and intervention assumptions: labels can change or fail to reveal the phenomenon, perturbations can induce compensation, and a reconstituted system demonstrates capability under its constructed conditions.
- Use theory-first design when the project needs a model to specify what should be measured and what would distinguish alternatives.
- Separate exploratory and confirmatory work. Exploration finds patterns; confirmation tests specific claims.
- Do not demand every possible method; add methods that reduce the decisive uncertainty.

## Variants And Edge Cases

- For living systems, evidence may need to span molecular, cellular, organismal, population, temporal, or ecological scales.
- For rich datasets, exploratory visualization can reveal unexpected structure, but it should not be reported as a confirmed causal claim without follow-up.
- For theory-driven projects, the most important next experiment may be one that falsifies a model assumption.

## Anti-Patterns

- Assuming a single high-resolution method provides full understanding.
- Adding techniques for prestige rather than decision value.
- Calling data-driven pattern discovery hypothesis-free in a way that denies background assumptions.
- Treating theoretical figures or models as decoration rather than design tools.

## Diagnostic Questions

- What claim is the user trying to support?
- What scale does the current evidence cover?
- What blind spot would most threaten the interpretation?
- Is the next step meant to discover patterns or test a named claim?
- What complementary evidence would actually change the project decision?

## Output Patterns / Mini-Templates

| Claim | Current evidence | Blind spot | Next evidence type | Why it changes the decision |
|---|---|---|---|---|
| Mechanism, association, prediction, or explanation | Data/method used now | What it cannot see | Pilot, perturbation, comparison, model, or integration | Decision impact |

## Examples

- If a dataset suggests a pattern, recommend an exploratory pass plus a later confirmatory test.
- If the user has a mechanism story, ask what perturbation or prediction would distinguish it from alternatives.
- If a method has narrow scale coverage, pair it with a complementary check only when the blind spot affects the claim.

## When Not To Apply This

Do not use this playbook as a protocol generator. It selects experiment strategy, not exact bench or code implementation.
