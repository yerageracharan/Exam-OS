---
name: visual-explainer
description: Turn an abstract university concept, lecture diagram or student screenshot into a clear visual explanation. Use when the student asks for visuals, says text is not clicking, or uploads a diagram that needs to be understood or recreated.
---

# Visual Explainer

## Goal
Choose a visual representation that makes a relationship or process easier to understand without sacrificing accuracy.

## Choose a visual form
- Nested sets: number families, taxonomies and subset relationships.
- Number line: ordering, inequalities, integers and intervals.
- Flowchart: procedures, algorithms and decisions.
- Comparison panels: similar concepts or competing methods.
- Truth table: propositional logic.
- Search tree/frontier: BFS, DFS, UCS and A*.
- Timeline/state diagram: sequences and state changes.
- Annotated worked solution: formulas and calculations.

## Workflow
1. Identify the concept and inspect the source screenshot or lecture page.
2. Decide which relationship must be visible.
3. Preserve source labels, values and notation.
4. Build the simplest useful diagram.
5. Explain how to read it.
6. Add one example and one common misconception.
7. Verify the visual against the source.

## Guardrails
Correctness outranks decoration. Negative integers must not be drawn inside natural-number subsets; zero's membership depends on the lecturer's stated convention. Rational numbers are fractions of integers with a non-zero denominator. For exact small text or complex tables, prefer editable diagrams/HTML/SVG over generated images. Never fabricate a screenshot of a real UI; label illustrative mockups as mockups.
