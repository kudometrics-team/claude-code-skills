---
name: information-gain-researcher
description: Use when researching stats, primary sources, or expert angles to add information gain to content (listicles, articles) so AI engines cite it. Run the filetype:/site: search patterns and compile a sourced stats document.
---

# Information Gain Researcher

Mine primary-source documents to add "information gain" — unique data and expertise that makes a page the one AI engines (ChatGPT, Perplexity, Gemini, Google AI Overviews) cite instead of the near-identical pages above and below it in search results.

## When to use

- Writing or refreshing a listicle, blog post, or landing page that must rank AND get cited by AI engines.
- The user asks to "add information gain", "find unique stats", "mine primary sources", or make content "not generic".

## The 4 information-gain levers

1. First-party data — original numbers, internal tests, before/after metrics, real screenshots.
2. Expert perspective — practitioner quotes, counter-points, a named framework.
3. Unanswered questions — support tickets, forums, the reader's next question beyond the title.
4. Primary-source documents — PDFs/PPTs/DOCs that never surface in normal search.

## Search patterns (run these for the topic)

Run each via web search (or a Google SERP tool), using the current year where relevant:

- "{topic}" filetype:pdf
- "{topic}" site:edu
- "{topic}" site:gov and "{topic}" inurl:gov
- "{topic}" filetype:ppt / filetype:xlsx / filetype:doc
- "{topic}" inurl:report / inurl:research / inurl:survey
- "{topic}" statistics / "{topic}" survey / "{topic}" study

## Output

Compile a sourced markdown document with one row per stat:

| Stat | Source | Year | File type | Suggested use |
|---|---|---|---|---|

Then convert to .docx for the content team (pandoc).

## Rule (non-negotiable)

AI invents statistics. Open the original source and confirm the number, date, and attribution before anything is published. If the source cannot be opened, mark the stat UNVERIFIED and do not use it.

## How it feeds listicle writing

This skill supplies the information-gain ammunition. The writing itself uses the house voice guide plus the content brief. A cited listicle = this skill's stats and angles + a ranking structure + a clear "why this one" per entry.
