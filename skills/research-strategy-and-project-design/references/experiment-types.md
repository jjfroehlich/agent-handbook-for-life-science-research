# Experiment Types

## Use This When

Use this playbook when the user is deciding what kind of experiment, evidence, or measurement strategy should come next.

## The Job Of This Topic

Match the research claim to the evidence type that can test it, while making blind spots visible.

## Default workflow

1. Name what the user wants to learn and which claim the evidence would need to support.
2. Identify the scale and evidence type currently available.
3. Ask what the current approach cannot see.
4. Decide whether the next step should be exploratory, confirmatory, mechanistic, comparative, perturbational, theoretical, or integrative.
5. Choose a complementary evidence source only if it changes the decision or interpretation.

## Decision rules

- State the approach's actual scope and assumptions. One well-used method can adequately support a bounded claim; several poorly used or dependent methods need not improve it.
- Use the approach distinctions below only when they expose an inference that matters. They are not a methods menu to complete or a requirement for a complementary method per claim.
- Check proxy suitability and noninterference separately. A proxy can leave the system undisturbed yet fail to track the target, or track the target under conditions it has itself altered. Reproducibility does not resolve either problem.
- Use theory-first design when the project needs a model to specify what should be measured and what would distinguish alternatives.
- Preserve which observations shaped the explanation, which predictions were specified before testing and which selections changed the analysis. Exploration and testing can interleave; do not report a discovery as an independent confirmation of itself.
- Do not demand every possible method; add methods that reduce the decisive uncertainty.

## What the approach can establish

| Approach | Inference to check before expanding the program |
|---|---|
| Perturbation | A changed part acts within a system. A phenotype does not identify a unique master regulator; compensation or other consequences can hide or mimic the intended effect. |
| Visualization | What is detectable, and does observation alter it? A label must remain interpretable across relevant locations/conditions; an unseen feature need not be absent. |
| Substitution | Does the measurable proxy preserve the target-like interactions needed for this claim, without consequentially changing the system? Unexpected proxy behavior may reveal another interaction rather than the target's behavior. |
| Characterization | Measuring an isolated part can omit context, interactions or distinct entities. Precision of the assay does not make the property a complete explanation. |
| Reconstitution | Assembled components show what they can do under constructed conditions; missing components or arrangement can prevent transfer to the intact system. |
| Simulation | A model explores selected features and can guide otherwise inaccessible comparisons. Its behavior depends on assumptions and is not itself evidence that the biological mechanism operates. |

Choose another method when it addresses a consequential ambiguity worth its cost. A new label on the same weak proxy may preserve the problem. Conversely, do not delay an adequately supported concentration, location or descriptive claim merely to satisfy a technique count. The support needed for a mechanism may be different from that for the narrower observation.

## Designing an informative comparison

Identify the actual contrast and independent sampling or assignment units. Hundreds of cells, technical repeats or split aliquots do not create independent cultures or subjects. Preserve useful pairing and nesting; a multilevel model is not an automatic cure for inadequate design. Separate significance outcomes do not establish that effects differ: the relevant contrast and its uncertainty are needed.

Use controls, comparable handling, allocation and blinding for the particular alternatives they address. A before/after change alone may combine intervention, time and practice. No one-variable-only rule excludes factorial designs, and no universal sample count makes a study adequate. Consider meaningful effects, plausible variation, the estimand and feasible population; rare-population work may be useful with explicitly limited precision. Seek appropriate design expertise rather than invent a statistical recipe.

Selection can bias a test when the same noise helps select and test the claimed effect. Not every subset analysis is circular: independent criteria or a valid separation under the null can be appropriate, with dependence respected. Explain the actual family and aim when multiple comparisons matter; do not demand correction for imaginary unperformed tests. Neither a bootstrap, a correction label nor a small P value guarantees sound inference. Association, manipulation or adjustment alone also leaves causal assumptions to examine.

Theory is useful when it changes the measurement or prediction. A verbal cartoon can expose assumptions; equations can make their consequences more precise. A distribution may separate mechanisms that share a mean, or a model-implied rescaling may compare responses across conditions. Check whether actual precision can distinguish the predictions. A curve collapse or fit alone need not identify a unique mechanism. Retrospective explanation remains legitimate, while observations used to tune a model are not thereby an independent predictive test.

## Failed, inconclusive and contrary evidence

Retain observations that disagree with the preferred account. Distinguish a failed manipulation/control, a valid but imprecise comparison and a credible result against the model's actual prediction under the tested conditions. Repeated failure is not automatically the researcher's fault, and a local retry heuristic is not a universal threshold.

A working control does not alone make nondetection evidence of biological absence. Ask which effect sizes remain compatible with the measurement and uncertainty. An appropriate sufficiently precise comparison can challenge a predicted response without proving exact zero or absence in every condition. Practical equivalence needs a meaningful margin and suitable analysis; a large N, a nonsignificant P value or a small estimate alone does not establish it. Keep that scientific conclusion separate from whether another experiment is worth the resources.

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

Use this comparison only when choosing between approaches is genuinely unclear; an adequately supported bounded claim needs no compulsory extra row or method.

| Claim | Current evidence | Consequential ambiguity | Useful next evidence, if any | Why it changes the decision |
|---|---|---|---|---|
| Mechanism, association, prediction, or explanation | Data/method used now | What it cannot see | Pilot, perturbation, comparison, model, or integration | Decision impact |

## Examples

- If a dataset suggests a pattern, identify its exploratory status and what valid evidence would support the proposed inference; do not order further exploration or a new experiment regardless of the task.
- If the user has a mechanism story, ask what perturbation or prediction would distinguish it from alternatives.
- If a method has narrow scale coverage, pair it with a complementary check only when the blind spot affects the claim.

## When Not To Apply This

Do not use this playbook as a protocol generator. It selects experiment strategy, not exact bench or code implementation.
