<p align="center">
  <img src="./images/agent-handbook-for-life-science-research_banner.jpg" width="900" alt="Scientific work header illustration" />
</p>

# Agent Handbook and Skills for Life Science Research

The **Life Science Research Handbook** and agent skills cover research methodology. They are for agents! Based on a collection of **317 sources**, inspired by [awesome-life-science-resources](https://github.com/jjfroehlich/awesome-life-science-resources). The handbook covers explanations, examples, and references, while the skills apply these principles. 

## Handbook

Due to slop it might be hard to read for humans. You can read the [HTML handbook](https://jjfroehlich.github.io/agent-handbook-for-life-science-research/handbook/) or [PDF](handbook/life-science-research-handbook.pdf). 

## Skills

| Skill | Used for |
| --- | --- |
| `career-development` | Explore career options, choose advisors and research environments, and prepare applications, CVs and interviews. |
| `data-visualization-and-figures` | Choose suitable plots, communicate uncertainty, and improve scientific images and figure layouts. |
| `grant-writing` | Choose funding opportunities, develop proposals and budgets, and prepare for funding interviews. |
| `literature-reading-and-synthesis` | Read papers critically, assess their evidence, and compare findings across studies. |
| `mentoring-management-and-lab-culture` | Improve mentoring, delegation, lab policies, feedback and collaboration within research groups. |
| `publishing-and-peer-review` | Choose journals, prepare submissions, review manuscripts and respond to reviewers. |
| `research-strategy-and-project-design` | Develop research questions, hypotheses and experimental designs, and decide how projects should proceed. |
| `scientific-communication` | Prepare scientific talks, slides, posters, chalk talks and explanations for different audiences. |
| `scientific-feedback` | Get an integrated critique of a manuscript, presentation, proposal, figure or lab policy. |
| `scientific-writing` | Plan, draft and revise papers, thesis chapters, abstracts and figure captions. |
| `life-science-research-handbook` | Handbook reference for the other skills, with automatic triggering disabled where supported. |


## How to Install

Give your agent the repository link and let it install. For example `Please install the skills at https://github.com/jjfroehlich/agent-handbook-for-life-science-research`. Alternatively, copy one or more folders from `skills/` into your agent's skill directory. Skills are portable across different agent systems.

## How to Use 

The skills should be triggered automatically in the right conditions. Just ask for advice on anything related to the above topics.

## Related Work
There are existing agent skills for scientific work; some also cover scientific writing or research workflows: [K-Dense-AI scientific writer](https://github.com/K-Dense-AI/claude-scientific-writer/tree/main), [Imbad0202 academic research skills](https://github.com/Imbad0202/academic-research-skills), [K-Dense-AI science-superpowers](https://github.com/K-Dense-AI/science-superpowers), and [John Kitchin research skills](https://github.com/jkitchin/skillz/tree/main/skills/research). Many others focus on computational biology or bioinformatics: [GPTomics bioSkills](https://github.com/GPTomics/bioSkills), [ClawBio skills](https://github.com/ClawBio/ClawBio/tree/main/skills), [Google Deepmind science-skills](https://github.com/google-deepmind/science-skills), and [K-Dense-AI scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills). 


## Limitations

- This handbook and the skills are experimental and I am unsure if they are useful, useless or harmful.
- The extraction and synthesis process can miss context or overgeneralize from the source material.
- Cannot replace advice from human experts or organizations.


## Repository Layout

Each skill is a self-contained folder with a `SKILL.md` entry point plus supporting references, checklists, and examples. The `life-science-research-handbook` "skill" works as a reference package.

```text
README.md
LICENSE
images/                               # README illustrations
handbook/                             # Reading edition; can be served online
  index.html
  life-science-research-handbook.pdf
  handbook-index.json                 # Chapter paths and section identifiers
  reader/                             # Agent-readable Markdown chapters
  ...                                 # HTML chapters and supporting assets
skills/
  <task-skill>/                        # Ten task skills
    SKILL.md
    references/
    checklists/
    examples/
  life-science-research-handbook/
    SKILL.md
    agents/openai.yaml                # Disables automatic triggering
    references/handbook/              # Complete local handbook edition
```

`SKILL.md` defines when the skill should trigger, how the agent should work, which reference files to open, and what output formats to use.

## License

MIT. See [LICENSE](./LICENSE).
