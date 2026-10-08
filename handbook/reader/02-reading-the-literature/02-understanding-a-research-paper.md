<a id="quarto-document-content"></a> 

<a id="title-block-header"></a>

<a id="paper-reading-chapter"></a>

# Understanding a research paper

You may understand every word in a paper yet be unsure why an experiment supports its conclusion. Work through that connection using the figures, captions and relevant methods. Aim to explain what the study found and which questions remain open.

<a id="paper-reading-purpose"></a>

## What do you need from the paper?

Decide what you need from this paper: orientation in an unfamiliar field, evidence for a particular claim, a method you might adopt or preparation for a discussion. That purpose changes where to spend time. For orientation, the Introduction can identify the question and useful earlier work. To adopt a method, concentrate on the procedure, its validation and conditions of use. To rely on a biological conclusion, follow the experiments supporting it, including controls and supplementary material [[1, Rules 1–3]](#ref-paper-reading-carey2020reading).

Identify the article type as well. A review can orient you and lead to original studies; its account of an experiment is not a substitute for reading that experiment when your conclusion depends on it. A methods paper needs evidence about performance and limits. An original research article presents observations and an argument about what they mean. The workflow below concentrates on that argument.

Begin with enough of the abstract and Introduction to state the question and proposed answer. Then move between Results, figures and methods. Reading the figures first can work when you know the system; reading each Results passage alongside its figure can work when you need more context. Neither order is compulsory. Look up an unfamiliar term or follow a cited method when it blocks your understanding of a consequential step, rather than allowing every unfamiliar word to start a separate literature search [[1, Rules 4 and 8]](#ref-paper-reading-carey2020reading).

For an overview, it may be enough to understand the question, approach and main finding. Before adopting a method, check how its performance was assessed and whether that assessment covers the samples you plan to use. Before citing a proposed mechanism as established, read the experiments that distinguish it from other explanations. Note anything you still need to check.

<a id="paper-reading-argument"></a>

## Following the argument

State the research question in your own words, then identify the comparison intended to answer it. What changed between the groups or conditions? What was measured? Why would that measurement help answer the question?

Follow the main claim through its supporting experiments. One may establish that the measurement works, another show a response and another test an alternative explanation. The order of Results usually expresses this logic rather than the order in which the work happened. Ask what each experiment adds and which later conclusion depends on it [[3, Rule 7]](#ref-paper-reading-mensh2017).

Write an observation before accepting the interpretation: *reporter fluorescence was lower* describes a measurement; *the treatment suppresses a specific pathway* proposes why it changed. Results headings and figure titles can contain interpretations too. Check whether the panels support them [[1, Rules 3–6]](#ref-paper-reading-carey2020reading).

<a id="paper-reading-reporter-example"></a>**Example: what a reporter measurement establishes**

In this fictional paper, cultured cells receive inhibitor Q or vehicle. At six hours, Figure 1A shows lower background-corrected whole-well reporter fluorescence with Q. The authors propose that Q suppresses the reporter through a specific molecular target. The material considered so far does not identify viable-cell number or fluorescence per cell.

<table>
<colgroup>
<col>
<col>
</colgroup>
<thead>
<tr>
<th>Part of the argument</th>
<th>What the reader can establish</th>
</tr>
</thead>
<tbody>
<tr>
<td>Question</td>
<td>Does Q suppress reporter activity through the proposed target?</td>
</tr>
<tr>
<td>Observation</td>
<td>Whole-well fluorescence is lower with Q than with vehicle at six hours.</td>
</tr>
<tr>
<td>Unresolved inference</td>
<td>Total signal depends on contributing cells and their signal. This measurement alone does not distinguish fewer cells from lower signal per cell, or establish target specificity.</td>
</tr>
</tbody>
</table>

To assess the proposed mechanism, look for measurements of cell number and signal per cell, then for experiments testing whether Q acts through the proposed target. The whole-well measurement alone cannot answer those questions.

<a id="paper-reading-figures-methods"></a>

## Figures and methods

For each panel supporting the conclusion, establish what its points or other marks represent. A point may be a cell, a culture, an animal or an average across several measurements. Read the axes, units, group labels and legend. Check whether values are totals, proportions or normalized measurements. For a fold change, identify the baseline used to calculate it [[1, Rule 4]](#ref-paper-reading-carey2020reading).

Use the caption to find the relevant method. Follow how samples were selected and measured, then how those measurements became the plotted values. For a normalized result, find the denominator; for an analysis that excludes observations, find the exclusion criteria. These details may be in supplementary methods.

In the reporter example, background correction does not account for how many viable cells contribute to the signal. The measurement also tells you only what happened at six hours, not when the response began or how long it lasts.

Ask whether the display supplies the evidence claimed. A representative image can show a phenotype, but to assess how common it is, you need to know how samples were selected and how the phenotype was counted. A smooth curve may be a fitted model rather than additional observations. For an unfamiliar figure type, consult [specialized displays and explanatory diagrams](../03-data-visualization/05-specialized-displays-and-explanatory-diagrams.md#specialist-chapter), then return to the paper’s caption and methods to check how it was constructed.

If a necessary detail remains missing, name it specifically. “The caption does not identify whether points are cultures or repeated measurements from one culture” is a question you can resolve. “The experiment is unreliable” goes beyond what that absence establishes.

<a id="paper-reading-inference"></a>

## Assessing the evidence

Examine controls by the alternative explanation they address. In a before-and-after experiment, a change may reflect elapsed time or repeated measurement as well as the intervention. A suitable concurrent control helps separate these effects. In the reporter example, vehicle supplies a treatment comparison, but it does not by itself settle cell number, assay interference or target specificity. Read what the controls test and what they leave open [[2]](#ref-paper-reading-makin2019).

Also identify the independent units behind the comparison. Repeated images from one culture can describe that culture more thoroughly; they do not create additional independently treated cultures. Check how the analysis handles this dependence and whether the replication supports the scope of the claim. If the paper says the treatment works differently in two conditions, look for a direct comparison of those effects. A significant result in one condition and a non-significant result in the other does not establish that they differ [[2]](#ref-paper-reading-makin2019).

Read the estimated effect together with its uncertainty. Identify what error bars represent: standard deviation describes spread among observations; standard error or a confidence interval concerns precision of an estimate. To compare groups, look for an analysis of their difference rather than judging whether their separate error bars overlap [[4, pp. 186–191]](#ref-paper-reading-wilke2019). See [showing observations and uncertainty](../03-data-visualization/02-showing-observations-and-uncertainty.md#uncertainty-effects) for an explanation of these intervals.

A non-significant result alone does not establish that an effect is absent. Check the range of effects compatible with the estimate and its uncertainty interval. If that range includes both no change and the change predicted by a proposed mechanism, the measurement does not resolve the prediction. A narrower interval may rule out an effect as large as predicted without establishing an exact zero. Base that judgment on the analysis the paper reports [[2]](#ref-paper-reading-makin2019).

Distinguish an association, the effect of an intervention and evidence for its mechanism. Observational covariation can have several explanations. Manipulating a treatment strengthens some inferences, but the treatment may act through routes other than the proposed one. Ask which experiment distinguishes those routes before describing the mechanism as established [[2]](#ref-paper-reading-makin2019).

Judge a descriptive study by the description it supports. An atlas need not identify a mechanism to be useful, but its coverage depends on which specimens, conditions and measurements it includes. Ask whether the sampling supports the claimed population and whether the method could miss the feature being described. A missing mechanism and an inadequate measurement are different limitations. [[1, Rules 3–6]](#ref-paper-reading-carey2020reading).

Apply the same scrutiny to findings you agree with and those you doubt. Would you ask for the same control if the result supported your expectations? Distinguish a missing explanation of a method from evidence that the method was used incorrectly. Likewise, a study confined to one cell model may answer its stated question while leaving open whether the finding applies elsewhere [[1, Rules 6–7]](#ref-paper-reading-carey2020reading).

<a id="paper-reading-account"></a>

## Taking useful notes

Close the paper and explain the question, main evidence and conclusion in a few sentences, including any important limits. Then reopen it to check your account and add the relevant figure, table or method locations. If you cannot explain a step, reread it or discuss it with someone who understands the method [[1, Rules 3, 8–9]](#ref-paper-reading-carey2020reading).

Keep the paper’s citation or stable link with the note. Include the experimental system, treatment and measurement time when these define the finding you plan to use. In the reporter example, the note needs to say that the measurement is whole-well fluorescence in cultured cells at six hours. Separate what the authors conclude from what you have checked yourself.

<a id="paper-reading-note-example"></a>**Example: a short reading note**

The paper asks whether inhibitor Q suppresses reporter activity through its proposed target. In cultured cells, Q produces lower background-corrected whole-well fluorescence than vehicle at six hours (Fig. 1A). The authors interpret it as target-specific suppression, but I have not yet found viable-cell counts or per-cell signal measurements. Replication and estimate precision also need checking in the caption and Methods. Before using the paper as evidence for the mechanism, I need to look for cell-normalized measurements and experiments testing target specificity.

Suppose you then find an additional panel reporting fewer viable cells with Q. Update the note:

The additional viable-cell-count panel shows fewer viable cells with Q. Cell number may therefore contribute to the lower whole-well fluorescence. The findings still do not establish whether signal per viable cell changes or whether the proposed target mediates the response. I will look for a per-cell measurement, check how it was obtained and examine whether specificity experiments distinguish the proposed mechanism from other effects of Q.

Fewer viable cells alone do not establish how much of the fluorescence difference is explained by cell number.

If you are preparing a journal review, see [writing the report](../08-publishing/02-reviewing-a-manuscript.md#review-report) for organizing your comments.

<a id="paper-reading-references"></a>

## References

1. <a id="ref-paper-reading-carey2020reading"></a>[Carey, M. A., Steiner, K. L., & Petri, W. A., Jr. (2020). **Ten simple rules for reading a scientific paper.** *PLOS Computational Biology*, 16(7), e1008032.](https://doi.org/10.1371/journal.pcbi.1008032)

2. <a id="ref-paper-reading-makin2019"></a>[Makin, T. R., & Orban de Xivry, J.-J. (2019). **Science Forum: Ten common statistical mistakes to watch out for when writing or reviewing a manuscript.** *eLife*, 8, e48175.](https://elifesciences.org/articles/48175)

3. <a id="ref-paper-reading-mensh2017"></a>[Mensh, B., & Kording, K. (2017). **Ten simple rules for structuring papers.** *PLOS Computational Biology*, 13(9), e1005619.](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005619)

4. <a id="ref-paper-reading-wilke2019"></a>[Wilke, C. O. (2019). **Fundamentals of Data Visualization: A Primer on Making Informative and Compelling Figures.** O’Reilly Media.](https://clauswilke.com/dataviz/)
