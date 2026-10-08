# Literature Tracking

Use this when the user wants to stay current, design alerts, triage papers over time, or repair an overwhelming reading queue.

## Use this when...

- The user asks how to follow a field or topic.
- Alerts, feeds, journals, newsletters, or preprints are too noisy or too sparse.
- The user needs a weekly paper triage routine.
- The user wants to map source types for a field.

## The job of this topic

Build a sustainable literature-tracking system. The goal is not maximum coverage; it is a stream the user can process, tune, and convert into selected deep reads and synthesis updates.

## Default workflow

1. Define the tracking goal: broad field awareness, narrow topic, method/tool updates, author/lab tracking, or review-oriented orientation.
2. Create a small source portfolio with distinct roles:
   - database/topic feeds for relevance
   - journal or venue feeds for field awareness
   - author/lab alerts for known groups
   - review sources for orientation
   - informal channels only as discovery leads to verify
3. Estimate weekly volume before adding a source.
4. Define triage actions: ignore, save, skim, deep read, follow citation trail, or add to synthesis.
5. Scan weekly and keep a curated backlog.
6. Tune noisy, empty, or redundant feeds.
7. Expand only after the current system is stable.

## Decision rules

- If the stream is too large to scan weekly, narrow queries, reduce feeds, or split topics into more specific feeds.
- If most alerts are irrelevant, fix query design before adding sources.
- If important papers are missing, add a complementary source role rather than many more feeds.
- If the user is busy, preserve a focused route for imminent decisions and defer optional reading. Label saved items with their purpose and actual reading status; saving is not appraisal.
- If saved papers are never revisited, add a backlog review step or reduce intake volume.

## Variants and edge cases

- **New field:** Start with reviews and broad venues, then add topic queries as vocabulary improves.
- **Fast-moving method:** Add preprint or community discovery channels, but verify against the primary paper.
- **Known lab or author:** Use author/lab alerts, but do not let them replace topic searches.
- **Sparse field:** Broaden terms, add adjacent fields, and track review sources.
- **Noisy common term:** Narrow the query with field, organism, method, date, or exclusion terms.

## Anti-patterns

- Subscribing to every plausible source during setup.
- Using one generic query for a whole field.
- Keeping a discovery route that the user cannot sustain, whether automated alerts or manual visits. A scheduled visit can work if it delivers the needed material within the available time.
- Treating exact venue lists as universal or timeless.
- Saving everything without a review routine.
- Counting duplicate alerts as new papers or using a recent-paper stream as an exhaustive search for a claim.

## Diagnostic questions

- Can the user scan the stream weekly?
- Does every source have a purpose?
- Is the expected volume realistic?
- Are irrelevant results mostly a query problem or a source problem?
- Are saved papers being converted into reads, notes, or synthesis?
- Has the system been stable long enough to justify expansion?

## Output patterns / mini-templates

### Alert portfolio

| Source/feed | Type | Purpose | Scope/query | Expected weekly volume | Triage action | Prune/expand date |
|---|---|---|---|---:|---|---|

### Weekly triage queue

| Paper | Source/feed | Why it surfaced | Relevance | Decision | Follow-up note | Backlog status |
|---|---|---|---|---|---|---|

### Field source map

| Field layer | Example source type | What it reveals | Review frequency | Known bias/gap |
|---|---|---|---|---|

## Examples

- A starter stream can combine a few specific topic feeds with a small set of high-value venues, then remain unchanged until weekly scanning is stable.
- If a stream produces many irrelevant papers, narrow it before adding more sources.
- If the user repeatedly saves papers and never reads them, the system is too large or the backlog action is undefined.

## When not to apply this

- Do not apply tracking setup when the user needs to read one known paper now.
- Do not provide citation-manager-specific mechanics from this package; they are not source-backed here.
