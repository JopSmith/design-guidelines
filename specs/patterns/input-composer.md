# Input Composer

## 1. Intent (Why this exists)

Provides a message input area that supports multiple input types beyond
text. Enables users to submit text, voice, files, images, or commands
within a single interface.

## 2. Context of Use

-   Use when:
    -   Multiple input types improve task completion
    -   Users need to attach or create content
    -   Interaction requires flexibility in how input is provided
-   Avoid when:
    -   Input is strictly simple text
    -   Additional tools do not add value

## 3. Core Behaviour (How it works)

-   Trigger:
    -   User focuses or activates the input area
-   System Response:
    -   Display text input field and available input tools
-   Ongoing Behaviour:
    -   Allow switching between input types
    -   Show or hide tools based on context
    -   Maintain current input state
-   Exit Condition:
    -   User submits input
    -   OR user leaves the input area

## 4. Rules & Constraints

-   MUST:
    -   Support text input as default
    -   Provide access to additional input methods
    -   Ensure each input type maps to a valid system action
-   SHOULD:
    -   Adapt visible tools based on context
    -   Keep controls consistent across interactions
-   MUST NOT:
    -   Require use of non-text inputs
    -   Overload interface with all tools simultaneously

## 5. Variants

-   Variant A: Minimal Composer
    -   When only essential tools are shown
-   Variant B: Context-Aware Composer
    -   When tools change based on task or state

## 6. Examples (Abstract, not visual)

-   User focuses input
-   System shows text field and upload option
-   User attaches file
-   System includes file in message submission

## 7. Rationale (Why it works)

-   Supports different input needs
-   Reduces friction for complex tasks
-   Aligns with multi-modal interaction patterns

## 8. Trade-offs

-   Pros:
    -   Flexible input
    -   Supports multiple workflows
-   Cons:
    -   Increased complexity
    -   Higher cognitive load if poorly managed

## 9. Related Components

-   TBC

## 10. Related Patterns

-   TBC