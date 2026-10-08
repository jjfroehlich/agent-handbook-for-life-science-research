<a id="quarto-document-content"></a> 

<a id="title-block-header"></a>

<a id="reporting-chapter"></a>

# Methods, results and figure legends

Draft Methods from the experimental records and analysis code, Results from the figures, and legends alongside each display. As you write, check that all three describe the same samples, measurements and comparisons. A change to the analysis may require a correction in each place. [[1]](#ref-reporting-pain2023); [[2]](#ref-reporting-capra2022).

The examples continue the fictional [Brake study](01-planning-the-paper.md#brake-case), inspired by Tang and colleagues (2024) [[12]](#ref-reporting-tang2024).

<a id="reporting-readers"></a>

## Plan what readers need

<a id="reporting-placement"></a>

### Where details belong

Place details according to the question they answer. [[3]](#ref-reporting-zhang2014); [[4]](#ref-reporting-scitable).

<a id="reporting-component-guide"></a>**Where the information belongs**

<table>
<colgroup>
<col>
<col>
<col>
</colgroup>
<thead>
<tr>
<th>Component</th>
<th>Main question</th>
<th>Information to provide</th>
</tr>
</thead>
<tbody>
<tr>
<td>Methods</td>
<td>How was the evidence obtained?</td>
<td>Design, materials, procedures, measurements, processing and analysis choices needed to evaluate and reproduce the work.</td>
</tr>
<tr>
<td>Results</td>
<td>What did the study find?</td>
<td>The question or comparison, principal finding, quantitative support and qualifications that affect its interpretation.</td>
</tr>
<tr>
<td>Figure legend</td>
<td>What am I looking at?</td>
<td>Figure topic, panel descriptions, experimental context, visual encodings and statistical details needed to read the display.</td>
</tr>
</tbody>
</table>

The same treatment may need three different descriptions: how it was applied in Methods, what it changed in Results, and which marks represent it in the figure legend. Give readers the context they need at each point, while describing the full protocol once. [[2]](#ref-reporting-capra2022); [[5]](#ref-reporting-bioturing2018).

<a id="reporting-reader-detail"></a>

### Choose how much detail to include

State which population was sampled and what was compared, even for a specialist audience. Define scores developed for the study. Before describing an unfamiliar analysis, explain the question it answers so readers know why you used it. [[3]](#ref-reporting-zhang2014); [[6]](#ref-reporting-huber2025).

Use prose for procedures and reasons, tables for repeated fields, and a schematic when several inputs follow different paths into an analysis. Keep exact settings in Methods. [[4]](#ref-reporting-scitable).

Supporting material can hold detailed procedures and extended analyses. Keep the evidence essential to the main conclusion accessible in the paper, with precise references to supporting displays and controls. [[3]](#ref-reporting-zhang2014).

<a id="reporting-methods"></a>

## Write reproducible Methods

<a id="reporting-methods-order"></a>

### Organizing Methods

Begin with the design and materials, then describe measurement, processing and analysis. Within a procedure, preserve the order of operations; across procedures, group shared methods so readers encounter each protocol once. [[7]](#ref-reporting-lafferty2016); [[8]](#ref-reporting-wilke2013). Open each subsection with its purpose or material, explaining unusual choices that affect interpretation before describing the steps. [[4]](#ref-reporting-scitable).

Write completed work in the past tense, choosing the subject that makes the procedure easiest to follow. Active sentences often clarify responsibility; passive wording works when the sample or procedure is the natural subject. [[6]](#ref-reporting-huber2025); [[4]](#ref-reporting-scitable). Have contributing authors check the account against their records and final code, including the steps where data passed between collaborators. [[1]](#ref-reporting-pain2023); [[2]](#ref-reporting-capra2022).

<a id="reporting-methods-detail"></a>

### Include the details that determine the outcome

Identify the materials or datasets and their sources, inclusion criteria, conditions and controls. Give laboratory settings needed to repeat the procedure, and identify datasets by accession or durable reference and relevant release. A table can collect reagent or dataset identities; the prose should explain how they were used. [[2]](#ref-reporting-capra2022); [[7]](#ref-reporting-lafferty2016).

Consult study-specific reporting requirements for additional details. Obtain details of the required ethics approvals and compliance information from the responsible investigators, identifying the samples or procedures they cover. [[2]](#ref-reporting-capra2022); [[7]](#ref-reporting-lafferty2016).

Describe how samples were allocated, when measurements were taken and how randomization or blinding operated when used. If a safeguard was absent, report that accurately and assess its effect on the conclusion. [[9]](#ref-reporting-makin2019).

For an established protocol, cite the version used and describe what you changed. The phrase “with minor modifications” does not tell someone repeating the work which steps to follow. [[7]](#ref-reporting-lafferty2016); [[2]](#ref-reporting-capra2022). For computational procedures, report filtering, reference annotations, normalization and thresholds because they can affect the result. Routine file-handling operations usually need no description. [[2]](#ref-reporting-capra2022); [[4]](#ref-reporting-scitable).

<a id="reporting-methods-example"></a>**Example: describing a matched comparison**

The Brake study compares infectious phage output across three bacterial genotypes. The values and design details below are invented for teaching. This excerpt covers titre calculation and analysis; the host, constructs, infection conditions and collection protocol would be specified elsewhere in Methods.

<a id="reporting-published-methods"></a>

**Infectious-titre analysis**

We compared empty-vector cultures, cultures carrying intact Brake and cultures carrying Brake with a catalytically inactive reverse transcriptase. On each of six experimental days, one independently started culture of each genotype was infected with phage A and sampled at the same endpoint.

For each culture, we estimated infectious titre in plaque-forming units per millilitre (PFU/mL) from technical duplicate plaque counts, accounting for the plated volumes and dilution factors. We combined the duplicate measurements into one culture-level estimate.

The primary comparison was intact Brake versus empty vector, matched by experimental day. We divided the intact-Brake titre by the empty-vector titre within each day and took the log10 of that ratio. We estimated the mean log10 ratio and its two-sided 95% confidence interval using a Student t distribution with five degrees of freedom. We exponentiated the estimate and interval limits to obtain a geometric mean titre ratio. Fold reduction was its reciprocal, with the interval limits inverted accordingly. The inactive reverse-transcriptase measurements were displayed as a mechanistic control.

**What to notice.** Each day contributes one matched contrast. Duplicate plates improve the measurement of a culture; they do not double the sample size. The analysis is specified for the between-genotype effect, rather than inferred from separate error bars on each group.

<a id="reporting-analysis"></a>

### Describe the analysis from input to inference

Describe how the input becomes the reported result. Identify the input data and version, then explain processing in order, naming the software and settings that affect the output. For genomic analyses, give the reference assembly. State what the final comparison or model estimates. Readers should be able to follow that account in Methods without having to reconstruct it from the code. [[2]](#ref-reporting-capra2022); [[6]](#ref-reporting-huber2025).

Explain selection and exclusion before presenting findings from the selected data. State how samples, genes, cells or regions entered the analysis and how many remained where counts affect interpretation. Distinguish prespecified decisions from choices made after inspecting the results. A subset selected because it shows the desired effect cannot also supply an independent test of that effect. Report exploratory analyses as exploratory and describe any separate data used for confirmation. [[9]](#ref-reporting-makin2019).

Name the statistical comparison, not merely the software command. Describe the outcome, explanatory variables and relevant pairing or grouping; state how uncertainty was estimated and how multiple testing was handled when many comparisons were made. If different panels use different analyses, make those assignments clear. [[7]](#ref-reporting-lafferty2016); [[2]](#ref-reporting-capra2022); [[9]](#ref-reporting-makin2019).

Identify the data and code in durable repository records, subject to applicable access restrictions. Prepare those records early and specify the version or retrieval date for changing datasets. [[2]](#ref-reporting-capra2022); [[6]](#ref-reporting-huber2025).

<a id="reporting-replicates"></a>

### Make the sampling and replication clear

Explain which samples were independently collected or treated and which measurements came from each. Hundreds of cells from one culture describe that culture more thoroughly, but do not establish consistency across independent cultures. Individual cells can be independent treatment units when the design assigns them that way and supports their independence. [[10]](#ref-reporting-lord2020).

Give sample sizes with their meaning: independent cultures, repeated readings or analysis runs. Where the study has more than one level, report the counts and their relationship, including exclusions. In the Brake example, there are six cultures per genotype, each measured on duplicate plates, and the primary effect is estimated from six contrasts matched by day. [[10]](#ref-reporting-lord2020); [[9]](#ref-reporting-makin2019).

Preserve that structure in both the analysis and its description. State whether the comparison uses sample summaries or a model that accounts for measurements nested within samples. Identify pairing when corresponding control and treatment observations belong to the same experimental run. A display can show individual observations and sample summaries together, provided the legend distinguishes them and identifies the unit used for statistical inference. [[10]](#ref-reporting-lord2020).

<a id="reporting-results"></a>

## Present results as an argument

<a id="reporting-results-order"></a>

### Order findings by what they establish

Introduce each result before relying on it. In the Brake study, identifying the protein-coding DNA product prepares the experiment that tests the protein’s role. Presenting that test first would leave readers unsure why the protein was chosen. [[3]](#ref-reporting-zhang2014); [[6]](#ref-reporting-huber2025).

Use finding-based Results headings when one statement covers the evidence. “The Brake protein mediates phage restriction” is more informative than “Protein experiments.” A descriptive heading suits a resource, procedure or unresolved comparison. Read the heading with the figure title to check that the written claim and display answer the same question. [[2]](#ref-reporting-capra2022).

One figure may support several paragraphs, and a claim may draw on several figures. Refer to the panels that support each finding and give the values needed to explain it. [[2]](#ref-reporting-capra2022); [[3]](#ref-reporting-zhang2014).

<a id="reporting-results-paragraph"></a>

### Build a paragraph around a finding

Build the paragraph around a finding, bringing together observations that support it. Briefly introduce the question and approach for an unfamiliar experiment; begin with the finding when the comparison is already clear. Name the treatment, comparison and outcome, then give the evidence, panel reference and any necessary qualification. Keep the full procedure in Methods. [[8]](#ref-reporting-wilke2013); [[2]](#ref-reporting-capra2022).

When introducing the next experiment, explain what you still needed to find out after the previous result. You do not need to repeat the paper’s broad motivation. [[4]](#ref-reporting-scitable); [[6]](#ref-reporting-huber2025). Explain what each result supports where readers need that connection to follow the next experiment. Reserve extended literature comparisons and broader implications for Discussion. If Results and Discussion are combined, still distinguish the observations from your proposed explanations. [[3]](#ref-reporting-zhang2014); [[4]](#ref-reporting-scitable).

A closing interpretation is useful when it connects several observations or motivates the next experiment. If the paragraph has already made and supported its point, move on without restating it. [[6]](#ref-reporting-huber2025).

<a id="reporting-results-quantification"></a>

### Report magnitude, comparison and uncertainty

State what changed, relative to what and by how much, with units and the scale of comparison. Give the important difference or proportion explicitly. The display or underlying data can carry the remaining values. [[6]](#ref-reporting-huber2025); [[3]](#ref-reporting-zhang2014).

Report the estimate together with appropriate uncertainty and, where used, the statistical test result. A small p-value cannot convey the magnitude of an effect, and “significant” alone does not tell readers its direction or biological importance. Distinguish variability among observations from uncertainty in an estimated effect. Make clear whether an interval describes a group mean, a between-group contrast or another quantity. [[7]](#ref-reporting-lafferty2016); [[9]](#ref-reporting-makin2019); [[10]](#ref-reporting-lord2020).

A claim that two effects differ needs a direct comparison between them. A significant response in one condition and a non-significant response in another can occur even when their estimated effects are similar, because the estimates have different precision. Separate significance tests do not answer the comparative question. [[9]](#ref-reporting-makin2019).

Name what was measured before giving its biological interpretation. In the Brake example below, the measurement is endpoint infectious titre; the interpretation concerns phage restriction. [[6]](#ref-reporting-huber2025).

<a id="reporting-results-example"></a>**Example: reporting a quantitative finding**

Endpoint infectious titres were compared within each experimental day, as described in the Methods above.

<a id="reporting-published-results"></a>

Brake reduced infectious phage A output. Across six experimental days, the geometric mean of the day-matched titre ratios indicated a 79-fold reduction with intact Brake relative to the empty-vector control (95% confidence interval, 55–116-fold; Figure 1B). Cultures carrying the inactive reverse transcriptase retained high phage titres. These results support a requirement for reverse-transcriptase activity in phage restriction.

**What to notice.** The interval belongs to the fold reduction. The final sentence gives a local interpretation of the control; it does not identify which downstream product causes defence. That question motivates Figures 2 and 3.

A lower endpoint titre is not automatically a smaller burst size per infected cell. Keep the result named after the quantity measured.

<a id="reporting-results-limits"></a>

### Negative and inconclusive findings

Report results that disagree with the prediction. State whether they provide evidence against it or are too imprecise to assess it. Also report controls that leave an alternative explanation unresolved. [[9]](#ref-reporting-makin2019); [[3]](#ref-reporting-zhang2014).

Give the estimated effect and uncertainty even when a test is non-significant. If you want to claim that any difference is too small to matter scientifically, specify how small it would need to be and whether the design and analysis can rule out larger differences. An inconclusive control leaves open the explanation it was intended to test. [[9]](#ref-reporting-makin2019).

When an unexpected result prompts exploration, explain how that analysis arose and label it accordingly. Report what it establishes and which questions remain unresolved, preserving the distinction from the original test. [[9]](#ref-reporting-makin2019).

<a id="reporting-legends"></a>

## Figure captions and legends

The figure caption, often called a figure legend, is the text beneath or alongside the display. Here, “legend” refers to that text rather than the key inside a plot. Include the conditions, label definitions and statistical details needed to understand the figure without searching the main text. [[5]](#ref-reporting-bioturing2018); [[2]](#ref-reporting-capra2022).

<a id="reporting-legends-structure"></a>

### Identify what each panel shows

Write the legend while looking at the figure. Begin with a concise title identifying its subject or principal finding, then describe the panels in their labeled order. Explain what readers are looking at before interpreting it: a schematic needs its relationships explained; an image needs the specimen, displayed signal and relevant scale; a quantitative plot needs the measured quantity and comparison. Add a brief finding when the journal permits and the title has not already conveyed it. [[5]](#ref-reporting-bioturing2018); [[11]](#ref-reporting-strack2020).

Label figures directly where practical, using the legend to define remaining symbols, abbreviations and encodings. Describe shared conditions once and identify panel-specific exceptions. Use the same names for conditions in the legend and display. [[5]](#ref-reporting-bioturing2018); [[2]](#ref-reporting-capra2022).

<a id="reporting-legend-statistics"></a>

### Make the statistical display interpretable

Identify sample sizes, what each plotted point represents, the summary statistic and the meaning of error bars or intervals. Distinguish individual observations from independent-sample summaries. [[2]](#ref-reporting-capra2022); [[10]](#ref-reporting-lord2020).

State which comparison each test or annotation refers to. Include the test and relevant sidedness, pairing and multiple-comparison information where applicable, following the journal’s reporting format. For box plots, define the boxes, central line, whiskers and any separately plotted points. For normalized data, explain the reference used for normalization if it is needed to interpret the values. [[2]](#ref-reporting-capra2022).

Keep the full analysis in Methods, but define the displayed samples and error bars in the legend. Shorten a long legend by describing shared procedures once. If the panels require unrelated explanations, consider whether they belong in separate figures. [[5]](#ref-reporting-bioturing2018); [[2]](#ref-reporting-capra2022).

<a id="reporting-legend-example"></a>**Example: a panel and its legend**

This is the quantitative panel from Figure 1 in the [Brake figure plan](01-planning-the-paper.md#planning-case-figures). It uses the same illustrative data as the Methods and Results passages above.

Original teaching figure; all plotted values are illustrative.

![Illustrative Figure 1B. Endpoint infectious phage A titres on a logarithmic axis for empty vector, intact Brake and inactive reverse transcriptase. Six connected sets of points represent matched experimental days. Intact Brake has lower titres on every day.](../../assets/images/reporting-example.png)

<a id="reporting-published-legend"></a>

**Figure 1B. Brake reduces infectious phage A yield.** Endpoint titres from cultures carrying empty vector, intact Brake or Brake with a catalytically inactive reverse transcriptase (inactive RT). Each point represents one independently started culture; lines connect the three cultures assayed on the same day. Six days were measured, with technical duplicate plaque counts combined for each culture. The vertical axis is logarithmic. The geometric mean titre was 79-fold lower for intact Brake than for empty vector (95% confidence interval, 55–116-fold), calculated from the six day-matched log10 titre ratios.

A legend for the complete Figure 1 would also describe the construct schematic and growth curves in panels A and C.

<a id="reporting-legend-style"></a>

### Adapt the explanation to the publication stage

An initial legend can explain the figure’s takeaway to reviewers; some journals retain that style, while others require shorter descriptions for publication. [[11]](#ref-reporting-strack2020). Use a finding-based title when it accurately summarizes the figure and the journal permits it, or a descriptive title otherwise. When shortening the legend, move necessary procedural or interpretive detail to the appropriate Methods or Results passage while retaining what readers need to decode the display. [[5]](#ref-reporting-bioturing2018); [[11]](#ref-reporting-strack2020).

Keep figures and legends together in a review copy when the submission format allows it. To test a legend, first give it to a colleague without the figure and ask them to sketch the panels they expect. Compare that sketch with the figure: a missing comparison, unexplained image or ambiguous panel identity tells you what to clarify. Then inspect the figure and legend together to check the labels and statistical details. [[11]](#ref-reporting-strack2020).

<a id="reporting-check"></a>

## Check reporting across text and figures

Check each result against its figure, legend, Methods and underlying analysis, following the same samples and comparison through to the reported numbers and interpretation. [[2]](#ref-reporting-capra2022); [[3]](#ref-reporting-zhang2014). Contributing authors should verify technical details; a second reader can identify missing explanations or unclear figure labels that the authors overlook. [[1]](#ref-reporting-pain2023); [[2]](#ref-reporting-capra2022).

Make the final pass on the assembled manuscript and supporting files, checking figure letters, units, terminology and statistical labels. Test data and code links, and carry each correction through all affected files. [[1]](#ref-reporting-pain2023); [[6]](#ref-reporting-huber2025).

<a id="reporting-checklist"></a>**Reporting checklist**

- Each result states a clear comparison and points to its supporting evidence.

- Methods identify the materials, design, procedures and analysis choices needed to follow the work.

- Selection, exclusions and exploratory decisions are reported where they affect inference.

- Sample counts distinguish independent units from measurements within them.

- Quantitative claims include the relevant magnitude and uncertainty, with suitable statistical support.

- Findings that limit the conclusion remain visible; inconclusive evidence retains its uncertainty.

- Legends identify the panels, conditions, encodings, summaries and statistical comparisons.

- Text, figures, legends, Methods and supporting files agree, and data/code access has been checked.

<a id="reporting-references"></a>

## References

1. <a id="ref-reporting-pain2023"></a>[Pain, E. (2023, March 31). **How to write a research paper.** *Science Careers*.](https://www.science.org/content/article/how-write-research-paper)

2. <a id="ref-reporting-capra2022"></a>[Capra Lab (2022, February). **The Capra Lab manuscript template.** [Manuscript template; formats finalized March 2022]. *GitHub*. Retrieved September 7, 2026.](https://github.com/CapraLab/lab-manuscript-template)

3. <a id="ref-reporting-zhang2014"></a>[Zhang, W. (2014). **Ten Simple Rules for Writing Research Papers.** *PLOS Computational Biology, 10(1), e1003453*.](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003453)

4. <a id="ref-reporting-scitable"></a>[Doumont, J.-L. (2010). **Scientific Papers.** In *English Communication for Scientists*. NPG Education, *Scitable*. [Web chapter; course page updated January 17, 2014]. Retrieved September 7, 2026.](https://www.nature.com/scitable/topicpage/scientific-papers-13815490/)

5. <a id="ref-reporting-bioturing2018"></a>[BioTuring Team (2018, May 11). **How to craft a figure legend for scientific papers.** [Blog post; originally published at BioTuring Blog]. *Medium*.](https://bioturing.medium.com/how-to-craft-a-figure-legend-for-scientific-papers-b26a77fa890)

6. <a id="ref-reporting-huber2025"></a>[Huber, W. (2025, August 18). **Scientific writing tips.** *Huber Group @ EMBL*. [Web guide; version consulted: August 18, 2025; live page now dated August 18, 2026]. Retrieved September 7, 2026.](https://www.huber.embl.de/group/posts/writingtips.html)

7. <a id="ref-reporting-lafferty2016"></a>[Lafferty, K. D. (2016). **Writing a scientific paper, step by painful step.** [Writing guide]. Parasite Ecology Group, University of California, Santa Barbara.](https://parasitology.msi.ucsb.edu/sites/default/files/docs/publications/Writing%20a%20Scientific%20Paper.doc)

8. <a id="ref-reporting-wilke2013"></a>[Wilke, C. O. (2013, August 29). **Writing a scientific paper in four easy steps.** [Blog post]. *Claus O. Wilke*.](https://clauswilke.com/blog/2013/08/29/writing-a-scientific-paper-in-four-easy-steps/)

9. <a id="ref-reporting-makin2019"></a>[Makin, T. R., & Orban de Xivry, J.-J. (2019). **Science Forum: Ten common statistical mistakes to watch out for when writing or reviewing a manuscript.** *eLife*, 8, e48175.](https://elifesciences.org/articles/48175)

10. <a id="ref-reporting-lord2020"></a>[Lord, S. J., Velle, K. B., Mullins, R. D., & Fritz-Laylin, L. K. (2020). **SuperPlots: Communicating reproducibility and variability in cell biology.** *Journal of Cell Biology*, 219(6), e202001064.](https://doi.org/10.1083/jcb.202001064)

11. <a id="ref-reporting-strack2020"></a>[Strack, R. [@rita_strack] (2020, May 28). **Here is a #ritaunsolicited very long thread on writing good figure legends.** [Twitter thread]. *Twitter (now X)*.](https://x.com/rita_strack/status/1266029631876018176)

12. <a id="ref-reporting-tang2024"></a>[Tang, S., and colleagues (2024). **De novo gene synthesis by an antiviral reverse transcriptase.** *Science*, 386(6717), eadq0876.](https://doi.org/10.1126/science.adq0876)

<a id="ref-reporting-wang2018"></a>⁠

<a id="ref-reporting-wang2018correction"></a>⁠
