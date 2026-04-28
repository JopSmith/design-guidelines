# Contextual Indicators

## 1. Intent (Why this exists)

Displays system actions when external tools are used. Provides
transparency during processing.

## 2. Context of Use

-   Use when:
    -   System relies on external tools
-   Avoid when:
    -   No background processing occurs

## 3. Core Behaviour (How it works)

-   Trigger:
    -   System initiates tool usage
-   System Response:
    -   Display status indicator
-   Ongoing Behaviour:
    -   Update status while tool runs
-   Exit Condition:
    -   Tool completes

## 4. Rules & Constraints

-   MUST:
    -   Indicate active processing
    -   Reflect current state accurately
-   SHOULD:
    -   Keep status concise
-   MUST NOT:
    -   Misrepresent system state

## 5. Variants

-   Variant A: Inline Status
-   Variant B: Separate Status Block

## 6. Examples (Abstract, not visual)

-   System starts search
-   System shows "Searching"
-   System completes and shows result

## 7. Rationale (Why it works)

-   Builds trust
-   Explains delays

## 8. Trade-offs

-   Pros:
    -   Transparency
-   Cons:
    -   Adds UI elements

## 9. Related Components

-   TBC

## 10. Related Patterns

-   TBC