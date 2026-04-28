# Conversation Branching

## 1. Intent (Why this exists)

Allows users to explore alternative conversation paths. Maintains the
original conversation while supporting divergence.

## 2. Context of Use

-   Use when:
    -   Users need to revisit or explore alternatives
    -   Conversations are exploratory or iterative
-   Avoid when:
    -   Interaction is strictly linear

## 3. Core Behaviour (How it works)

-   Trigger:
    -   User selects previous message or response
-   System Response:
    -   Create a new branch from selected point
-   Ongoing Behaviour:
    -   Maintain separate paths
    -   Allow switching between branches
-   Exit Condition:
    -   User returns to main thread or leaves conversation

## 4. Rules & Constraints

-   MUST:
    -   Preserve original conversation
    -   Clearly separate branches
-   SHOULD:
    -   Allow easy navigation between branches
-   MUST NOT:
    -   Merge branches without user action

## 5. Variants

-   Variant A: Forked Threads
-   Variant B: Version History

## 6. Examples (Abstract, not visual)

-   User selects past message
-   System creates new branch
-   User continues conversation in branch

## 7. Rationale (Why it works)

-   Supports exploration
-   Prevents loss of context

## 8. Trade-offs

-   Pros:
    -   Flexible interaction
-   Cons:
    -   Increased complexity

## 9. Related Components

-   TBC

## 10. Related Patterns

-   TBC