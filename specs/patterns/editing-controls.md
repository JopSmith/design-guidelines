# Editing Controls

## 1. Intent (Why this exists)

Allows users to modify or retry interactions. Supports iterative
workflows and correction of errors.

## 2. Context of Use

-   Use when:
    -   Outputs may need refinement
    -   Users need control over previous inputs or results
-   Avoid when:
    -   Interaction is single-step with no iteration

## 3. Core Behaviour (How it works)

-   Trigger:
    -   User selects undo, edit, or regenerate action
-   System Response:
    -   Revert, modify, or regenerate content
-   Ongoing Behaviour:
    -   Update conversation with new state
-   Exit Condition:
    -   New result is finalized

## 4. Rules & Constraints

-   MUST:
    -   Preserve original context where needed
    -   Apply changes to correct message
-   SHOULD:
    -   Allow comparison between versions
-   MUST NOT:
    -   Lose user intent during modification

## 5. Variants

-   Variant A: Edit Input
-   Variant B: Regenerate Output

## 6. Examples (Abstract, not visual)

-   User edits message
-   System updates response

## 7. Rationale (Why it works)

-   Supports iteration
-   Reduces frustration

## 8. Trade-offs

-   Pros:
    -   Flexible interaction
-   Cons:
    -   Can create confusion if overused

## 9. Related Components

-   TBC

## 10. Related Patterns

-   TBC