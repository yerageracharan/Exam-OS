---
name: source-grounded-audit
description: Inspect lecture PDFs, revision sheets, tutorial papers and past exams when exact course content or official question wording matters. Use whenever the student asks for official MCQs, formulas from slides, coverage checks, source mapping or question extraction.
---

# Source-Grounded Audit

## Goal
Extract what the course source actually says, preserving its identifiers and distinguishing source facts from interpretation.

## Workflow
1. Locate the exact file and inspect the relevant pages or slides.
2. Record source name and page/slide range.
3. Extract definitions, formulas, diagrams, examples and questions relevant to the topic.
4. Preserve official wording, options, numbering and diagram references as faithfully as possible.
5. Mark whether an answer is supplied by the source or independently derived.
6. Flag unreadable diagrams, incomplete options, scanned pages or ambiguous notation.
7. Separate official course material, assistant explanation and generated practice.

## Output
Source checked; topic/question identifiers; extracted content; answer status (provided, independently derived or unknown); ambiguities and limitations.

## Guardrails
Never label an invented question as official. Never silently simplify an official question. Never reconstruct an unreadable diagram by guessing. Do not present an interpretation as a lecturer's statement.
