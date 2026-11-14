# Exam OS

A reusable, source-grounded exam-preparation toolkit built from the study workflow used across an eight-lecture university module.

Exam-OS now provides two ways to use the same method:
- **Prompt templates** for ChatGPT conversations.
- **Modular Agent Skills** for compatible skill-based assistant environments.

## Start here

1. Open [SKILLS_INDEX.md](SKILLS_INDEX.md) to choose a modular skill, or [PROMPT_INDEX.md](PROMPT_INDEX.md) for copy-ready prompts.
2. Upload the student's own lecture slides, notes, tutorials, official revision papers and past exams.
3. For a full ChatGPT workflow, paste [prompts/01-master-exam-tutor.md](prompts/01-master-exam-tutor.md).
4. Type START and let the assistant inspect the actual course sources before teaching.

## Prompt library

- Course intake and syllabus mapping.
- Source audit and exact official-question extraction.
- Plain-language teaching and visual explanations.
- Batch practice, detailed marking and worked-problem coaching.
- Error diagnosis and remediation.
- Honest progress dashboards, mock exams and last-minute cram mode.
- Session continuation and adapting the workflow for another student.

## Agent Skills

The skills directory contains modular SKILL.md workflows for course intake, source-grounded auditing, concept teaching, visual explanation, batch practice, worked problems, error remediation, progress auditing, mock exams, cram mode and skill evaluation.

- [Browse all skills](SKILLS_INDEX.md)
- [Agent operating rules](AGENTS.md)
- [Claude instructions](CLAUDE.md)
- [Karpathy principles adaptation and attribution](references/karpathy-principles-adaptation.md)
- [Skill evaluation cases](evals/evals.json)

The project adapts four behavioural principles associated with the community project [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills): think before acting, simplicity first, surgical changes and goal-driven verification. Exam-OS applies them to learning and source handling. See the attribution note for context.

## What makes the workflow different

The system keeps four measures separate:
- **Taught:** an explanation was provided.
- **Understood:** the student demonstrated understanding in a check.
- **Attempted:** the student independently submitted an answer.
- **Correct:** the submitted answer was checked and correct.

Observed worked examples are not counted as independent attempts. Official questions remain verbatim; generated questions are labelled as generated. Course-specific content must be grounded in the student's own sources.

## Compatibility

Prompt templates can be pasted into ChatGPT. The modular skills use the public Agent Skills-style folder pattern with YAML frontmatter and Markdown instructions. They can be loaded by compatible skill-based environments. ChatGPT does not automatically load arbitrary GitHub skill folders; use the prompt templates or provide the relevant SKILL.md content.

## Adapt it for another student

Start a fresh conversation and a fresh progress tracker. Use only that student's course materials and preferences. See [Working with Another Student](guides/working-with-another-student.md).

## Important

Exam-OS is a prompt and instruction toolkit, not a software agent or a guarantee of exam results. Its usefulness depends on accurate source material, the assistant's capabilities and the student's independent practice.
