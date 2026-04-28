# Inline Forms

## 1. Intent (Why this exists)

Collects precise input using structured fields. Reduces ambiguity
compared to free text.

## 2. Context of Use

-   Use when:
    -   Input requires specific format or constraints
    -   Accuracy is critical
-   Avoid when:
    -   Input is exploratory or open-ended

## 3. Core Behaviour (How it works)

-   Trigger:
    -   System requires structured input
-   System Response:
    -   Display form elements inline
-   Ongoing Behaviour:
    -   Validate inputs as user interacts
-   Exit Condition:
    -   User submits form

## 4. Rules & Constraints

-   MUST:
    -   Enforce input constraints
    -   Provide valid field types
-   SHOULD:
    -   Guide user with defaults or hints
-   MUST NOT:
    -   Accept invalid structured input

## 5. Variants

-   Variant A: Single Field Input
-   Variant B: Multi-Field Form

## 6. Examples (Abstract, not visual)

-   System asks for date
-   Displays date picker
-   User selects date
-   System accepts input

## 7. Rationale (Why it works)

-   Improves accuracy
-   Reduces ambiguity

## 8. Trade-offs

-   Pros:
    -   Reliable input
-   Cons:
    -   Less flexible

## 9. Related Components

-   TBC

## 10. Related Patterns

-   TBC