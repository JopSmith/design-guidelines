# Quick Reply Chips

## 1. Intent (Why this exists)

Provides predefined, tappable options to guide user input. Reduces
decision effort and increases likelihood of valid, structured responses.

## 2. Context of Use

-   Use when:
    -   The system expects a limited set of valid responses
    -   The flow benefits from guided choices (e.g., onboarding,
        decision trees)
    -   Users may be unsure what to type next
-   Avoid when:
    -   Input is open-ended or exploratory
    -   The number of options is large or unbounded

## 3. Core Behaviour (How it works)

-   Trigger:
    -   System sends a message that expects a response
-   System Response:
    -   Render a set of selectable chips associated with the message
-   Ongoing Behaviour:
    -   Chips remain visible until user selects one or context changes
    -   Selecting a chip sends its value as the user message
    -   Append resulting user message to the chat stream
-   Exit Condition:
    -   User selects a chip
    -   OR chips are removed due to context change or timeout

## 4. Rules & Constraints

-   MUST:
    -   Present only valid, actionable options
    -   Send the exact chip value as the user message on selection
    -   Place chips contextually near the triggering message
    -   Remove or disable chips after selection
-   SHOULD:
    -   Limit number of chips to avoid overload
    -   Use concise, clear labels
    -   Maintain consistent ordering for similar contexts
-   MUST NOT:
    -   Present options that the system cannot handle
    -   Persist outdated chips after context changes
    -   Require typing when a chip fully answers the prompt

## 5. Variants

-   Variant A: Single-Select Chips
    -   When only one response is allowed
    -   Behaviour allows one selection and then removes chips
-   Variant B: Multi-Select Chips
    -   When multiple responses are allowed
    -   Behaviour allows multiple selections before submission

## 6. Examples (Abstract, not visual)

-   System asks a yes/no question
-   System shows chips: Yes, No
-   User selects Yes
-   System sends "Yes" as user message and removes chips
-   System asks for preferences
-   System shows multiple selectable chips
-   User selects multiple options
-   System submits selected values

## 7. Rationale (Why it works)

-   Reduces cognitive load by limiting choices
-   Increases response accuracy
-   Speeds up interaction
-   Guides users through structured flows

## 8. Trade-offs

-   Pros:
    -   Faster input
    -   Lower error rate
    -   Clear guidance
-   Cons:
    -   Limits flexibility
    -   Can clutter interface if overused
    -   May not cover all user intents

## 9. Related Components

-   TBC

## 10. Related Patterns

-   TBC