# Message Bubbles

## 1. Intent (Why this exists)

Provides a clear, chronological structure for a conversation between
user and system. Separates roles (user vs system) and maintains
readability over time.

## 2. Context of Use

-   Use when:
    -   The interface is conversation-based
    -   Messages are exchanged sequentially over time
    -   Both user and system produce content
-   Avoid when:
    -   Interaction is form-based or single-step
    -   No conversational back-and-forth exists

## 3. Core Behaviour (How it works)

-   Trigger:
    -   User submits a message
    -   OR system generates a response
-   System Response:
    -   Create a new message bubble
    -   Assign sender type (user or system)
    -   Append bubble to the end of the chat stream
-   Ongoing Behaviour:
    -   Maintain strict chronological order
    -   Visually distinguish sender types
    -   Group consecutive messages from same sender when applicable
    -   Allow vertical scrolling as messages increase
    -   Preserve previous messages unchanged
-   Exit Condition:
    -   Conversation ends
    -   OR user leaves the interface

## 4. Rules & Constraints

-   MUST:
    -   Display messages in chronological order (top older, bottom
        newer)
    -   Clearly differentiate user vs system messages
    -   Append new messages at the end of the stream
    -   Preserve message history within the session
    -   Ensure each message is visually contained as a discrete unit
-   SHOULD:
    -   Group consecutive messages from the same sender
    -   Support long-form content without breaking layout
    -   Maintain consistent spacing between messages
-   MUST NOT:
    -   Reorder past messages
    -   Merge messages from different senders
    -   Overwrite existing messages after rendering
    -   Hide messages without explicit user action

## 5. Variants

-   Variant A: Grouped Bubbles
    -   When multiple messages from same sender occur consecutively
    -   Behaviour changes to grouping messages together
-   Variant B: Streaming Bubble
    -   When system response is generated incrementally
    -   Behaviour changes to updating the same bubble progressively

## 6. Examples (Abstract, not visual)

-   User submits message
-   System appends user bubble
-   System generates response
-   System appends system bubble
-   User sends multiple short messages
-   System groups consecutive user messages
-   System streams response
-   System updates one bubble until complete

## 7. Rationale (Why it works)

-   Separates roles clearly
-   Preserves conversation context
-   Reduces cognitive load by chunking information
-   Aligns with familiar messaging mental models
-   Supports incremental interaction patterns

## 8. Trade-offs

-   Pros:
    -   Easy to understand
    -   Scales with conversation length
    -   Familiar interaction model
-   Cons:
    -   Can become long and hard to navigate
    -   Limited structure for complex data
    -   Repetition can reduce information density

## 9. Related Components

-   TBC

## 10. Related Patterns

-   TBC