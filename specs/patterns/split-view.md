# Split View

## 1. Intent (Why this exists)

Displays conversation and generated output simultaneously. Improves
usability for complex outputs.

## 2. Context of Use

-   Use when:
    -   Outputs require more space
-   Avoid when:
    -   Interaction is simple

## 3. Core Behaviour (How it works)

-   Trigger:
    -   System generates large output
-   System Response:
    -   Display output in separate panel
-   Ongoing Behaviour:
    -   Sync updates between panels
-   Exit Condition:
    -   User closes or navigates away

## 4. Rules & Constraints

-   MUST:
    -   Keep chat and output visible
-   SHOULD:
    -   Allow resizing panels
-   MUST NOT:
    -   Hide primary interaction

## 5. Variants

-   Variant A: Fixed Split
-   Variant B: Resizable Split

## 6. Examples (Abstract, not visual)

-   System generates document
-   Shows document beside chat

## 7. Rationale (Why it works)

-   Improves readability
-   Supports productivity tasks

## 8. Trade-offs

-   Pros:
    -   Efficient workflow
-   Cons:
    -   Requires more screen space

## 9. Related Components

-   TBC

## 10. Related Patterns

-   TBC