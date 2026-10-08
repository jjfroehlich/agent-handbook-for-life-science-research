<a id="quarto-document-content"></a> 

<a id="title-block-header"></a>

<a id="planning-paper"></a>

# Planning the paper

Which finding should the paper lead with, and which experiments support it? A working title and a short statement of the contribution can help you decide. Check them against the results before developing the figure plan and manuscript outline.

<a id="planning-contribution"></a>

## Define the contribution

<a id="planning-reader"></a>

### Identify the reader and question

The paper needs a question to answer or a problem for the new method to solve. Write that question with the intended readers in mind: what do they already know, and what background will they need to understand it? [[1]](#ref-planning-mensh2017); [[3]](#ref-planning-pain2023); [[2]](#ref-planning-zhang2014). The relevant literature should establish what is known, what remains unresolved and why resolving it matters. [[12]](#ref-planning-huber2025); [[5]](#ref-planning-carandini2022); [[6]](#ref-planning-scitable).

<a id="planning-scope"></a>

### State what the study establishes

Write a working title and a one- or two-sentence contribution statement that names the main finding and what it adds to existing knowledge. Specify the system or conditions when they limit the conclusion. [[1]](#ref-planning-mensh2017); [[4]](#ref-planning-gewin2018). Distinguish the observation from its interpretation: a measured response may support a functional role without identifying the mechanism. Choose the wording accordingly. [[11]](#ref-planning-makin2019).

A computational method and the biological insight it enables may belong in one paper. If two groups of results answer independent questions, consider separate papers. [[1]](#ref-planning-mensh2017); [[2]](#ref-planning-zhang2014).

<a id="planning-evidence"></a>

## Build the argument from the evidence

<a id="planning-claims"></a>

### Connect claims to results

List the proposed claims in a table, with the supporting result and planned figure or panel beside each one. Add the assumptions on which the claim depends and any limits to its interpretation. Include results that challenge it and questions that remain unresolved. [[3]](#ref-planning-pain2023); [[7]](#ref-planning-capra2022); [[8]](#ref-planning-lafferty2016). For a quantitative claim, include the effect estimate and its uncertainty. Note whether the analysis tested a planned prediction or suggested an explanation during exploration. [[11]](#ref-planning-makin2019).

<a id="planning-case-contribution"></a>**Example: defining the contribution**

<a id="brake-case"></a>Brake is a <a id="planning-imaging-inventory"></a>fictional bacterial defence system inspired by the antiviral gene-synthesis discovery of [[15]](#ref-planning-tang2024). Genome annotation reveals a reverse transcriptase and an RNA template, but no conventional defence-effector gene. The researchers ask what this system produces and how it restricts phage infection.

**Working title:** An RNA-templated gene arrests bacterial growth and restricts phage propagation

**Working contribution:** Brake assembles a protein-coding gene from an RNA template. Its protein product arrests bacterial growth and restricts phage propagation, revealing a route to defence in which the functional gene must first be assembled.

**Claim inventory**

<table>
<colgroup>
<col>
<col>
<col>
<col>
<col>
</colgroup>
<thead>
<tr>
<th>Proposed claim</th>
<th>Supporting analysis/result</th>
<th>Planned figure/panel</th>
<th>Assumptions</th>
<th>Interpretation limits</th>
</tr>
</thead>
<tbody>
<tr>
<td>Brake restricts phage propagation.</td>
<td>Lower infectious phage yield with intact Brake than with empty vector or inactive reverse transcriptase.</td>
<td>Figure 1B–C</td>
<td>Matched infections and comparable titre measurements.</td>
<td>Establishes restriction in the tested host.</td>
</tr>
<tr>
<td>The RNA template supplies a protein-coding DNA product.</td>
<td>Repeat-junction sequences, DNA measurements and protein detection; template-deletion control.</td>
<td>Figure 2A–D</td>
<td>Product identification distinguishes newly assembled DNA from the construct.</td>
<td>The infection signal that activates the pathway is unknown.</td>
</tr>
<tr>
<td>The protein mediates growth arrest and defence.</td>
<td>Blocking translation preserves DNA production but removes growth arrest and phage restriction; separate protein expression restores both.</td>
<td>Figure 3A–C</td>
<td>The translation change leaves upstream RNA and DNA production intact.</td>
<td>The protein’s molecular target is unknown.</td>
</tr>
<tr>
<td>Activity differs among tested phages.</td>
<td>Restricted output of phages A and B; phage C remains productive.</td>
<td>Figure 4A</td>
<td>Infection conditions permit each phage to replicate in the control.</td>
<td>Three phages do not establish the full host–phage range.</td>
</tr>
<tr>
<td>Recovery after infection remains unresolved.</td>
<td>Infected cells stop growing during observation; subsequent recovery was not measured.</td>
<td>Figure 4B</td>
<td>Tracking captures the infected cells of interest.</td>
<td>Growth arrest does not establish survival or irreversible death.</td>
</tr>
</tbody>
</table>

The third row identifies the decisive control. If blocking translation also stopped DNA production, loss of defence would not distinguish a protein effect from a DNA effect.

<a id="planning-gaps"></a>

### Resolve gaps and conflicting findings

An incomplete argument may need a clearer explanation, a different analysis or additional evidence. Use the claim inventory to locate the missing step before planning more experiments. In Brake, checking that DNA production survives the translation-disrupting change is necessary to attribute defence to the protein. Identifying the protein’s molecular target would address a further question. [[1]](#ref-planning-mensh2017); [[4]](#ref-planning-gewin2018).

When findings disagree, examine the conditions, measurements and analytical choices. If the disagreement persists, revise the interpretation and discuss it in the main text, even when the detailed displays are in supporting material. [[2]](#ref-planning-zhang2014); [[3]](#ref-planning-pain2023).

<a id="planning-gap-decisions"></a>**How to resolve incomplete arguments**

[[1]](#ref-planning-mensh2017); [[4]](#ref-planning-gewin2018); [[2]](#ref-planning-zhang2014); [[11]](#ref-planning-makin2019).

<table>
<thead>
<tr>
<th>Problem</th>
<th>How to recognize it</th>
<th>Next action</th>
</tr>
</thead>
<tbody>
<tr>
<td>Missing explanation</td>
<td>The evidence is present, but a link in the reasoning is unstated.</td>
<td>Explain why the comparison answers the question. Note the missing explanation beside the relevant claim, then include it in the <a href="#planning-paragraphs">manuscript’s paragraph outline</a>.</td>
</tr>
<tr>
<td>Missing essential evidence</td>
<td>The claim depends on an untested assumption or missing control.</td>
<td>Obtain the necessary evidence or narrow the claim.</td>
</tr>
<tr>
<td>Contradictory findings</td>
<td>Results support different answers to the same question.</td>
<td>Check conditions, measurements and analyses. If disagreement remains, include it and revise the interpretation.</td>
</tr>
<tr>
<td>Inconclusive findings</td>
<td>The estimate or assay is too uncertain to answer the question.</td>
<td>State what remains unresolved. If the central claim needs that answer, improve the evidence or narrow the claim.</td>
</tr>
</tbody>
</table>

<a id="planning-figures"></a>

## Arrange the figures

<a id="planning-figure-purpose"></a>

### Give each figure a purpose

Group results from the claim inventory around the question each figure will answer. Write its title early: a finding-based title helps you judge whether the panels support one conclusion, while a descriptive title suits a design or unresolved comparison. [[7]](#ref-planning-capra2022); [[8]](#ref-planning-lafferty2016); [[3]](#ref-planning-pain2023).

For an unfamiliar procedure or a comparison across several stages, include a schematic showing the starting material, important steps and measurement. Align corresponding stages when comparing conditions. Use recognizable schematic symbols and keep them distinct from the images or plots reporting observations. [[13]](#ref-planning-wong2011).

Plan the comparisons within each figure. Put the treatment and reference condition together; use a separate control panel when you need to establish that the intervention worked. Pair an illustrative observation with a population summary when readers need to judge how typical it is. Keep group names consistent across figures. Rough plots and panel notes are sufficient for this stage; refine the layout once the scientific content is settled. [[5]](#ref-planning-carandini2022); [[7]](#ref-planning-capra2022).

<a id="planning-figure-order"></a>

### Choose the figure sequence

Order figures by the questions they answer. First establish the problem or observation; then present the tests needed to explain or resolve it. Arrange panels within each figure so the relevant comparisons can be read together. [[1]](#ref-planning-mensh2017); [[6]](#ref-planning-scitable).

<a id="planning-case-figures"></a>**Example: planning the figures**

<a id="planning-imaging-figures"></a>The experiment log starts with a growth defect during protein expression, followed by phage-yield assays, sequence analysis, DNA measurements and tests of the translation-disrupted construct. The figure plan changes that order: first establish defence, then explain how it works.

**Figure 1 — Brake restricts phage propagation**

Does Brake reduce phage output?

- **A:** Introduce the defence region and the control constructs.

- **B:** Compare infectious phage A yield with empty vector, intact Brake and inactive reverse transcriptase.

- **C:** Show host growth during infection alongside uninfected controls.

**Figure 2 — Brake produces a protein-coding DNA intermediate**

What does the reverse transcriptase make?

- **A:** Map the RNA template and the coding sequence created across DNA repeat junctions.

- **B:** Compare DNA products before and during infection.

- **C:** Show expression of the encoded protein during infection.

- **D:** Test the RNA-template deletion.

**Figure 3 — The Brake protein mediates growth arrest and defence**

Which product carries out the defence?

- **A:** Introduce the translation-disrupting change and verify that DNA production remains intact.

- **B:** Show loss of growth arrest and phage restriction.

- **C:** Test restoration by expressing the protein separately.

**Figure 4 — Brake responses across phage challenges**

How do the tested phages differ in restriction and infected-cell growth?

- **A:** Compare phage output for A, B and C.

- **B:** Track growth of infected cells, retaining the observation window in the display.

Starting with protein expression would leave readers wondering why that protein was tested. Placing it after product identification makes it a test of the proposed effector.

<a id="planning-supporting"></a>

### Decide what belongs in supporting material

Keep the evidence essential to the main contribution in the paper, including controls on which its interpretation depends. Supporting material can hold extended analyses and additional checks. A result from another system belongs in the main paper when the claim depends on its generality. [[4]](#ref-planning-gewin2018); [[7]](#ref-planning-capra2022).

Read the figure titles in sequence and ask a colleague to explain the argument from the figures and provisional legends. If a figure needs several unrelated explanations, split it; if two displays establish the same point, consider combining them. [[7]](#ref-planning-capra2022); [[5]](#ref-planning-carandini2022).

<a id="planning-outline"></a>

## Develop the outline

<a id="planning-sections"></a>

### Section purposes

Build the manuscript outline around the figure plan, using the section purposes below. [[6]](#ref-planning-scitable); [[1]](#ref-planning-mensh2017).

<a id="planning-paper-structure"></a>**Section overview**

<table>
<colgroup>
<col>
<col>
</colgroup>
<thead>
<tr>
<th>Component</th>
<th>Purpose</th>
</tr>
</thead>
<tbody>
<tr>
<td>Title and abstract</td>
<td>Identify the contribution and summarize the question, approach, main findings and meaning.</td>
</tr>
<tr>
<td>Introduction</td>
<td>Establish the relevant knowledge, explain the unresolved question and introduce the study.</td>
</tr>
<tr>
<td>Methods</td>
<td>Describe the design, materials, procedures and analyses needed to assess and reproduce the work.</td>
</tr>
<tr>
<td>Results</td>
<td>Present a logical sequence of findings, supported by figures, tables and the controls needed to interpret them.</td>
</tr>
<tr>
<td>Discussion</td>
<td>Answer the research question, relate the findings to prior work, assess alternatives and limitations, and explain the contribution.</td>
</tr>
<tr>
<td>Supporting material</td>
<td>Supply additional methods, data and analyses that support the paper while keeping its main argument easy to follow.</td>
</tr>
</tbody>
</table>

Adjust the outline to the journal’s format: Methods may appear later, Results and Discussion may be combined, or a separate conclusion may be required. [[6]](#ref-planning-scitable); [[9]](#ref-planning-wilke2013).

Start the outline with the working title and contribution statement, then place the figure findings under Results. Work outward from those findings: list the background needed to understand them, the procedures to describe in Methods and the interpretations to examine in Discussion. [[1]](#ref-planning-mensh2017); [[7]](#ref-planning-capra2022).

<a id="planning-budget-example"></a>Check the journal’s length and display limits before developing the manuscript outline. Use a [rough word and figure budget](05-drafting-reviewing-and-revising-a-paper.md#revision-budget-example) to allocate space. [[14]](#ref-planning-jjfroehlich2026budget).

<a id="planning-paragraphs"></a>

### Plan paragraph purposes

Outline what each paragraph will establish and which results or sources it will draw on. A figure may require several paragraphs if readers need to follow distinct steps in the reasoning. [[1]](#ref-planning-mensh2017); [[8]](#ref-planning-lafferty2016). For Results, specify the finding and the comparison that supports it; leave sentence-level development to drafting. See [building a Results paragraph](03-methods-results-and-figure-legends.md#reporting-results-paragraph). [[5]](#ref-planning-carandini2022); [[6]](#ref-planning-scitable); [[12]](#ref-planning-huber2025).

Read the paragraph statements in order. Does the reader have enough information to understand each new comparison? Combine repeated points and divide paragraphs that try to explain several things at once. Introduce each experiment through the question it addresses; you need not repeat the motivation for the whole study. [[12]](#ref-planning-huber2025).

<a id="planning-case-outline"></a>**Example: developing the outline**

<a id="planning-imaging-outline"></a>Manuscript outline for the Brake study

**Introduction**

1. Explain why understanding bacterial defence requires identifying the product that inhibits infection.

2. Introduce the puzzle: Brake contains a reverse transcriptase and an RNA template but no recognizable effector gene. Explain why identifying its products could resolve this gap.

3. State the question: what does Brake produce, and how does that product restrict phage infection?

**Results**

1. Intact Brake reduces infectious phage A output relative to the controls; host growth measurements distinguish infection-associated effects from growth without infection (Figure 1).

2. RNA-derived DNA repeat junctions create a coding sequence. Use the sequence analysis and RNA-template deletion control to explain the product’s origin (Figure 2A, D).

3. The DNA product is present before infection; double-stranded DNA and the encoded protein are detected during infection (Figure 2B–C).

4. Preventing translation removes defence despite continued DNA production; separate protein expression restores growth arrest and restriction (Figure 3).

5. Activity varies among the three tested phages, and infected-cell tracking shows growth arrest without establishing recovery (Figure 4).

**Methods**

1. Identify the host, defence constructs, phages and infection conditions.

2. Describe DNA-product identification, sequence analysis and protein measurements.

3. Explain growth measurements and infectious-titre assays, including independent cultures, technical measurements and matching by experimental day.

4. Describe cell tracking and the analyses behind each comparison.

**Discussion**

1. Explain how RNA-templated gene assembly supplies a defence protein, connecting product identification with the genetic tests.

2. Contrast this organization with a defence protein encoded by a conventional genomic gene. Identify the literature needed to support that comparison in an actual manuscript.

3. Explain why growth arrest leaves cell recovery unresolved and why the protein’s molecular target requires further work.

4. Close with the contribution: a functional defence gene can emerge from RNA-templated DNA assembly rather than exist as a conventional coding sequence in the genome.

Figure 2 supports two paragraphs: one identifies the DNA product; the next connects protein production to infection. The following paragraph tests the protein’s function. Product detection alone would not establish that role.

You can plan Methods alongside Results, noting software versions, analysis choices and experimental details while they are available. Check that every reported analysis has a corresponding method. [[7]](#ref-planning-capra2022); [[2]](#ref-planning-zhang2014).

<a id="planning-drafting-order"></a>

### Choose where to start drafting

If the comparisons are settled, starting with Results and Methods lets you describe work you already know well. If you are unsure what the paper contributes, try writing the title and Introduction first. If you have many results but no clear order, return to the figure plan. These are different ways into the draft; the finished paper’s reading order need not determine where you start. See [Drafting and revising](05-drafting-reviewing-and-revising-a-paper.md#revision-entry) for starting a passage and organizing writing sessions. [[9]](#ref-planning-wilke2013); [[5]](#ref-planning-carandini2022); [[3]](#ref-planning-pain2023).

<a id="planning-coauthors"></a>

## Plan the writing with coauthors

<a id="planning-responsibilities"></a>

### Agree the plan and responsibilities

Share the contribution statement, rough figures and manuscript outline before dividing the writing. Ask coauthors to challenge the claims and identify missing evidence or alternative interpretations. Agree on the main argument before authors develop separate sections. [[4]](#ref-planning-gewin2018); [[3]](#ref-planning-pain2023).

Assign a writer and a scientific checker for each part, set dates and choose who will integrate the manuscript. That person should reconcile terminology, transitions and repetition across contributions. Keep one current version with recoverable history, and record decisions that affect other sections. [[10]](#ref-planning-albert2003); [[3]](#ref-planning-pain2023).

Assign data and metadata preparation early, allowing time for repository queries and corrections alongside the writing. [[12]](#ref-planning-huber2025).

<a id="planning-authorship"></a>

### Agree authorship and credit

Discuss who should be an author and the proposed order before drafting, then revisit the agreement when contributions change. Use the target journal’s criteria and relevant disciplinary or institutional guidance. Record the reasons for the order, including any shared-author designation, so that later discussion can refer to the work each person actually did. [[10]](#ref-planning-albert2003); [[16, section 2]](#ref-planning-icmje2026).

For a journal following ICMJE, a substantial contribution to the research alone does not complete the authorship requirements. Contributors must also help draft or critically review the paper, approve the version for publication and accept responsibility for addressing concerns about the work. Give eligible contributors the manuscript and enough time to participate; do not exclude them by withholding that opportunity. [[16, section 2]](#ref-planning-icmje2026).

Prepare the contribution statement with the authors. If the journal uses CRediT, its roles describe the work performed; they do not decide who qualifies as an author or the order of names. Check the statement with each contributor, agree who will handle correspondence with the journal, and identify other contributions to acknowledge. [[17]](#ref-planning-niso2022); [[16, sections 2–3]](#ref-planning-icmje2026). For a worked credit decision and guidance when contributions are disputed, see [Contributions, authorship and order](../10-mentoring-and-management/04-collaboration-authorship-and-credit.md#collaboration-credit-decisions).

<a id="planning-feedback"></a>

### Organize feedback

Plan an early review of the contribution and figures, then a later review of the written explanation. Ask a domain expert to challenge the inference and a colleague less familiar with the project to identify missing context. Agree these roles and review dates with the coauthors. The chapter [Drafting and revising](05-drafting-reviewing-and-revising-a-paper.md#revision-feedback) explains how to request and resolve their feedback. [[1]](#ref-planning-mensh2017); [[2]](#ref-planning-zhang2014); [[8]](#ref-planning-lafferty2016).

<a id="planning-checklist"></a>**Before drafting**

- Can a reader state the question, contribution and conditions without an oral explanation?

- Can each retained claim be traced to supporting evidence, with important assumptions and limits identified?

- Can readers find the controls needed to interpret each finding, including comparisons that remain inconclusive?

- Do paragraph purposes connect the figures to the section plan, with each reported analysis assigned a method?

- Have coauthors agreed who will write and check each section and how contributions will be credited?

<a id="planning-references"></a>

## References

1. <a id="ref-planning-mensh2017"></a>[Mensh, B., & Kording, K. (2017). **Ten simple rules for structuring papers.** *PLOS Computational Biology, 13(9), e1005619*.](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005619)

2. <a id="ref-planning-zhang2014"></a>[Zhang, W. (2014). **Ten Simple Rules for Writing Research Papers.** *PLOS Computational Biology, 10(1), e1003453*.](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003453)

3. <a id="ref-planning-pain2023"></a>[Pain, E. (2023, March 31). **How to write a research paper.** *Science Careers*.](https://www.science.org/content/article/how-write-research-paper)

4. <a id="ref-planning-gewin2018"></a>[Gewin, V. (2018). **How to write a first-class paper.** *Nature, 555, 129-130*.](https://www.nature.com/articles/d41586-018-02404-4)

5. <a id="ref-planning-carandini2022"></a>[Carandini, M. (2022). **Some Tips for Writing Science.** *eNeuro, 9(6), ENEURO.0497-22.2022*.](https://doi.org/10.1523/ENEURO.0497-22.2022)

6. <a id="ref-planning-scitable"></a>[Doumont, J.-L. (2010). **Scientific Papers.** In *English Communication for Scientists*. NPG Education, *Scitable*. [Web chapter; course page updated January 17, 2014]. Retrieved September 7, 2026.](https://www.nature.com/scitable/topicpage/scientific-papers-13815490/)

7. <a id="ref-planning-capra2022"></a>[Capra Lab (2022, February). **The Capra Lab manuscript template.** [Manuscript template; formats finalized March 2022]. *GitHub*. Retrieved September 7, 2026.](https://github.com/CapraLab/lab-manuscript-template)

8. <a id="ref-planning-lafferty2016"></a>[Lafferty, K. D. (2016). **Writing a scientific paper, step by painful step.** [Writing guide]. Parasite Ecology Group, University of California, Santa Barbara.](https://parasitology.msi.ucsb.edu/sites/default/files/docs/publications/Writing%20a%20Scientific%20Paper.doc)

9. <a id="ref-planning-wilke2013"></a>[Wilke, C. O. (2013, August 29). **Writing a scientific paper in four easy steps.** [Blog post]. *Claus O. Wilke*.](https://clauswilke.com/blog/2013/08/29/writing-a-scientific-paper-in-four-easy-steps/)

10. <a id="ref-planning-albert2003"></a>[Albert, T., & Wager, E. (2003). **How to handle authorship disputes: a guide for new researchers.** *The COPE Report 2003, 32-34*.](https://publicationethics.org/files/2003pdf12_0.pdf)

11. <a id="ref-planning-makin2019"></a>[Makin, T. R., & Orban de Xivry, J.-J. (2019). **Science Forum: Ten common statistical mistakes to watch out for when writing or reviewing a manuscript.** *eLife*, 8, e48175.](https://elifesciences.org/articles/48175)

12. <a id="ref-planning-huber2025"></a>[Huber, W. (2025, August 18). **Scientific writing tips.** *Huber Group @ EMBL*. [Web guide; version consulted: August 18, 2025; live page now dated August 18, 2026]. Retrieved September 7, 2026.](https://www.huber.embl.de/group/posts/writingtips.html)

13. <a id="ref-planning-wong2011"></a>[Wong, B. (2011b). **Points of view: The overview figure.** *Nature Methods*, 8, 365.](https://www.nature.com/articles/nmeth0511-365)

14. <a id="ref-planning-jjfroehlich2026budget"></a>[jjfroehlich (2026). **Research papers: practical length targets.** *Awesome Life Science Resources*.](https://github.com/jjfroehlich/awesome-life-science-resources/blob/main/pages/journal-text-lengths.md)

15. <a id="ref-planning-tang2024"></a>[Tang, S., and colleagues (2024). **De novo gene synthesis by an antiviral reverse transcriptase.** *Science*, 386(6717), eadq0876.](https://doi.org/10.1126/science.adq0876)

16. <a id="ref-planning-icmje2026"></a>[International Committee of Medical Journal Editors. (2026). **Defining the Role of Authors and Contributors.** *Recommendations for the Conduct, Reporting, Editing, and Publication of Scholarly Work in Medical Journals*.](https://www.icmje.org/recommendations/browse/roles-and-responsibilities/defining-the-role-of-authors-and-contributors.html)

17. <a id="ref-planning-niso2022"></a>[National Information Standards Organization. (2022). **ANSI/NISO Z39.104-2022, CRediT, Contributor Roles Taxonomy.**](https://doi.org/10.3789/ansi.niso.z39.104-2022)

<a id="ref-planning-wang2018"></a>⁠
