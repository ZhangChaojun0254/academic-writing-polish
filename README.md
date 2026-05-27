# Academic Writing Polish

A lightweight ChatGPT skill for polishing academic manuscripts in Chinese and English.

This skill is designed for academic editing, manuscript refinement, AI-artifact removal, logical flow improvement, journal/thesis style adaptation, translation polishing, and section-level revision. It supports common academic writing scenarios such as research papers, review papers, theses, abstracts, introductions, methods, results, conclusions, cover letters, and response letters.

## Overview

`academic-writing-polish` provides a structured editing workflow for academic texts. It helps improve clarity, logic, precision, conciseness, formality, terminology consistency, and style suitability while preserving the author's original meaning and claims.

The skill is intentionally lightweight. It does not rely on external scripts or complex dependencies. Instead, it uses a main `SKILL.md` file and several reference files to define editing principles, output modes, and section-specific writing guidelines.

## Key Features

### Academic manuscript polishing

The skill can polish Chinese and English academic writing by improving:

- sentence clarity;
- paragraph coherence;
- logical flow;
- academic tone;
- grammatical correctness;
- terminology consistency;
- conciseness;
- precision of claims;
- figure/table description style;
- section-level readability.

### Chinese and English support

The skill supports both Chinese and English academic texts.

For Chinese academic writing, it focuses on:

- reducing empty or slogan-like expressions;
- improving sentence fluency;
- strengthening paragraph transitions;
- reducing overuse of expressions such as “进行”;
- maintaining formal but natural academic prose;
- adapting to undergraduate, master’s, or doctoral thesis style.

For English academic writing, it focuses on:

- improving grammatical accuracy;
- reducing excessive nominalization;
- avoiding inflated or unnatural wording;
- preserving cautious academic claims;
- maintaining stable technical terminology;
- improving journal-style readability.

### AI-artifact removal

The skill can identify and revise common AI-generated writing patterns, including:

- generic openings;
- inflated contribution claims;
- repetitive transition words;
- vague academic clichés;
- overly symmetrical paragraph structures;
- unsupported broad claims;
- unnatural wording caused by direct translation.

It does not simply replace stock phrases with synonyms. Instead, it rewrites the sentence so that it states a concrete problem, method, result, limitation, or contribution.

### Multiple editing modes

The skill supports different revision strengths and output formats.

Supported modes include:

- minimal edit;
- standard polish;
- deep polish;
- refined-text-only output;
- comparison-based editing;
- diagnosis mode;
- file-based revision.

This makes it suitable for both quick language polishing and deeper manuscript improvement.

### Section-specific academic editing

The skill includes section-aware editing guidelines for:

- Abstract;
- Introduction;
- Related Work;
- Methods;
- Results;
- Discussion;
- Conclusion;
- Figure and table captions;
- Response letters;
- Thesis chapters.

It adapts editing strategies according to the function of each section instead of applying the same rewriting style everywhere.

### Style adaptation

When the user provides a target journal, conference, thesis requirement, supervisor preference, or reference sample, the skill can adapt the writing style by considering:

- sentence length;
- formality;
- active/passive voice balance;
- terminology density;
- contribution phrasing;
- citation placement;
- paragraph structure;
- figure/table description style.

The skill extracts style features from the target context rather than mechanically copying wording.

## Use Cases

This skill is useful for:

- polishing academic papers;
- revising thesis chapters;
- improving abstracts and introductions;
- refining related work sections;
- improving methods and results descriptions;
- editing discussion and conclusion sections;
- weakening AI-like writing traces;
- polishing Chinese-to-English academic translation;
- polishing English-to-Chinese academic translation;
- preparing response letters to reviewers;
- revising cover letters;
- diagnosing weaknesses in manuscript writing;
- converting rough drafts into formal academic prose.

## When to Use This Skill

Use this skill when the user asks to:

- polish academic text;
- revise manuscript language;
- improve logical flow;
- remove AI-generated patterns;
- make writing more formal;
- make writing more concise;
- adapt text to journal or thesis style;
- improve translation quality;
- diagnose academic writing problems;
- compare original and revised versions.
