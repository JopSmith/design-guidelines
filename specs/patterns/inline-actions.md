# Inline Actions

## 1. Intent (Why this exists)

Provides controls attached to individual messages. Enables users to
interact with outputs without modifying the conversation flow.

## 2. Context of Use

-   Use when:
    -   Users need to act on specific messages
    -   Outputs support secondary actions (copy, edit, regenerate)
-   Avoid when:
    -   No per-message actions are required

## 3. Core Behaviour (How it works)

-   Trigger:
    -   Message is rendered
-   System Response:
    -   Attach available actions to the message
-   Ongoing Behaviour:
    -   Show actions on hover or focus
    -   Execute action when selected
-   Exit Condition:
    -   Action completes or user moves away

## 4. Rules & Constraints

-   MUST:
    -   Attach actions to correct message
    -   Ensure actions map to valid operations
-   SHOULD:
    -   Keep actions secondary to content
-   MUST NOT:
    -   Obscure message content

## 5. Variants

-   Variant A: Always Visible Actions
-   Variant B: Hover-Only Actions

## 6. Examples (Abstract, not visual)

-   System displays message
-   User selects copy
-   System copies content

## 7. Rationale (Why it works)

-   Keeps interaction localized
-   Reduces need for global controls

## 8. Trade-offs

-   Pros:
    -   Efficient actions
-   Cons:
    -   Can add clutter

## 9. Related Components

-   TBC

## 10. Related Patterns

-   TBC