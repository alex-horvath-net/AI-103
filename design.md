# Quiz Structure and Placement Audit

## Goal

Ensure every numbered topic has exactly one `#### Quize` section, including topics with no questions.
Ensure each question is located under the topic whose learning objective it directly tests.

## Observed Defect

Section 2.1.2 has no standalone `<details>` container.
Its body and quiz are currently nested in section 2.1.1, which gives 2.1.1 two quiz sections and leaves 2.1.2 without one.

## Approach

1. Restore the missing 2.1.2 `<details>` and summary boundary around its existing RAG content and quiz.
2. Verify every numbered topic has exactly one quiz heading.
3. Review question content against its enclosing topic objective.
4. Move only questions whose primary tested objective clearly belongs to another topic.

## Acceptance Checks

- Every 3-level numbered topic has one `<details>` container and one `#### Quize` heading.
- Every `QA-` block remains present exactly once.
- Quiz question counts can be mapped to one unambiguous topic after the repair.

## QA Numbering

Renumber every `QA-` marker in document order, starting at `QA-001`.
The final sequence must have no duplicates or gaps.

## Section 2 Nesting

Remove the duplicate closing tag after section 2.1.2 so it cannot close parent section 2.1 before topics 2.1.3 through 2.1.6.
Section 2 must retain its 2.1, 2.2, and 2.3 child containers, and each child must contain all of its numbered topics.
