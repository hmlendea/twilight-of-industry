---
description: Chapter body composition, chronology, and section-structure rules for chapter files.
applyTo: "chapters/**/*.md"
---

## Chapter Composition Rules

- After frontmatter, start with a level-1 heading in the format `# <year or range> — <opening label>`.
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
- Conclude with an end-of-period synthesis section containing:
  - world-by-world status blocks (population, change, sovereignty, IRF, life expectancy, living standards, major developments);
  - optional `Newly practical` capability notes per world where relevant;
  - a final major-project status recap.
- Each chapter must end with a `Next chapter` navigation line that links to the subsequent chapter file.
- Use this exact format for the final line in the file: `Next chapter: [<next chapter label>](<next chapter filename>.md)`.
- The line immediately before `Next chapter` must be a horizontal separator line: `---`.
- Keep the `Next chapter` line as the final non-empty line in the chapter.
