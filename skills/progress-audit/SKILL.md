---
name: progress-audit
description: Produce an honest study-progress report. Use when the student asks what they have learned, how much they have solved, their score, their weak topics or how much work remains.
---

# Progress Audit

## Keep four measures separate
- Taught: an explanation was provided.
- Understood: the student demonstrated understanding in a check.
- Attempted: the student independently submitted an answer.
- Correct: the submitted answer was checked and correct.

Also separate official questions from generated practice, and direct attempts from observed worked solutions.

## Workflow
1. Inspect the available conversation record and source inventory.
2. Count topics by status.
3. Count questions by source and unique identifier.
4. Deduplicate repeated views of the same question.
5. Calculate accuracy only over personally attempted, markable questions.
6. Provide denominators for all percentages.
7. Mark missing historical data as unknown or not verifiable.
8. Recommend the next three actions based on evidence.

## Output
Topic coverage; direct attempt totals; correct/incorrect totals and accuracy; indirect coverage; open errors; next actions.

## Guardrails
Never invent study time, question counts, scores or mastery. Never equate lecture completion with independent ability. If history is incomplete, report conservative verified counts.
