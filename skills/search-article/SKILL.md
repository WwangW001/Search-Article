---
name: search-article
description: Search, screen, compare, and synthesize academic articles for any user-specified research direction. Use when Codex is asked to find recent papers, surveys, related work, datasets, benchmarks, GitHub projects, arXiv papers, OpenReview submissions, conference papers, research trends, research gaps, or frontier directions across scientific and technical fields.
---

# Search Article

Use this skill to turn a broad research question into a focused literature scan, paper shortlist, and frontier summary.

## Workflow

1. Clarify the topic, time window, language, target output, and inclusion or exclusion criteria.
2. Build a topic profile with core terms, synonyms, adjacent fields, methods, datasets, benchmarks, venues, and application areas.
3. Search authoritative sources. Prefer official paper pages, conference proceedings, arXiv, OpenReview, PubMed, IEEE, ACM, Springer, Elsevier, Semantic Scholar, Papers with Code, and GitHub when relevant.
4. Screen candidates by relevance, novelty, method fit, venue quality, evidence strength, code or data availability, and fit to the user's goal.
5. Summarize each selected paper with problem, method, data, results, limitations, and why it matters.
6. Group papers into themes, compare methods, identify gaps, and suggest next reads or possible research directions.

## Search Strategy

When the user asks for current or recent work, browse the web and verify dates, links, venues, and paper metadata.

Generate query variants from:

- Exact topic terms and common synonyms
- Method names, model families, metrics, datasets, and benchmark names
- Top venues and workshops in the field
- Adjacent fields with transferable methods
- Phrases such as `survey`, `benchmark`, `dataset`, `state of the art`, `foundation model`, `review`, `OpenReview`, `arXiv`, and `GitHub`

Read `references/search-workflow.md` when the task needs a deeper query plan, scoring rubric, or report template.

## Output

Prefer concise structured reports:

- Search scope
- Query strategy
- Key papers
- Thematic clusters
- Methods, datasets, and benchmarks
- Open problems and research gaps
- Recommended next reads

For each paper, include a stable link and separate verified facts from inference.

## Rules

- Do not invent papers, authors, venues, dates, DOIs, GitHub repositories, or results.
- Say when a source could not be verified.
- Prefer primary sources over secondary summaries.
- If the topic is broad, produce a representative map rather than pretending to be exhaustive.
- If the user gives exclusions, apply them explicitly and mention borderline items.

## Acknowledgments
-This skill references the skill for searching papers in the field of remote sensing research, found at https://github.com/limi124/remote-sensing-research-radar/blob/main/skills/remote-sensing-research-radar/SKILL.md.

This skill further expands the searchable research areas beyond just remote sensing.
