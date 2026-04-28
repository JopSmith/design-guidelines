# Mode Switcher

## 1. Intent (Why this exists)

Allows users to change system behaviour or role. Adapts responses to
different use cases.

## 2. Context of Use

-   Use when:
    -   Multiple roles are supported
-   Avoid when:
    -   System has single fixed behaviour

## 3. Core Behaviour (How it works)

-   Trigger:
    -   User selects mode
-   System Response:
    -   Update system behaviour
-   Ongoing Behaviour:
    -   Apply mode to responses
-   Exit Condition:
    -   User changes mode

## 4. Rules & Constraints

-   MUST:
    -   Apply selected mode consistently
-   SHOULD:
    -   Indicate current mode
-   MUST NOT:
    -   Mix behaviours across modes

## 5. Variants

-   Variant A: Explicit Selector
-   Variant B: Contextual Mode

## 6. Examples (Abstract, not visual)

-   User selects "Tutor"
-   System responds in tutor style

## 7. Rationale (Why it works)

-   Increases flexibility
-   Improves relevance

## 8. Trade-offs

-   Pros:
    -   Customization
-   Cons:
    -   Added complexity

## 9. Related Components

-   TBC

## 10. Related Patterns

-   TBC