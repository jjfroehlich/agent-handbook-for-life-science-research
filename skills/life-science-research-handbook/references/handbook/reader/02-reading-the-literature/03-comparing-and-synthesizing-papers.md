<a id="quarto-document-content"></a> 

<a id="title-block-header"></a>

<a id="synthesis-chapter"></a>

# Comparing and synthesizing papers

Before deciding whether papers agree, check what each study measured and under which conditions. An increase in RNA and no detectable increase in protein may both be accurate observations. To explain what the studies show together, you need to keep that difference in view.

<a id="synthesis-question"></a>

## Defining the review question

State the question you want the papers to answer. “Does this pathway matter?” could mean a role in development, a molecular response or survival after treatment. “Does inhibiting the pathway reduce cell survival in this model?” is specific enough to guide paper selection. A developmental study may suggest a mechanism to investigate, but it does not directly answer the survival question.

Decide which systems, interventions and outcomes belong in the comparison before selecting papers by their conclusions. Record how you searched, when you searched and why you excluded papers; note papers you could not obtain. A reader should be able to tell whether your account covers a few selected studies or a search intended to find all the evidence on the question [[3, Rules 1–2 and 9]](#ref-synthesis-pautasso2013).

A review can orient you to the concepts and point toward original work. For a conclusion that depends on a particular experiment, inspect that experiment’s paper and relevant supplementary material. Keep a review’s account separate from your assessment of the primary evidence. Before describing an unresolved question, check both recent work and older studies that the current discussion may have overlooked [[3, Rule 10]](#ref-synthesis-pautasso2013).

<a id="synthesis-comparison"></a>

## Comparing methods and evidence

Compare the studies side by side, using the same fields for each. Record where you found each detail so you can return to the figure, table or Methods passage when a difference needs checking.

<table>
<colgroup>
<col>
<col>
</colgroup>
<thead>
<tr>
<th>Record</th>
<th>What to establish</th>
</tr>
</thead>
<tbody>
<tr>
<td>Question and system</td>
<td>Which biological question, organism, cell type, population or state does the study address?</td>
</tr>
<tr>
<td>Intervention and comparator</td>
<td>What changes, at what dose or intensity, and relative to what control? Is the study observational or experimental?</td>
</tr>
<tr>
<td>Timing</td>
<td>When does the intervention occur, and when is the outcome measured?</td>
</tr>
<tr>
<td>Measurement</td>
<td>What quantity is measured, with what assay, normalization and units?</td>
</tr>
<tr>
<td>Replication</td>
<td>What are the independent biological units? Which measurements repeat within them?</td>
</tr>
<tr>
<td>Finding and uncertainty</td>
<td>What is the effect estimate or observed pattern? How precise is it, and what analysis supports it?</td>
</tr>
<tr>
<td>Inference and limits</td>
<td>What conclusion follows, and what alternative explanation or missing control remains?</td>
</tr>
</tbody>
</table>

Do not fill an absent detail with an assumption. Mark it as unreported or not yet checked and return to the source if it affects comparability. These fields extend the distinction between question, approach, observation and interpretation used by Carey and colleagues [[1, Rules 3–6 and 8]](#ref-synthesis-carey2020reading).

Check what each study means by “pathway inhibition.” A drug may only partly inhibit its target and may affect other targets too. Deleting a gene produces a different perturbation. Check how long each treatment acts before treating the experiments as equivalent.

Also check how the measurements were normalized. Total fluorescence per well depends on how many cells are present as well as their fluorescence. A measurement divided by the number of viable cells accounts for cell number differently; the two values cannot be compared directly. For fold changes, identify the baseline in each study before comparing the reported effects.

Evaluate the evidence for the particular claim you need. A strong observational association may establish a relationship while leaving its cause unresolved. An intervention can narrow causal explanations, but its controls and possible additional effects still matter. Likewise, many measurements from a few cultures do not provide the same biological replication as independently initiated cultures [[2]](#ref-synthesis-makin2019).

Check whether papers reuse a cohort, dataset or experimental series. Analyses of the same observations may answer different questions, but they do not show that a finding recurs in a new sample. Record which papers share data. When studies address different questions or measurements, compare them in separate groups and explain how the groups relate.

Repeating an experiment in independent samples tests whether the finding recurs. Using a different method may help determine whether it depends on a weakness of the first assay. Check what changed in each additional study: repeating the same assay can repeat its bias, and a second method needs its own validation.

<a id="synthesis-disagreement"></a>

## Explaining differences between studies

First ask whether the studies disagree about the same quantity under comparable conditions. An increase in mRNA and an unchanged protein estimate are distinct observations. They can both be accurate; neither alone establishes how RNA changes lead to protein changes. Similarly, a short perturbation and a long depletion can reveal different parts of a response.

Compare the estimated effects and their uncertainty, not just their significance labels. A statistically significant result in one study and a non-significant result in another do not establish that their effects differ. The second estimate may be too imprecise to distinguish no effect from an effect as large as the first study reports. To claim that the effects differ, you need an analysis of that difference; judging overlap or nonoverlap of their separate confidence intervals is not a general substitute [[2]](#ref-synthesis-makin2019). See [showing observations and uncertainty](../03-data-visualization/02-showing-observations-and-uncertainty.md#uncertainty-effects) for the distinction between separate estimates and an estimate of their difference.

When studies of the same outcome still give different findings, examine how their methods differ. Start with differences that could affect the measurement or the biological response. For example, a longer exposure might allow a response to develop. That explanation predicts a change over time that could be tested. Finding a difference in exposure time does not by itself establish why the results differ.

If several explanations remain possible, say which ones and what evidence would distinguish them. Apply the same scrutiny to findings you favor and those you doubt. An unexplained disagreement belongs in the synthesis even when you cannot yet resolve it [[4, pp. 4–6]](#ref-synthesis-yanaicontradictions2021).

<a id="synthesis-comparison-example"></a>**Example: compare the evidence behind different conclusions**

The following three study summaries are fictional. They ask whether ligand L changes marker M in cultured epithelial cells. All use the same stated cell model, ligand dose, exposure conditions, vehicle comparator and two-hour endpoint. Independently initiated cultures are the biological replication units. The values are authored study reports, not results calculated from a dataset. Fold changes compare L with vehicle; CI denotes the reported confidence interval.

<table>
<thead>
<tr>
<th>Study</th>
<th>Outcome</th>
<th>Fold change</th>
<th>95% CI</th>
</tr>
</thead>
<tbody>
<tr>
<td>A</td>
<td>M mRNA</td>
<td>1.4</td>
<td>1.2–1.6</td>
</tr>
<tr>
<td>B</td>
<td>M protein abundance</td>
<td>1.0</td>
<td>0.9–1.1</td>
</tr>
<tr>
<td>C</td>
<td>M mRNA</td>
<td>1.3</td>
<td>0.9–1.7</td>
</tr>
</tbody>
</table>

A fold change of 1 means equal abundance. Study A supports increased mRNA. Study C’s estimate is in the same direction but is less precise, allowing no change as well as an increase. Its interval crossing 1 does not show that it contradicts A. No direct comparison of the study effects is supplied.

B measures a different outcome. Its protein estimate is near 1 with the stated interval; this does not refute A’s mRNA finding or prove that protein abundance cannot respond. A delay between the RNA and protein responses is one possible explanation, but these reports contain no later measurement that tests it.

Suppose you need to choose a follow-up now. If you need to know whether the RNA increase recurs, repeat the two-hour RNA measurement. If you need to know whether protein abundance rises later, measure it at later times. The reports alone do not tell you which question to prioritize, and they leave the delay explanation untested.

<a id="synthesis-writing"></a>

## Writing the synthesis

Organize each paragraph around a question that the studies help answer. You might first explain whether the outcome changes, then discuss the evidence for a mechanism or for a response in other systems. Within each paragraph, show how the findings relate: one study may establish an observation while another tests whether it occurs under different conditions [[3, Rules 4 and 6–7]](#ref-synthesis-pautasso2013).

State what the studies establish together and explain which findings support that answer. Keep the relevant conditions and uncertainty beside the conclusion. “These results are consistent with a delayed protein response” allows other explanations; “the protein response is delayed” asserts that this explanation has been established. If the studies still conflict, identify what remains unresolved.

For the fictional studies, the completed synthesis could read:

<a id="synthesis-worked-output"></a>**Synthesis of studies A–C**

Ligand L increased marker M mRNA after two hours in the epithelial-cell model examined by study A. Study C estimated an increase of similar magnitude, although its uncertainty interval also allowed no change. The mRNA findings therefore do not establish a disagreement between these studies. Study B measured protein abundance and reported an estimate near no change at the same endpoint. Together, the studies support an mRNA response at two hours more clearly than a protein response at that endpoint. Whether the mRNA change produces a later protein increase remains unresolved; measurements of both outcomes over time would help distinguish that possibility from a response confined to mRNA abundance.

Check each conclusion against the original studies. In the example, the measurements concern a particular marker in one cell model at two hours; they do not establish a general effect on gene expression or a response at later times. Ask a colleague to check your interpretation and identify missing details that could change it [[3, Rule 8]](#ref-synthesis-pautasso2013).

A synthesis for a whole field needs a search and appraisal design suited to that purpose. Quantitative pooling also requires comparable quantities and an analysis that accounts for their uncertainty and dependence.

<a id="synthesis-references"></a>

## References

1. <a id="ref-synthesis-carey2020reading"></a>[Carey, M. A., Steiner, K. L., & Petri, W. A., Jr. (2020). **Ten simple rules for reading a scientific paper.** *PLOS Computational Biology*, 16(7), e1008032.](https://doi.org/10.1371/journal.pcbi.1008032)

2. <a id="ref-synthesis-makin2019"></a>[Makin, T. R., & Orban de Xivry, J.-J. (2019). **Science Forum: Ten common statistical mistakes to watch out for when writing or reviewing a manuscript.** *eLife*, 8, e48175.](https://elifesciences.org/articles/48175)

3. <a id="ref-synthesis-pautasso2013"></a>[Pautasso, M. (2013). **Ten Simple Rules for Writing a Literature Review.** *PLOS Computational Biology*, 9(7), e1003149.](https://doi.org/10.1371/journal.pcbi.1003149)

4. <a id="ref-synthesis-yanaicontradictions2021"></a>[Yanai, I., & Lercher, M. (2021). **Novel predictions arise from contradictions.** *Genome Biology*, 22, 153.](https://doi.org/10.1186/s13059-021-02371-6)
