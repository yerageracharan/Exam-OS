---
name: skill-evaluation
description: Create, review or improve an Exam-OS prompt or skill. Use when someone asks to create a study skill, improve triggering instructions, evaluate a workflow or make the system more reliable for other students.
---

# Skill Evaluation

## Goal
Improve skills using representative tasks and observable checks rather than adding instructions by intuition alone.

## Workflow
1. State the skill's purpose, activation contexts and expected output.
2. Inspect existing prompts and skills to avoid duplication.
3. Draft the smallest useful instruction set.
4. Create 2–3 realistic test prompts.
5. Define observable checks for each test.
6. Run tests with the skill and compare against a baseline or previous version when an execution environment is available.
7. Review failures, ambiguity and unnecessary complexity.
8. Revise only the parts tied to observed issues.
9. Update the skill index and test cases.
10. Record limitations and untested assumptions.

## Test dimensions
- Correct activation for matching requests.
- No activation for unrelated requests.
- Source grounding and exact official wording.
- Correct output structure.
- Honest accounting of independent attempts.
- Handling missing or ambiguous material.
- Evidence that the learner can apply the concept independently.

## Guardrails
Do not claim a skill is benchmarked if tests were not actually run. Do not turn subjective preferences into fake scores. Do not increase complexity without observed reason.
