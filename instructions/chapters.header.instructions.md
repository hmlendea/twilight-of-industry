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
- Derive metadata from the completed body: include all factions with substantive participation or a material status change, including regional compacts and political alliances, not only planetary governments.
- Use canonical institutional names consistently in metadata and prose; do not create aliases or imply a foundation through a paraphrased label.
- If additional frontmatter keys are needed, place them after the required keys above unless explicitly instructed otherwise.
