---
name: career-development
description: "Use this skill when a scientist needs stage-specific career help with advisor or lab choice, PhD/postdoc/faculty applications, CVs, resumes, cover letters, recommendation-letter scaffolds, referee evidence packets, interviews, offers, startup negotiation, academia-to-industry transitions, job ad interpretation, networking, or a concrete career-path decision. Trigger when the input is a career artifact, opportunity, role comparison, application package, or personal career constraint. Do not trigger for manuscript, grant, figure, project-strategy, journal-selection, or lab-management tasks unless the main issue is the user's own career decision."
license: MIT
metadata:
  author: jjfroehlich
  version: "0.1.0"
---

# Career Development

## Purpose

Turn scientist career questions into concrete decisions, document edits, interview preparation, and next actions.

## Use this skill when

- The user is choosing an advisor, PhD program, postdoc lab, faculty path, industry role, or other career option.
- The user provides a CV, resume, cover letter, recommendation-letter scaffold, recommender evidence packet, application package, job ad, interview plan, offer, or outreach draft.
- The user asks how to translate scientific training for a non-academic reader.
- The user needs scientist-specific career guidance rather than generic job-search advice.

## Do not use this skill when

- The main task is manuscript, grant, poster, or figure feedback.
- The user is asking how to manage a lab member rather than make their own career decision.
- The request is a broad sociology-of-academia discussion without a decision, artifact, or next action.
- The user needs legal, visa, medical, or mental-health advice beyond practical career framing and referral to appropriate support.

## Core workflow

1. Identify the user's stage, target role, decision, reader, artifact type, deadline, and hard constraints.
2. Route to the narrowest relevant playbook before giving advice.
3. Convert claims about fit, readiness, promise, or risk into evidence the reader or decision maker can verify.
4. Separate document strategy from relationship, safety, negotiation, or career-path strategy.
5. Name tradeoffs and uncertainty explicitly when evidence is incomplete.
6. End with concrete edits, questions to ask, screening criteria, or a short action plan.

## Output formats

- Advisor or lab evaluation matrix.
- Application-materials critique.
- CV/resume or cover-letter revision plan.
- Career-path comparison table.
- Interview preparation plan.
- Offer or startup negotiation checklist.
- Recommendation-letter scaffold or recommender evidence packet.

## Reference routing

- `references/advisor-choice.md`: Use for advisor, mentor, lab-environment, power, and safety evaluations.
- `references/phd-applications.md`: Use for PhD program selection, prospective-advisor questions, funding, rotations, and milestones.
- `references/postdoc-applications.md`: Use for postdoc search, lab comparison, project ownership, independence, and career launch.
- `references/faculty-search.md`: Use for faculty application packages, job-market strategy, startup negotiation, and independent-lab readiness.
- `references/cv-resume.md`: Use for academic CVs, industry resumes, document genre choice, and bullet translation.
- `references/cover-letters.md`: Use for job, internship, postdoc, faculty, and first-contact letters.
- `references/interviews.md`: Use for scientific job, industry, postdoc, and faculty interview preparation.
- `references/recommendation-letters.md`: Use when the user was asked to draft a recommendation scaffold or needs a recommender evidence packet.
- `references/career-transitions.md`: Use for academia/industry comparisons, leaving-path decisions, networking, and role exploration.
- `checklists/advisor-evaluation-checklist.md`: Use for a fast advisor, mentor, or lab evidence matrix.
- `checklists/postdoc-choice-checklist.md`: Use for postdoc offer and lab comparison.
- `checklists/faculty-search-checklist.md`: Use for faculty-search readiness and package audits.
- `checklists/application-review-checklist.md`: Use for CV, resume, cover-letter, and packet review triage.
- `examples/career-material-examples.md`: Use when the user needs a concrete table or rewrite pattern.
- `examples/advisor-question-bank.md`: Use when preparing advisor, trainee, or alumni questions.

## Quick checklist

- What decision or reader is this answer serving?
- What evidence would change the outcome?
- Which constraints are hard, negotiable, or unknown?
- Which playbook applies, and which near-miss playbook should stay out?
- What is the next concrete action the user can take?

## Common pitfalls

- Giving generic encouragement instead of stage-specific career advice.
- Treating prestige, publication venue, salary, or job title as the whole decision.
- Rewriting documents without naming the reader's decision criteria.
- Ignoring power asymmetry, retaliation risk, funding, visa, health, or family constraints.
- Copying source fragments, bibliographic details, raw URLs, or provenance into the answer.
- Writing final recommender judgment, comparative rank, or private recommender voice when the user should only supply evidence.

## Quality bar

- Advice is specific to the user's stage, target role, artifact, and constraints.
- Claims are tied to evidence, observable signals, or clear assumptions.
- The answer uses the right playbook and avoids over-triggering on nearby writing, grant, or lab-management tasks.
- The output leaves the user with edits, questions, criteria, or a practical next-step plan.
