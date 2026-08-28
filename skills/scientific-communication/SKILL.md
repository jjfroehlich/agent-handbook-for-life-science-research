---
name: scientific-communication
description: "Use when the user needs to design, review, adapt, or rehearse scientific communication for a live, spoken, visual, or audience-facing setting: talks, slide decks, posters as presentation artifacts, chalk talks, elevator pitches, public explanations, research stories, delivery plans, timing, or Q&A preparation. Trigger from drafts, outlines, venue/audience constraints, slide or poster plans, scripts, or rehearsal concerns. Prefer writing for manuscript prose, visualization for chart/figure design decisions, and publishing for submission or peer-review logistics."
license: MIT
metadata:
  author: jjfroehlich
  version: "0.1.0"
---

# Scientific Communication

## Purpose

Help agents turn scientific content into audience-aware live or visual communication: talks that have one argument, slides and posters that can be read in the room, pitches that fit the listener, and Q&A plans that preserve credibility.

## Use this skill when

- The user asks for help with a scientific talk, seminar, conference presentation, poster, chalk talk, elevator pitch, research story, or public-facing explanation.
- The artifact is a slide outline, slide deck, poster layout, spoken script, title, abstract-for-a-talk, presentation plan, or Q&A preparation note.
- The user needs structure, cuts, visual hierarchy, delivery rehearsal, audience adaptation, or a short spoken version of research.
- The user asks for a communication review rather than manuscript editing, figure publication review, grant strategy, or peer-review response.

## Do not use this skill when

- The user primarily needs manuscript prose, paper organization, cover letters, or reviewer responses.
- The task is only about choosing or coding a data visualization for a publication figure.
- The request is about research strategy, experimental design, citation management, or conference logistics without a communication artifact.
- The user wants generic public-speaking motivation rather than concrete scientific communication work.

## Core workflow

1. Identify the medium, audience, stakes, time/space limit, and the one message the audience should retain before building slides.
2. Diagnose the main failure mode: unclear premise, overloaded detail, weak audience bridge, unreadable visuals, poor format fit, or unprepared delivery/Q&A.
3. Route to the narrowest useful playbook. Open only the needed reference unless the artifact spans formats.
4. Make cuts before polish. Preserve what supports audience belief, orientation, or action; move secondary details to backup, handout, speaker notes, or conversation.
5. Produce a concrete artifact: revised outline, slide-by-slide plan, poster redesign, pitch script, chalk-talk board plan, Q&A prep list, or prioritized checklist.
6. State assumptions when audience, timing, venue, or visual access is missing. Ask at most the clarifying questions needed to avoid a misleading recommendation.

## Output formats

- Talk outline: `audience -> premise -> hook or governing message -> 2-3 main moves -> decisive evidence -> close -> backup/Q&A`.
- Slide review: `top failure -> cuts -> slide order -> per-slide job -> visual fixes -> rehearsal check`.
- Poster redesign: `main claim -> layout hierarchy -> text cuts -> figure treatment -> standing-distance checks -> 30-second walkthrough`.
- Elevator pitch: `listener -> opening hook -> problem -> approach -> payoff -> ask/next step`.
- Chalk talk plan: `opening board map -> research program modules -> interruption plan -> feasibility/vision evidence -> closing ask`.
- Delivery/Q&A prep: `likely questions -> answer moves -> bridge phrases -> rehearsal plan -> failure recovery`.

## Reference routing

- `references/talk-structure.md`: Open for seminars, conference talks, thesis talks, or slide order problems.
- `references/slide-design.md`: Open for slide density, visual hierarchy, figure adaptation, text-heavy slides, or deck mechanics.
- `references/posters.md`: Open for conference posters, digital posters, poster walkthroughs, or poster redesign.
- `references/chalk-talks.md`: Open for faculty interview chalk talks, board-based research plans, or highly interactive research vision sessions.
- `references/elevator-pitches.md`: Open for short spoken summaries, networking pitches, lay explanations, or timed project introductions.
- `references/storytelling.md`: Open when the user needs narrative framing, audience memory, tension, explanation, or a stronger through-line.
- `references/delivery-and-qa.md`: Open for rehearsal, vocal/physical delivery, question handling, nerves, timing, or audience interaction.
- `checklists/talk-review.md`: Use for a fast final review of a talk or deck.
- `checklists/poster-review.md`: Use for a final poster review before print, upload, or presentation.
- `examples/communication-feedback-examples.md`: Open when the user needs a model output pattern.

## Quick checklist

- What is the one sentence the audience should remember?
- Who is the audience, and what do they already believe or need?
- What can be cut, moved to backup, or left for conversation?
- Can the visual artifact be understood at the expected distance or screen size?
- Does each slide, panel, board section, or pitch sentence have one job?
- Is the opening orienting, the close specific, and the Q&A plan credible?

## Common pitfalls

- Treating a talk like a paper, a poster like a manuscript wall, or a chalk talk like a polished seminar.
- Fixing wording before deciding the message, audience bridge, and cuts.
- Letting methods, caveats, or secondary data compete with the main claim.
- Copying paper figures into talks or posters without redesigning labels, scale, and visual order.
- Asking too many clarifying questions when a first-pass plan with explicit assumptions would help.
- Starting slide production before deciding audience, message, and explanation path.

## Quality bar

- Advice must be medium-specific and audience-specific.
- The answer must include concrete cuts, ordering, visual hierarchy, rehearsal moves, or Q&A moves.
- The agent must preserve scientific uncertainty while still making the communication sharper.
- Public-facing outputs must not expose source provenance, bibliographies, raw URLs, or private-source details.
