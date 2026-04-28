# Typing Indicator

## 1. Intent (Why this exists)
Signals that the system is actively generating a response. Reduces perceived waiting time and keeps the user engaged during delays.

## 2. Context of Use
- Use when:
  - System response takes noticeable time to generate
  - Output can be delivered incrementally
  - User needs feedback that system is active
- Avoid when:
  - Responses are instant
  - No delay or processing time exists

## 3. Core Behaviour (How it works)
- Trigger:
  - System receives user input
  - OR system begins processing a response
- System Response:
  - Display typing indicator OR start streaming output
- Ongoing Behaviour:
  - Update indicator while processing continues
  - OR progressively render response content in a single message bubble
  - Maintain position at end of chat stream
- Exit Condition:
  - Full response is generated
  - Replace typing indicator with final message OR complete streamed message

## 4. Rules & Constraints
- MUST:
  - Show clear indication that system is active
  - Transition smoothly from indicator to final output
  - Keep indicator aligned with system message position
- SHOULD:
  - Use streaming when responses are long
  - Maintain consistent behaviour across interactions
- MUST NOT:
  - Leave indicator visible after completion
  - Show indicator without actual processing
  - Create multiple message bubbles for a single streamed response

## 5. Variants
- Variant A: When streaming is not supported → Behaviour shows temporary indicator before full response appears
- Variant B: When incremental output is supported → Behaviour updates a single message progressively until complete

## 6. Examples (Abstract, not visual)
- User submits message
- System shows typing indicator
- System replaces indicator with full response
- User submits message
- System begins streaming response
- System updates one message progressively until complete

## 7. Rationale (Why it works)
- Reduces perceived latency
- Provides continuous feedback
- Keeps user engaged during processing
- Aligns with real-time interaction expectations

## 8. Trade-offs
- Pros:
  - Improves perceived performance
  - Increases transparency
- Cons:
  - Can feel slow if overused
  - Streaming may expose partial or unrefined output

## 9. Related Components
- TBC

## 10. Related Patterns
- TBC