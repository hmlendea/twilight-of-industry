---
description: Frontmatter header key priority and ordering rules for chapter files.
applyTo: "chapters/**/*.md"
---

## Chapter Header Rules

- Each chapter file must contain a YAML frontmatter header.
- The frontmatter must include these keys in this exact priority order:
  - `name`
  - `summary`
  - `period`
  - `locations`
  - `factions`
  - `events`
  - `tags`
- Do not reorder these keys.
- Inside `locations`, `factions`, `events` and `tags`, keep all items sorted alphabetically.
- If additional frontmatter keys are needed, place them after the required keys above unless explicitly instructed otherwise.
- When changing a chapter `name` value, also update the corresponding chapter entry label in the `Reading Sequence` section of `README.md` to keep chapter titles consistent.
