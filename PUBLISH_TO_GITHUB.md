# Repository Setup Notes

This project is stored in the Exam-OS repository.

## Repository layout

- prompts/ — copy-ready prompt templates.
- guides/ — adaptation, quality control and student handoff guidance.
- examples/ — anonymised workflow and command sequence.
- PROMPT_INDEX.md — catalogue and suggested order.

## Local development

Clone the repository:

~~~bash
git clone https://github.com/yerageracharan/Exam-OS.git
cd Exam-OS
~~~

Edit prompt files, update the prompt index when adding templates, and commit changes with a descriptive message.

## Contributing a new prompt

1. Add a Markdown file under prompts/.
2. Include a one-line “Use” description.
3. Make placeholders explicit with square brackets.
4. Preserve source-grounding and progress-accounting safeguards.
5. Add the new prompt to PROMPT_INDEX.md.
6. Test the prompt on a small sample conversation and check that it does not encourage fabricated source claims or progress numbers.
