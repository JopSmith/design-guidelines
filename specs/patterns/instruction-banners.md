# Instruction Banners

## 1. Intent (Why this exists)

Communicates system capabilities, roles, or constraints. Helps users
understand what the system can and cannot do.

## 2. Context of Use

-   Use when:
    -   System capabilities change dynamically
    -   Users need guidance about system behavior
-   Avoid when:
    -   Information is static and already known

## 3. Core Behaviour (How it works)

-   Trigger:
    -   System state changes or session starts
-   System Response:
    -   Display banner with relevant information
-   Ongoing Behaviour:
    -   Update banner when state changes
-   Exit Condition:
    -   User dismisses banner
    -   OR context changes

## 4. Rules & Constraints

-   MUST:
    -   Display accurate and current information
-   SHOULD:
    -   Keep content concise
-   MUST NOT:
    -   Show outdated or irrelevant instructions

## 5. Variants

-   Variant A: Persistent Banner
-   Variant B: Dismissible Banner

## 6. Examples (Abstract, not visual)

-   System enables browsing
-   System shows banner "Browsing enabled"
-   User continues interaction

## 7. Rationale (Why it works)

-   Sets expectations
-   Reduces confusion

## 8. Trade-offs

-   Pros:
    -   Improves clarity
-   Cons:
    -   Can be ignored

## 9. Related Components

-   TBC

## 10. Related Patterns

-   TBC