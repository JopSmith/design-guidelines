# UI Pattern Spec (LLM-Friendly Template)

## 1. Pattern Name
Social Media Interactions

---

## 2. Intent (Why this exists)
A Social media interactions pattern is a compact set of standardised actions presented alongside content or messages. It enables users to quickly engage with content through familiar actions such as liking, commenting, saving, or copying, without interrupting their flow.

---

## 3. Context of Use
- Use when:
  - In feeds where users are expected to frequently interact with items in lightweight ways
  - In messaging interfaces where users interact with messages
  - In content-driven interfaces where users react, explore conversations, or manage content
- Avoid when:
  - Not specified

---

## 4. Core Behaviour (How it works)
- Trigger: Content or message is displayed in a feed, chat, or content-driven interface
- System Response: A row of standardised interaction actions is presented alongside the content or message
- Ongoing Behavior:
  - Users select an interaction such as like, comment, save, or copy
  - System provides clear feedback for the interaction (e.g. liked state, message copied)
  - System updates counts or states immediately after interaction
- Exit Condition: Interaction is completed and feedback is shown

---

## 5. Rules & Constraints
- MUST:
  - Use familiar, widely recognised icons for common actions
  - Keep actions concise and limited to the most important interactions
  - Place interactions consistently in relation to content or messages
  - Provide clear feedback for interactions
  - Ensure actions are easy to tap or click
  - Prioritise frequently used actions in prominent positions
  - Place interactions close to the related content or message
  - Keep interactions in a consistent and predictable order
  - Update counts or states immediately after interaction
  - Use clear visual states for active and inactive interactions
  - Provide immediate feedback when a message is copied
- SHOULD:
  - Use subtle animations for certain interactions to enhance feedback without distracting from the content
- MUST NOT:
  - Introduce unclear or non-standard icons
  - Overload the pattern with too many actions
  - Move or vary placement between items
  - Leave users unsure if their action was successful
  - Use small or tightly spaced touch targets
  - Hide key actions behind additional interactions unnecessarily

---

## 6. Variants
- News Interactions: When used with posts or content in a news feed → includes actions such as Like, Comments, Save
- Chat Interactions: When used with messages in conversations → includes actions such as Copy

---

## 7. Examples (Abstract, not visual)
- User views a post in a news feed
- System shows Like, Comments, Save actions near the post
- User selects Like
- System updates liked state and count immediately

- User views a message in a chat
- System shows Copy action near the message
- User selects Copy
- System shows feedback that the message is copied

---

## 8. Rationale (Why it works)
- Enables quick interaction without interrupting user flow
- Uses familiar actions to reduce effort
- Provides immediate feedback to confirm user actions
- Keeps interactions consistent and predictable

---

## 9. Trade-offs
- Pros:
  - Quick and lightweight interactions
  - Minimal effort required from users
- Cons:
  - Limited to a small set of actions
  - Can become cluttered if too many actions are added

---

## 10. Related Components
- Icons
- Buttons

---

## 11. Related Patterns
- Not specified
