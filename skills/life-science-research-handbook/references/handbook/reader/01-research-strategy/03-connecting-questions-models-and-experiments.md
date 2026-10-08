<a id="quarto-document-content"></a> 

<a id="title-block-header"></a>

<a id="models-chapter"></a>

# Connecting questions, models and experiments

You may need to describe a pattern before trying to explain it: when does the response appear, how much does it vary, and does it recur? Once you have possible explanations, choose a comparison for which they predict different results. Then check whether your measurement can detect that difference.

<a id="models-question"></a>

## Defining the question

The question states what you want to learn. A hypothesis offers a possible answer; a model describes how the proposed explanation works and what it assumes. A prediction states what you would expect to observe if the explanation and its assumptions hold. A statistical test can assess a difference between conditions, but that difference may have several biological explanations. [[5, pp. 723–724]](#ref-models-phillips2015theory); [[4]](#ref-models-makin2019).

Describing a response over time can be worthwhile before you have a mechanism to test. Decide which population you want to describe, what you will measure and how you will sample it. To investigate an unexpected pattern, you also need to understand how the method could produce it. Yanai and Lercher argue for moving between exploration and hypothesis testing as the work develops. Neither must always come first, and both depend on assumptions about the system and its measurements. [[7, pp. 2–4]](#ref-models-yanaiconversation2021).

Separate the observation from the explanation. Higher reporter fluorescence in dense cultures is an observation; communication between cells is one possible explanation. A question such as “Do these cells communicate?” leaves many choices hidden. Which cells, which response, under which conditions, and what would count as communication? A narrower question might ask whether something in medium conditioned by dense cultures increases a recipient population’s reporter response after a depleted nutrient has been restored.

“The cells warn their neighbors” may help you imagine a mechanism. To test it, ask whether a factor released by one population changes the response of another. You then need conditions that distinguish the factor’s action from other changes in the medium [[6, pp. 3–6]](#ref-models-yanai2020).

Keep the biological model and the measurement assumptions distinct. The biological model describes what produces the response. The measurement assumptions explain why your readout represents that response: whether fluorescence reflects promoter activity, whether a tag changes protein behavior, or whether a sample represents the population you intend to study. A precise measurement of the wrong proxy can produce a reproducible result without answering the biological question [[2, pp. 2–4]](#ref-models-jose2020illusions).

<a id="models-predictions"></a>

## Comparing predictions

Write a small set of plausible models, including an explanation that challenges your preferred one. For each, ask what should happen under the proposed intervention and why. A statement such as “expression will change” is rarely enough. Direction, timing, dependence on another factor, or the shape of a response may distinguish models that agree about an endpoint. If their predictions overlap, change the conditions or measure a different feature before treating the experiment as a test between them [[8, pp. 4–6]](#ref-models-yanaicontradictions2021).

A model can start as a verbal mechanism or a sketch. Mathematics becomes useful when it exposes an assumption or yields a prediction that the verbal account leaves vague. For example, two mechanisms may both predict an increase but differ in how the response depends on concentration. Check whether those predicted differences exceed the variation and resolution of the proposed assay. Adding equations does not help if the competing models remain indistinguishable at the conditions you can measure [[5, pp. 723–724 and 728]](#ref-models-phillips2015theory).

Explaining existing data is useful work. It can expose missing mechanisms and suggest the next comparison. However, a model adjusted to reproduce a dataset has not thereby passed an independent predictive test. Mark which observations shaped it and identify a prediction to examine with new data or data kept separate from model development. Theory can guide an experiment, and an unexpected observation can prompt a better theory; neither must come first in every project [[5, p. 728]](#ref-models-phillips2015theory); [[7, pp. 1–6]](#ref-models-yanaiconversation2021).

<a id="models-medium-example"></a>**Example: a proposed test of conditioned medium**

This fictional bacterial strain carries a promoter reporter. At a fixed sampling time, background-corrected fluorescence per viable cell is higher after exposure to cell-free medium conditioned by dense cultures than after fresh medium. A nutrient, N, is measured to be lower in the conditioned medium. These observations establish neither a signal nor its mechanism.

Consider two simple models. In A, N depletion alone causes the increase. In B, an extracellular factor released by the donor cells causes it, N depletion has no effect on its own, and the factor acts independently of N over the tested range. Compare the following conditions in recipient cultures started at the same density. “Baseline” means no increase relative to fresh medium; these are predictions, not results.

<table>
<colgroup>
<col>
<col>
<col>
</colgroup>
<thead>
<tr>
<th>Proposed condition</th>
<th>Model A: N depletion</th>
<th>Model B: N-independent factor</th>
</tr>
</thead>
<tbody>
<tr>
<td>Fresh medium</td>
<td>Baseline</td>
<td>Baseline</td>
</tr>
<tr>
<td>Untreated conditioned medium</td>
<td>Increased response</td>
<td>Increased response</td>
</tr>
<tr>
<td>Fresh medium with N lowered to the measured conditioned-medium level</td>
<td>Increased response</td>
<td>Baseline</td>
</tr>
<tr>
<td>Conditioned medium with N restored to the fresh-medium level</td>
<td>Baseline</td>
<td>Increased response</td>
</tr>
</tbody>
</table>

Both models predict an increase in untreated conditioned medium, so that comparison cannot distinguish them. They disagree about the two conditions in which N is changed. These test only the two explanations specified here. If the response increases in both, neither simple model accounts for the full pattern. Multiple causes or an interaction could be involved, but the result alone would not establish that two mechanisms coexist.

<a id="models-assumptions"></a>

## Assumptions and controls

Ask what else your intervention changes. Deleting a gene may induce compensation; adding a compound may affect growth, uptake or the reporter itself. A loss-of-function phenotype can support a role for the gene in the response, without showing how it acts. Likewise, reproducing a behavior with selected components shows what they can do together under those conditions. It does not establish that the intact organism uses the same mechanism [[2, pp. 2–5]](#ref-models-jose2020illusions).

In the medium example, restoring N must leave the proposed extracellular factor available and active for the table’s B prediction to hold. If N changes the factor’s stability or uptake, loss of the response after restoration could fit either explanation. Conversely, nutrient depletion can alter recipient physiology and reporter production. Dividing fluorescence by cell count addresses cell number, but does not automatically correct those effects. Keep the fluorescence, viable-cell counts and growth measurements available alongside the ratio.

Choose controls that check a specific possible problem. A negative control can reveal background or an effect of handling; a positive control can show that the assay responds in the medium being tested. Neither shows whether an unidentified factor survived a manipulation. If you cannot check that the factor remains active after restoring N, a loss of response will leave its possible role unresolved.

<a id="models-design"></a>

## Designing the experiment

Specify what is independently sampled or assigned to treatment. Many cells from one culture describe that culture more precisely, but do not replace independent cultures when the question concerns variation between cultures. Split samples can provide useful paired comparisons; preserve that pairing in the analysis. State the direct contrast that answers the question. A significant response in one condition and a non-significant response in another do not establish that the responses differ [[4]](#ref-models-makin2019).

Keep treatment groups comparable in handling, timing and measurement. Calibrate the assay and consider how a systematic error could survive repeated runs. A second method is useful when it challenges a different possible error; repeating the same proxy with a new label may preserve the same weakness [[1, chapter 5]](#ref-models-goslingnoordam2022thesis); [[4]](#ref-models-makin2019).

Suppose all treated cultures are measured on Monday and all controls on Tuesday. A difference then combines treatment with whatever changed between days. Measuring more cells on each day can make that difference look precise without separating its causes. If both conditions can be measured on each day, the within-day comparison is more informative. Random allocation reduces systematic assignment differences; blinding addresses a different problem, such as scoring borderline cells more generously when you expect a treatment to work. Neither repairs an assay that measures the wrong quantity. [[4]](#ref-models-makin2019); [[1, chapter 5]](#ref-models-goslingnoordam2022thesis).

<a id="models-plan-example"></a>**Experimental plan for the fictional medium comparison**

**Question:** Does N depletion account for the reporter increase, or does activity remain after N restoration?

**Manipulations:** Prepare the four medium conditions in the prediction table. Verify N concentration after preparation. Match pH, added volume and vehicle, exposure time and recipient starting density.

**Measurement:** At the specified sampling time, measure background-corrected reporter fluorescence and viable-cell count separately, then calculate fluorescence per viable cell. Track growth to identify physiological differences that complicate the ratio.

**Sampling and allocation:** Grow independent donor cultures and split each conditioned-medium preparation between untreated and N-restored conditions. Use independent recipient cultures and distribute all four conditions across experimental batches. Preserve donor pairing and recipient identity; extra aliquots are not extra donor cultures.

**Assay checks:** Include a reporter-free background control and a validated reporter-inducing positive control in each medium matrix. Verify that the recipient population remains viable. These checks address detection and recipient competence; they leave the preservation of an unknown factor unresolved.

**Analysis and decision:** Estimate N-lowered fresh medium versus fresh medium, N-restored conditioned medium versus untreated conditioned medium, and N-restored conditioned medium versus fresh medium. Retain the paired structure for the conditioned-medium comparison. Choose replication after assessing variation and the smallest response difference that would separate the predictions. Fix the primary comparisons, sampling time and exclusion criteria before the discriminating experiment; record additional analyses as exploratory.

**Assumption that could defeat the test:** N restoration may interfere with the factor. If that cannot be excluded, an A-like pattern will remain compatible with an N-dependent extracellular mechanism. A B-like pattern would motivate identifying the active component and challenging its action with a different approach; it would not establish direct promoter regulation.

**When you cannot check the key assumption.** Suppose the factor is still unidentified, so you cannot measure its activity independently after restoring N. You could develop that measurement before running the comparison. Alternatively, you could run the comparison now to find out whether restoring N changes the reporter response. A loss of response would then leave two explanations open: N depletion caused the increase, or restoring N interfered with a factor that caused it. Decide whether learning about the reporter response alone is worth the experiment, or whether you need a different way to distinguish the explanations. Repeating the same ambiguous comparison more precisely will not settle which explanation applies.

<a id="models-results"></a>

## Interpreting negative and inconclusive results

A result can challenge your preferred model only if the manipulation worked and the assay could detect the predicted response. Check these points whether the result agrees or disagrees with your expectation. A failed control, a failed manipulation and an imprecise estimate each require a different next step [[3]](#ref-models-kamounlab2021failed).

<table>
<colgroup>
<col>
<col>
<col>
</colgroup>
<thead>
<tr>
<th>Possible outcome</th>
<th>What it establishes</th>
<th>Next action</th>
</tr>
</thead>
<tbody>
<tr>
<td>The manipulation and assay checks pass; the estimated response is precise enough to exclude the increase predicted by the model</td>
<td>Evidence against that prediction under the tested conditions</td>
<td>Revise the model or its stated domain; develop a new discriminating prediction</td>
</tr>
<tr>
<td>The positive control fails in the experimental matrix</td>
<td>The absent response cannot distinguish biological absence from detection failure</td>
<td>Diagnose the assay or matrix before interpreting the biological comparison</td>
</tr>
<tr>
<td>The manipulation did not achieve its intended change</td>
<td>The proposed intervention was not tested</td>
<td>Repair or replace the manipulation</td>
</tr>
<tr>
<td>The checks pass, but uncertainty allows both little response and the predicted increase</td>
<td>The data do not resolve the relevant difference</td>
<td>Improve precision or choose a contrast with better separated predictions</td>
</tr>
</tbody>
</table>

A non-significant test alone cannot tell these situations apart. Define the response magnitude that matters for the prediction, then assess the estimate and uncertainty against it. A sufficiently precise result may constrain an effect of that size; it does not prove an exact zero or absence in every condition. Select any equivalence or other absence-testing procedure with its assumptions and decision threshold before using it to interpret the outcome. See [showing observations and uncertainty](../03-data-visualization/02-showing-observations-and-uncertainty.md#uncertainty-effects) for estimates and intervals [[4]](#ref-models-makin2019).

<a id="models-update"></a>

## Revising the explanation

If the medium comparison follows B’s predictions, something other than simple N depletion is needed to explain the response. The experiment would not identify the factor or show how it affects the reporter. Those questions would still need to be investigated.

An unexpected pattern may suggest a model you had not considered. Record which explanation arose after seeing the results, then test a prediction with observations you did not use to develop it. Check whether a technical problem could explain a contradictory result. If the measurements hold up, reconsider the explanation rather than changing analyses or rejecting observations until they fit it [[7, pp. 5–6]](#ref-models-yanaiconversation2021); [[8, pp. 4–6]](#ref-models-yanaicontradictions2021).

<a id="models-references"></a>

## References

1. <a id="ref-models-goslingnoordam2022thesis"></a>[Gosling, P., & Noordam, B. (2022). **Mastering Your PhD: Survival and Success in the Doctoral Years and Beyond.** 3rd ed. Springer Nature Switzerland AG. Chapters 4–5.](https://doi.org/10.1007/978-3-031-11417-5)

2. <a id="ref-models-jose2020illusions"></a>[Jose, A. M. (2020). **Philosophy of Biology: The analysis of living systems can generate both knowledge and illusions.** *eLife*, 9, e56354.](https://doi.org/10.7554/eLife.56354)

3. <a id="ref-models-kamounlab2021failed"></a>[KamounLab. (2021). **What’s a failed experiment?** *Medium*, 11 October.](https://kamounlab.medium.com/whats-a-failed-experiment-7ea66fd96f8)

4. <a id="ref-models-makin2019"></a>[Makin, T. R., & Orban de Xivry, J.-J. (2019). **Science Forum: Ten common statistical mistakes to watch out for when writing or reviewing a manuscript.** *eLife*, 8, e48175.](https://elifesciences.org/articles/48175)

5. <a id="ref-models-phillips2015theory"></a>[Phillips, R. (2015). **Theory in Biology: Figure 1 or Figure 7?** *Trends in Cell Biology*, 25(12), 723–729.](https://doi.org/10.1016/j.tcb.2015.10.007)

6. <a id="ref-models-yanai2020"></a>[Yanai, I., & Lercher, M. (2020). **The two languages of science.** *Genome Biology*, 21, 147.](https://doi.org/10.1186/s13059-020-02057-5)

7. <a id="ref-models-yanaiconversation2021"></a>[Yanai, I., & Lercher, M. (2021). **The data-hypothesis conversation.** *Genome Biology*, 22, 58.](https://doi.org/10.1186/s13059-021-02277-3)

8. <a id="ref-models-yanaicontradictions2021"></a>[Yanai, I., & Lercher, M. (2021). **Novel predictions arise from contradictions.** *Genome Biology*, 22, 153.](https://doi.org/10.1186/s13059-021-02371-6)
