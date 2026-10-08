<a id="quarto-document-content"></a> 

<a id="title-block-header"></a>

<a id="ideas-chapter"></a>

# Developing ideas

An observation you cannot explain can give you the beginning of a research idea. Explore possible explanations and look for a way to test them. The question may change as you learn more.

Yanai and Lercher call exploratory thinking *night science* and systematic testing *day science*, following François Jacob’s distinction. You can move between the two as an experiment suggests a new idea or an idea becomes ready to test [[3]](#ref-ideas-yanainight2019).

<a id="ideas-exploration"></a>

## Start with an observation

Write down what drew your attention and why it is surprising. Keep the observation separate from the explanation. “The processed images look brighter near the colony edge” reports something you can inspect. “Cells at the edge activate the pathway” adds claims about cells, measurement and mechanism. Those claims may become ideas to investigate, but they should not replace the starting observation.

You can explore data before choosing a hypothesis to test. You still need to understand what the assay measures and how the data were produced. Familiarity with the biology helps you recognize an unexpected observation; familiarity with the method helps you judge whether the procedure could have produced it [[7, p. 2]](#ref-ideas-yanaiconversation2021).

Try different views of the data. A distribution can reveal variation hidden by an average; individual trajectories can show whether samples change in the same way over time. Check whether a pattern coincides with how or when samples were prepared and measured. If the pattern appears in processed data, compare them with the raw observations to see whether processing created it. Shoresh and Wong distinguish plots used to explore data from plots used to explain a finding already identified [[2]](#ref-ideas-shoresh2012). [Choosing a figure or table](../03-data-visualization/01-choosing-a-figure-or-table.md#display-chapter) explains what different displays can reveal.

A specific hypothesis can focus attention so narrowly that other features go unnoticed. But searching many views of a dataset can also turn up patterns by chance. Keep a record of the plots and analysis choices that led to an idea, including any observations you excluded. Identify it as an idea developed from those data: the pattern that suggested it does not also provide an independent test of it [[4, pp. 1–4]](#ref-ideas-yanaihypothesis2020).

<a id="ideas-connections"></a>

## Connections with other fields

An idea from another field may help explain an unfamiliar pattern. If a signal changes with distance from a colony’s edge, for example, you might ask whether a substance reaches the center less readily. Transport theory could help you develop that possibility [[5, pp. 2–4]](#ref-ideas-yanairenaissance2020).

Check the assumptions before applying a model from another system. In the colony example, ask which substance the model could describe and whether differences in its availability could change the reporter signal. A model might assume that concentrations have reached equilibrium, whereas your experiment observes a changing supply. Read how the model was derived, and ask someone familiar with it to help assess whether its assumptions fit your system.

An informal phrase such as “the colony’s center is being starved” can suggest an idea before you know which substance might be scarce. Before designing a test, spell out the proposed explanation: “Perhaps a substance supplied from outside the colony reaches the center at a lower concentration, causing the reporter to be dimmer there.” You would then need to find out which substance could do this and how it would affect the reporter. Yanai and Lercher describe how metaphors can help generate ideas that later need more precise wording [[6, pp. 4–8]](#ref-ideas-yanai2020).

Several other explanations remain possible. Lower fluorescence could mean less reporter per cell, different reporter chemistry or fewer cells in the imaged region. It could also arise from how the microscope records light. The nutrient explanation needs to be considered alongside these alternatives.

<a id="ideas-conversation"></a>

## Discussing unfinished ideas

Discuss the unfinished idea with someone who can help you develop it. A colleague familiar with the assay may notice a measurement problem; someone from another field may suggest an explanation you had not considered. Choose a person or group with whom you can think aloud before you have a defensible answer [[9, pp. 2–8]](#ref-ideas-yanaiimprov2022); [[11]](#ref-ideas-yanaitwo2024).

Give a tentative idea time to develop before rejecting it. Ask what would have to be true for it to work, or whether a narrower version could explain the observation. Then examine it critically: does it conflict with known evidence, and what alternatives have you overlooked? Yanai and Lercher recommend this constructive exchange without requiring colleagues to agree that an idea is true [[9, pp. 3–4]](#ref-ideas-yanaiimprov2022).

**Developing a spatial question**

The following fictional conversation concerns processed fluorescence images of bacterial colonies that appear brighter near their edges. No mechanism or quantitative difference has been established.

<a id="ideas-worked-conversation"></a>**Conversation: from a plausible story to alternatives**

**Researcher:** Perhaps cells near the edge get more nutrients, so the reporter is brighter there.

**Colleague:** Then we should look at how brightness changes with distance from the edge. Do we see the same pattern in different colonies?

**Researcher:** We could look for that. But the reporter might also behave differently where oxygen is more available. We have not checked its chemistry under these conditions.

**Colleague:** And are we sure the pattern follows the colony? If illumination is uneven, its position in the image could matter. Colony thickness might change the recorded signal too.

**Researcher:** Let’s first check the raw images. Are the bright regions near colony edges, or do they occur in the same part of the microscope’s field of view? If the pattern follows the colonies and remains after checking acquisition and processing, we can investigate nutrient access and reporter chemistry.

After a discussion, note how the question changed, what you still disagree about and who contributed each suggestion. Include alternatives you do not favor, so that your notes do not preserve only your preferred explanation.

<a id="ideas-reframing"></a>

## Questioning assumptions

When an observation does not fit, examine the observation and the expectation together. An apparent contradiction may reflect a technical problem, a difference in conditions or a hidden assumption about the biology. Apply the same scrutiny to an attractive finding. Gosling and Noordam warn both against dismissing data that disagree with a hypothesis and against mistaking systematic error or ordinary variation for a discovery [[1, pp. 24–25]](#ref-ideas-goslingnoordam2022thesis).

State the assumption you need to check. In the colony case, you might have assumed that a brighter region contains more reporter per cell. But a thicker region may contain more cells along the imaging path. Before interpreting brightness as a difference between cells, you would need to account for how many cells contribute to the signal.

When you are stuck, ask whether the facts you already have can explain the observation or whether you need to look elsewhere. You may need to learn about a process outside your field, as in the transport example. Or you may have imposed a restriction without noticing it, such as assuming that brightness must reflect a change inside individual cells. Yanai and Lercher’s puzzle framework offers these as different ways to reconsider a problem; you may not know in advance which one will help [[10, pp. 3–7]](#ref-ideas-yanaipuzzle2022).

Try developing the strongest contrary account of your preferred idea. What would a careful critic say you had overlooked? Which observation would be difficult to explain under your account? Yanai and Lercher suggest imagining a future paper that challenges the project as a way to expose assumptions. Use that exercise to generate alternatives, then assess whether they actually fit the evidence [[8, pp. 5–6]](#ref-ideas-yanaicontradictions2021).

<a id="ideas-next-check"></a>

## What to check next

Choose the next step by asking what you need to learn before designing an experiment. If you do not yet understand the reporter, read about its chemistry and check how it behaves under your conditions. If the observation is reliable but several explanations fit, work out what each would predict. You do not need a complete explanation before beginning, but you should be able to say what the next check would tell you.

For the colony example, the discussion produces the following note.

<a id="ideas-worked-note"></a>**Idea note: does the spatial pattern belong to the sample?**

**Starting observation:** Processed fluorescence images appear brighter near colony edges. This is an impression from images, not a validated estimate of reporter abundance per cell.

**Developed idea:** A substance supplied from outside the colony might reach the center at a lower concentration and affect the reporter signal. We could examine how brightness changes with distance from the edge.

**Alternatives to retain:** Reporter chemistry may vary with local conditions; colony thickness may alter the recorded signal; illumination or background subtraction may create a pattern. We have not established which explanation applies.

**Next check:** Inspect raw images, acquisition metadata and processing settings. Establish whether the pattern exists before processing and follows colony position rather than position in the field of view. Check what the reporter can indicate under these conditions.

**Decision after that check:** If acquisition or processing creates the pattern, investigate that cause before interpreting it biologically. If those checks leave a pattern that follows the colony, compare the predictions of the remaining explanations. We still need to determine what the reporter measures before choosing a biological test.

For the next experiment, [compare the predictions of the remaining explanations](03-connecting-questions-models-and-experiments.md#models-predictions).

<a id="ideas-references"></a>

## References

1. <a id="ref-ideas-goslingnoordam2022thesis"></a>[Gosling, P., & Noordam, B. (2022). **Mastering Your PhD: Survival and Success in the Doctoral Years and Beyond.** 3rd ed. Springer Nature Switzerland AG. Chapter 4, pp. 23–28.](https://doi.org/10.1007/978-3-031-11417-5)

2. <a id="ref-ideas-shoresh2012"></a>[Shoresh, N., & Wong, B. (2012). **Data exploration.** *Nature Methods*, 9, 5.](https://doi.org/10.1038/nmeth.1829)

3. <a id="ref-ideas-yanainight2019"></a>[Yanai, I., & Lercher, M. (2019). **Night science.** *Genome Biology*, 20, 179.](https://doi.org/10.1186/s13059-019-1800-6)

4. <a id="ref-ideas-yanaihypothesis2020"></a>[Yanai, I., & Lercher, M. (2020a). **A hypothesis is a liability.** *Genome Biology*, 21, 231.](https://doi.org/10.1186/s13059-020-02133-w)

5. <a id="ref-ideas-yanairenaissance2020"></a>[Yanai, I., & Lercher, M. (2020b). **Renaissance minds in 21st century science.** *Genome Biology*, 21, 67.](https://doi.org/10.1186/s13059-020-01985-6)

6. <a id="ref-ideas-yanai2020"></a>[Yanai, I., & Lercher, M. J. (2020c). **The two languages of science.** *Genome Biology*, 21, 147.](https://doi.org/10.1186/s13059-020-02057-5)

7. <a id="ref-ideas-yanaiconversation2021"></a>[Yanai, I., & Lercher, M. (2021a). **The data-hypothesis conversation.** *Genome Biology*, 22, 58.](https://doi.org/10.1186/s13059-021-02277-3)

8. <a id="ref-ideas-yanaicontradictions2021"></a>[Yanai, I., & Lercher, M. (2021b). **Novel predictions arise from contradictions.** *Genome Biology*, 22, 153.](https://doi.org/10.1186/s13059-021-02371-6)

9. <a id="ref-ideas-yanaiimprov2022"></a>[Yanai, I., & Lercher, M. (2022a). **Improvisational science.** *Genome Biology*, 23, 4.](https://doi.org/10.1186/s13059-021-02575-w)

10. <a id="ref-ideas-yanaipuzzle2022"></a>[Yanai, I., & Lercher, M. J. (2022b). **What puzzle are you in?** *Genome Biology*, 23, 179.](https://doi.org/10.1186/s13059-022-02748-1)

11. <a id="ref-ideas-yanaitwo2024"></a>[Yanai, I., & Lercher, M. J. (2024). **It takes two to think.** *Nature Biotechnology*, 42, 18–19.](https://doi.org/10.1038/s41587-023-02074-2)
