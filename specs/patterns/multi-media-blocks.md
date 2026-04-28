# Multi-Media Blocks

## 1. Intent (Why this exists)

Supports non-text inputs and outputs within the conversation. Expands
interaction beyond text.

## 2. Context of Use

-   Use when:
    -   Images, audio, video, or files are relevant
-   Avoid when:
    -   Interaction is strictly text-based

## 3. Core Behaviour (How it works)

-   Trigger:
    -   User submits or system generates non-text content
-   System Response:
    -   Render content in appropriate format block
-   Ongoing Behaviour:
    -   Provide controls for viewing or playback
-   Exit Condition:
    -   User navigates away

## 4. Rules & Constraints

-   MUST:
    -   Clearly differentiate content types
    -   Provide appropriate viewers
-   SHOULD:
    -   Maintain consistent layout
-   MUST NOT:
    -   Render unsupported formats

## 5. Variants

-   Variant A: Input Block
-   Variant B: Output Block

## 6. Examples (Abstract, not visual)

-   User uploads image
-   System displays image preview

## 7. Rationale (Why it works)

-   Supports diverse content
-   Improves usability

## 8. Trade-offs

-   Pros:
    -   Flexible interaction
-   Cons:
    -   Increased complexity

## 9. Related Components

-   TBC

## 10. Related Patterns

-   TBC