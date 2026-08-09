<p align="center">
  <img src="./images/agent-skills-for-scientific-work_banner.jpg" width="900" alt="Title banner" />
</p>

# Agent Skills for Academic Research

Experimental, agent skills for academic research workflows distilled from >290 human-curated resources. 

## Skills

| Skill | Use it for |
| --- | --- |
| `career-development` | Advisor and lab choice, PhD/postdoc applications, faculty searches, CVs, cover letters, interviews, negotiation, and career transitions. |
| `data-visualization-and-figures` | Choosing, critiquing, or validating scientific visual evidence—chart form, uncertainty display, scales, color, annotations, panel composition, images, and publication readiness—not plot-code organization or mechanical implementation of settled specifications. |
| `grant-writing` | Grant and fellowship planning, specific aims, significance/innovation/approach sections, feasibility, risk plans, budgets, and reviewer-facing narratives. |
| `literature-reading-and-synthesis` | Active paper reading, claim extraction, figure unpacking, literature tracking, and synthesis matrices. |
| `mentoring-management-and-lab-culture` | Mentoring, lab handbooks, onboarding, PI leadership systems, lab culture, IDPs, feedback scripts, and conflict diagnosis. |
| `publishing-and-peer-review` | Journal submissions, cover letters, editor inquiries, peer-review reports, reviewer ethics, resubmission plans, and response-to-reviewers letters. |
| `research-strategy-and-project-design` | Choosing scientific questions, hypotheses, project directions, experimental programs, and project-level stop, pivot, or kill criteria. |
| `scientific-communication` | Talks, slide decks, posters, chalk talks, elevator pitches, research stories, audience explanations, and Q&A plans. |
| `scientific-feedback` | Integrated, prioritized, multi-lens critique of audience-facing scientific manuscripts, talks, posters, grants, study proposals, research pitches, collaborator updates, and lab-policy documents—not code, pipelines, technical plans, or requirements-to-script review. |
| `scientific-writing` | Manuscripts, thesis sections, abstracts, introductions, results, discussions, figure legends, section flow, claim calibration, and publication-ready prose. |

The current version is built from 290 public- and personal resources and notes. A private pipeline extracts principles, normalizes them into rules, and synthesizes the final skill format. This project is inspired by [awesome-life-science-resources](https://github.com/jjfroehlich/awesome-life-science-resources), a curated collection of public resources on life-science training, writing, mentoring, publishing, visualization, and careers.

## How to Install

Give your agent the repository link and tell it to install it. For example `Please install the skills at https://github.com/jjfroehlich/agent-skills-for-academic-research`. Alternatively, copy one or more folders from `skills/` into your agent's skill directory. Skills are portable across different agent systems.

## How to Use 

The skills should be triggered automatically in the right conditions. 
Just ask for advice on anything related to the above topics.
For testing, try with and without skills. 


## Related Work
There are other agent skills for scientific work; many focus on computational biology or bioinformatics: [GPTomics bioSkills](https://github.com/GPTomics/bioSkills), [ClawBio skills](https://github.com/ClawBio/ClawBio/tree/main/skills), [Google Deepmind science-skills](https://github.com/google-deepmind/science-skills), and [K-Dense-AI scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills). But others cover scientific writing and research workflows: [K-Dense-AI scientific writer](https://github.com/K-Dense-AI/claude-scientific-writer/tree/main), [Imbad0202 academic research skills](https://github.com/Imbad0202/academic-research-skills), [K-Dense-AI science-superpowers](https://github.com/K-Dense-AI/science-superpowers), and [John Kitchin research skills](https://github.com/jkitchin/skillz/tree/main/skills/research). The advantage of the skills here might be their grounding in a corpus of >290 human-curated resources.


## Limitations

- These skills are experimental and I am unsure if they are useful, useless or even harmful. 
- The extraction and synthesis process can miss context or overgeneralize from the source material.
- Cannot replace advice from human experts or organizations.


## Repository Layout

Each skill is a self-contained folder with a `SKILL.md` entry point plus supporting references, checklists, and examples. 

```text
skills/
  <skill-name>/
    SKILL.md
    references/
    checklists/
    examples/
```

`SKILL.md` defines when the skill should trigger, how the agent should work, which reference files to open, and what output formats to use. Reference files are playbooks. Checklists and examples support common review, drafting, planning, and critique tasks.

## License

MIT. See [LICENSE](./LICENSE).
