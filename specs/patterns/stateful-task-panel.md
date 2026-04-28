# Stateful Task Panel

## 1. Intent (Why this exists)

Tracks progress across multi-step tasks. Provides structure within
conversational workflows.

## 2. Context of Use

-   Use when:
    -   Tasks span multiple steps
-   Avoid when:
    -   Interaction is simple

## 3. Core Behaviour (How it works)

-   Trigger:
    -   Multi-step task begins
-   System Response:
    -   Display panel with task state
-   Ongoing Behaviour:
    -   Update progress and inputs
-   Exit Condition:
    -   Task is completed

## 4. Rules & Constraints

-   MUST:
    -   Maintain task state
-   SHOULD:
    -   Show progress clearly
-   MUST NOT:
    -   Lose intermediate data

## 5. Variants

-   Variant A: Linear Task Panel
-   Variant B: Non-linear Task Panel

## 6. Examples (Abstract, not visual)

-   User starts booking flow
-   System shows steps
-   User completes steps
-   System completes task

## 7. Rationale (Why it works)

-   Adds structure
-   Improves task completion

## 8. Trade-offs

-   Pros:
    -   Clear workflow
-   Cons:
    -   Less flexible

## 9. Related Components

-   TBC

## 10. Related Patterns

-   TBC