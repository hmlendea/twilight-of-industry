---
description: Chapter body composition, chronology, and section-structure rules for chapter files.
applyTo: "chapters/**/*.md"
---

## Chapter Composition Rules

- After frontmatter, start with a level-1 heading in the format `# <year or range> — <opening label>`.
- In displayed chapter text, format years as follows: do not use a thousands separator for 4-digit years (for example `2026`), and use comma grouping for 5+ digit years (for example `10,000`, `117,260`).
- Open the chapter body with a concise baseline snapshot section that establishes starting conditions.
- Use a world-status table early in the chapter for population, sovereignty, and IRF context when relevant.
- Keep the main narrative in chronological order.
- Structure chronological entries as level-2 headings using one of these patterns:
  - `## <day> <month> <year> — <event label>`
  - `## <year> — <event label>`
  - `## <year>-<year> — <event label>`
- Use level-3 subheadings only for clear subdivisions inside a dated section.
- Separate major sections with horizontal rules (`---`) to keep long chapters readable.
- Prefer compact paragraphs followed by factual bullet lists for:
  - drivers and causes;
  - effects and consequences;
  - policy or technical details;
  - constraints and trade-offs.
- Keep terminology and named programmes consistent across the whole chapter.
- Whenever generating a place name is required, consider selecting one from: `https://raw.githubusercontent.com/hmlendea/stellaris-ui-star-names/refs/heads/master/ui-star-names/common/random_names/base/ui_stars_zzz_made-up.txt`.
- Aim for approximately 2,000 lines of chapter content per file.
- For this length target, do not count:
  - the YAML frontmatter header block;
  - the chapter title markdown header line (`# <year or range> — <opening label>`);
  - the navigation footer block at the end (`---`, the `Previous chapter: ...` line, and the `Next chapter: ...` line).
- Treat the length target as a planning objective rather than a strict limit; broadly ±10% around 2,000 content lines is acceptable when required by narrative coherence.
- Conclude with an end-of-period synthesis section containing:
  - world-by-world status blocks (population, change, sovereignty, IRF, life expectancy, living standards, major developments);
  - optional `Newly practical` capability notes per world where relevant;
  - a final major-project status recap.
- Each chapter must end with navigation lines that link to both the previous and subsequent chapter files.
- Use this exact format for the navigation lines:
  - `Previous chapter: [<previous chapter label>](<previous chapter filename>.md)`
  - `Next chapter: [<next chapter label>](<next chapter filename>.md)`
- The line immediately before `Previous chapter` must be a horizontal separator line: `---`.
- Keep the `Next chapter` line as the final non-empty line in the chapter.
