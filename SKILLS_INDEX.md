# Exam-OS Skills

Exam-OS includes modular Agent Skills-style workflows. Each skill is a folder with a SKILL.md file containing YAML metadata and task instructions.

## Skills catalogue

| Skill | Trigger | Main result |
|---|---|---|
| [Course intake](skills/course-intake/SKILL.md) | New course or exam | Exam profile, source inventory, syllabus map |
| [Source-grounded audit](skills/source-grounded-audit/SKILL.md) | PDFs, official questions, coverage checks | Exact source-backed question and topic inventory |
| [Concept tutor](skills/concept-tutor/SKILL.md) | Teach, explain, or confusing topic | Layered explanation and understanding check |
| [Visual explainer](skills/visual-explainer/SKILL.md) | Abstract idea or screenshot | Accurate diagram and visual walkthrough |
| [Batch practice](skills/batch-practice/SKILL.md) | MCQs, practice, answer checking | Batched questions and detailed marking |
| [Worked problem coach](skills/worked-problem-coach/SKILL.md) | Calculations, proofs, coding | Step-by-step reasoning and independent follow-up |
| [Error remediation](skills/error-remediation/SKILL.md) | Wrong or repeated answers | Root-cause diagnosis and targeted re-test |
| [Progress audit](skills/progress-audit/SKILL.md) | Learning totals or weaknesses | Evidence-based learning and question dashboard |
| [Mock exam](skills/mock-exam/SKILL.md) | Exam simulation | Mock paper and performance report |
| [Cram mode](skills/cram-mode/SKILL.md) | Exam imminent or formula sheet | Prioritised final revision |
| [Skill evaluation](skills/skill-evaluation/SKILL.md) | Create or improve a prompt/skill | Test cases, rubric and iteration plan |

## Recommended sequence

Course intake → source audit → concept tutor / visual explainer → batch practice / worked problem coach → error remediation → progress audit → mock exam → cram mode.

## Compatibility

These are portable Markdown skill instructions using the public Agent Skills-style folder pattern. An agent environment that supports SKILL.md folders can load them as skills. ChatGPT does not automatically load arbitrary GitHub skill folders: in ChatGPT, open the relevant SKILL.md and paste or attach its contents, or use the matching prompt template in prompts/.

## Design principles

Descriptions explain when a skill should activate. The skill body gives its workflow. Supporting resources are linked only when needed. This keeps the system modular and easier to inspect than one oversized instruction file.
