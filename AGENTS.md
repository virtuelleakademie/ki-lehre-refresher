# AGENTS.md

This file provides guidance when working with code in this repository.

## Project Overview

A Quarto website presenting the current state of AI in higher education. Content is in German, targeting staff at Swiss universities.

## Build Commands

```bash
quarto preview          # Live preview on port 8800
quarto render           # Build site to /docs/
```

## Project Structure

- `_quarto.yml` – Main configuration (navigation, custom callouts, filters)
- `index.qmd` – Welcome/landing page
- `presentation/index.qmd` – Embeds the RevealJS slides
- `slides/ai-higher-ed/index.qmd` – RevealJS presentation source
- `qa/index.qmd` – Q&A and further research page
- `docs/` – Rendered output (deployed to GitHub Pages)
- `_extensions/` – Quarto extensions (timer, custom-callout)

## Writing Conventions

**Language:** German with Swiss spelling conventions:

- Use "ss" instead of "ß" (e.g., "weisst" not "weißt")
- Address readers with informal "du" form, not formal "Sie"
- No emojis in content
- Do not use em-dashes ("---" or "—"). Use colons or restructure sentences instead.
- Do not use dividing lines ("---" on its own line) except in YAML headers
- Ensure blank line above all markdown lists

## Custom Callouts

Defined in `_quarto.yml`, use in content like:

```markdown
::: {.experiment}
## Title
Content here
:::
```

Available types: `experiment`, `demonstration`, `individual`, `pair`, `group`, `reflect`, `pro-tip`, `warning`, `key-point`, `scenario`, `source-check`

## Timer Extension

Add countdown timers with:

```markdown
{{< timer 5 >}}
```
