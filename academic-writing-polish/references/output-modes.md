# Output Modes

Use this reference to decide how to present results.

## Default mode

Return the polished text first. Add brief revision notes only when they help the user and were not forbidden.

## Refined-text-only mode

Trigger when the user says:

- “只输出润色后文本”
- “只给修改后的版本”
- “only refined text”
- “no explanation”
- “不要解释”

In this mode, output only the revised content. Do not add greetings, notes, summaries, or explanations.

## Minimal-edit mode

Trigger when the user says:

- “最小修改”
- “保留原句”
- “不要大改”
- “minor revision only”

Preserve original structure and wording as much as possible. Fix only grammar, clarity, terminology, consistency, and obvious academic style issues.

## Standard-polish mode

Default mode. Improve clarity, flow, academic tone, conciseness, and AI-artifact issues while preserving structure and meaning.

## Deep-polish mode

Trigger when the user asks for deep polishing, logical reconstruction, thesis-level improvement, journal adaptation, or section-level rewriting.

Allowed actions:

- rewrite awkward sentences;
- improve paragraph transitions;
- reorganize sentences within a paragraph;
- strengthen topic sentences;
- suggest section merging or expansion;
- add minimal transition sentences if requested.

Forbidden unless explicitly requested:

- adding new claims;
- adding unsupported literature;
- inventing results;
- changing the research meaning.

## Comparison mode

Use when the user wants to learn from the edits. Present:

| Original | Revised | Reason |
|---|---|---|

Keep reasons brief and actionable.

## Diagnosis mode

Use when the user asks whether the text is good, whether it meets a standard, or what problems remain. Provide:

1. main problems;
2. revised text or representative revisions;
3. concise suggestions.

## File output mode

When polishing a file, preserve the original file unless the user asks to overwrite it. Save the revised version with a clear suffix such as:

- `filename-polished.md`
- `filename-revised.docx`
- `filename-edited.txt`

Keep equations, citations, headings, figure/table labels, and formatting markers intact whenever possible.
