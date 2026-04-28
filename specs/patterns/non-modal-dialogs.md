# UI Pattern Spec (LLM-Friendly Template)

## 1. Pattern Name
Non-Modal Dialogs

---

## 2. Intent (Why this exists)
Non-modal dialog patterns are lightweight, contextual overlays used to present supporting information or optional actions without interrupting the user's workflow. They allow users to continue interacting with the underlying interface, providing flexibility and maintaining flow.

---

## 3. Context of Use
- Use when:
  - Contextual assistance is needed
  - Secondary actions are required
  - Guidance does not require full user attention
  - Additional information or controls are needed while continuing the primary task
- Avoid when:
  - High-risk or destructive actions are required
  - The interaction requires full user attention
  - The dialog would block interaction like a modal
  - The task is primary and requires focus

---

## 4. Core Behaviour (How it works)
- Trigger:
  - User interacts with a trigger element (e.g. button, icon, or content area)
- System Response:
  - A non-modal dialog appears positioned contextually relative to the trigger
  - The dialog presents supporting information or optional actions
- Ongoing Behavior:
  - User can continue interacting with the underlying interface
  - Dialog remains lightweight and context-specific
  - Dialog can remain open while the user continues their task
- Exit Condition:
  - User dismisses the dialog easily without disrupting workflow

---

## 5. Rules & Constraints
- MUST:
  - Allow users to continue interacting with the underlying interface
  - Keep content lightweight and context-specific
  - Position the dialog close to the triggering element
  - Allow easy dismissal
  - Maintain consistent styling and behaviour across patterns
  - Ensure the dialog does not obscure critical content
- SHOULD:
  - Use appropriate contextual styling (info for passive content, primary for transactional actions)
- MUST NOT:
  - Use for high-risk or destructive actions
  - Block interaction like a modal
  - Use incorrect or misleading styling
  - Overload with complex or unrelated content
  - Place far from relevant context
  - Make difficult to close or persist unnecessarily
  - Use for primary tasks requiring full attention
  - Create inconsistent or unpredictable experiences
  - Cover important UI elements without user control

---

## 6. Variants
- Passive Non-Modal:
  - When informational or supportive content is needed → no required actions, neutral or informational styling
- Transactional Non-Modal:
  - When users can take action within the dialog → higher emphasis, supports interaction and engagement

---

## 7. Examples (Abstract, not visual)
- User hovers over a feature icon
- System shows a passive non-modal dialog with guidance text
- User continues interacting with the interface without interruption

- User clicks “Add item”
- System shows a transactional non-modal dialog with action buttons
- User performs action without leaving the current workflow

---

## 8. Rationale (Why it works)
- Maintains user workflow without interruption
- Provides flexibility and continuous interaction
- Reduces disruption while offering contextual support

---

## 9. Trade-offs
- Pros:
  - Allows continuous interaction
  - Provides contextual support without interruption
- Cons:
  - Not suitable for high-risk actions
  - Can obscure content if not positioned correctly

---

## 10. Related Components
- Dialog

---

## 11. Related Patterns
- Modal Dialogs
- Tooltips
- Inline Overlays
