# Academic Writing Polish

A lightweight ChatGPT skill for polishing academic manuscripts in Chinese and English.

This skill is designed for academic editing, manuscript refinement, AI-artifact removal, logical flow improvement, journal/thesis style adaptation, translation polishing, and section-level revision. It helps improve clarity, precision, conciseness, formality, terminology consistency, and academic readability while preserving the author's original meaning and claims.

## Features

- Polish Chinese and English academic manuscripts
- Improve clarity, logic, coherence, and academic tone
- Support journal papers, theses, abstracts, section drafts, cover letters, and response letters
- Remove common AI-generated writing patterns and inflated expressions
- Adapt writing to journal, conference, thesis, supervisor, or reference style when provided
- Support minimal editing, standard polishing, deep polishing, comparison output, and diagnosis mode
- Preserve LaTeX, Markdown structure, equations, citations, figure/table labels, and numbering
- Avoid fabricated citations, data, references, results, and unsupported claims

## Use Cases

Use this skill when you need to:

- polish an academic paragraph or section;
- refine a Chinese or English manuscript;
- improve the logic of an Introduction, Related Work, Methods, Results, Discussion, or Conclusion section;
- weaken AI-like wording in academic writing;
- polish translated academic text;
- revise a thesis chapter according to academic writing standards;
- prepare or refine a response letter to reviewers;
- diagnose problems in manuscript language, structure, or style.

## Repository Structure

```text
academic-writing-polish/
├── SKILL.md
├── references/
│   ├── editing-rules.md
│   ├── output-modes.md
│   └── section-and-style.md
└── scripts/
    └── README.md
```

## File Overview

### `SKILL.md`

The main skill definition file. It defines the skill metadata, use cases, core behavior, workflow, hard constraints, and default response behavior.

### `references/editing-rules.md`

General academic editing rules, including clarity, logic, precision, conciseness, formality, consistency, AI-artifact removal, citation constraints, and grammar rules for Chinese and English.

### `references/output-modes.md`

Output mode definitions, including minimal edit, standard polish, deep polish, refined-text-only output, comparison mode, diagnosis mode, and file-based revision.

### `references/section-and-style.md`

Section-specific and style-specific guidelines for abstracts, introductions, related work, methods, results, discussion, conclusions, figure/table captions, response letters, Chinese theses, and English academic papers.

### `scripts/README.md`

Reserved for optional future scripts. The current version does not require executable scripts.

## Editing Modes

### Standard Polish

The default mode. It improves academic tone, clarity, fluency, conciseness, and logical flow while preserving the original structure and meaning.

Example:

```text
请帮我润色下面这段论文内容，要求学术、正式、逻辑更清晰。
```

### Minimal Edit

Preserves the original sentence structure as much as possible and only fixes necessary grammar, wording, clarity, and terminology issues.

Example:

```text
请最小修改下面这段话，不要大改原句结构。
```

### Deep Polish

Allows stronger rewriting for paragraph-level or section-level improvement. It can improve transitions, reorganize local sentence flow, and strengthen academic logic without adding unsupported content.

Example:

```text
请深度润色下面的 Introduction，使其更符合论文写作逻辑。
```

### Refined Text Only

Outputs only the polished text without explanations, comments, or revision notes.

Example:

```text
Only output the refined text.
```

### Comparison Mode

Outputs the original text, revised text, and revision reason in a comparison table.

Example:

```text
请用三列表格输出：原文、修改后文本、修改原因。
```

### Diagnosis Mode

Analyzes the main problems in the text before or alongside revision, such as unclear logic, weak claims, redundancy, or inappropriate academic tone.

Example:

```text
请判断这段 Introduction 是否符合论文写作逻辑，并指出主要问题。
```

## Design Principles

- Preserve the author's meaning, claims, evidence, terminology, and academic judgment.
- Do not fabricate citations, references, data, experiments, results, or conclusions.
- Do not over-polish with rare words, inflated expressions, or unnatural complexity.
- Prefer clear, precise, and readable academic language.
- Soften unsupported strong claims when necessary.
- Respect user-specified editing strength and output format.
- Preserve technical formatting such as LaTeX commands, equations, citations, Markdown headings, and figure/table labels.

## Example Prompts

```text
Please polish the following paragraph for an academic journal. Improve clarity, conciseness, and logical flow while preserving the original meaning.
```

```text
请帮我润色下面这段中文论文内容，要求语言更正式、逻辑更清晰，但不要改变原意。
```

```text
请帮我去除下面文本中的 AI 痕迹，使其更像自然的学术写作。
```

```text
请按照本科毕业论文的写作标准润色下面这一节，可以适当合并或扩写小节以增强逻辑连贯性。
```

```text
请用对照表给出修改结果，包括原文、修改后文本和修改原因。
```

## Limitations

This skill focuses on academic language polishing and manuscript presentation. It does not replace domain expert review, statistical validation, literature review, or factual verification.

It should not be used to fabricate references, exaggerate findings, create unsupported conclusions, or guarantee acceptance by a journal, conference, or university.

## Suggested GitHub Topics

```text
academic-writing
chatgpt-skill
manuscript-polishing
scientific-writing
thesis-writing
academic-editing
ai-writing
prompt-engineering
chinese-academic-writing
english-academic-writing
```

## License

This project is licensed under the MIT License.

## Author

Chaojun Zhang

## Version

`1.0.0`
