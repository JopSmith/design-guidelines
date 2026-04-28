# Follow-up Prompts

## 1. Intent (Why this exists)

Encourages continued interaction. Guides users toward next steps.

## 2. Context of Use

-   Use when:
    -   Next steps are unclear
    -   System can suggest actions
-   Avoid when:
    -   User intent is already clear

## 3. Core Behaviour (How it works)

-   Trigger:
    -   System completes response
-   System Response:
    -   Display follow-up suggestions
-   Ongoing Behaviour:
    -   Update suggestions based on context
-   Exit Condition:
    -   User selects option or continues

## 4. Rules & Constraints

-   MUST:
    -   Provide relevant suggestions
-   SHOULD:
    -   Limit number of prompts
-   MUST NOT:
    -   Interrupt user flow unnecessarily

## 5. Variants

-   Variant A: Inline Suggestions
-   Variant B: Separate Prompt Block

## 6. Examples (Abstract, not visual)

-   System answers question
-   Shows "Ask another question"
-   User selects prompt

## 7. Rationale (Why it works)

-   Maintains engagement
-   Guides interaction

## 8. Trade-offs

-   Pros:
    -   Increases usage
-   Cons:
    -   Can feel intrusive

## 9. Related Components

-   TBC

## 10. Related Patterns

-   TBC