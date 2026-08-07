---
description: Repository-specific README rules, including Reading Sequence maintenance and table formatting.
applyTo: "README.md"
---

## README Rules

- Keep the `Reading Sequence` section as a Markdown table with exactly these columns in this order:
  - `Period`
  - `Chapter`
  - `Summary`
- Keep `Reading Sequence` entries in strict chronological order.
- In `Chapter`, use the chapter title as the link text and link to the corresponding chapter file.
- In `Period`, display a single year or year range in plain text:
  - For 4-digit years, do not use a thousands separator (for example `2026`).
  - For 5+ digit years, use comma grouping (for example `10,000`, `117,260`, `100,011 - 100,100`).
- In `Summary`, use a very short synopsis aligned to each chapter frontmatter `summary` value.
- Keep summary lengths approximately consistent across all rows.
- When changing a chapter `name` value, update the corresponding `Chapter` cell in `Reading Sequence`.
- When adding a new chapter file, add the corresponding row to `Reading Sequence` in the same change.