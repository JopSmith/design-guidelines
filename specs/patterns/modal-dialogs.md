# UI Pattern Spec (LLM-Friendly Template)

## 1. Pattern Name
Modal Dialogs

---

## 2. Intent (Why this exists)
Modal dialog patterns are focused overlays that interrupt the user's current workflow to present important information, confirm actions, or guide users through tasks. They block interaction with the underlying interface, ensuring user attention is directed toward a specific purpose.

---

## 3. Context of Use
- Use when:
  - User focus is required to complete a task
  - User must acknowledge important information
  - User must confirm an action
  - Critical moments such as confirmations, form entry, or multi-step flows
  - Interruption is necessary to maintain clarity and prevent errors
- Avoid when:
  - Non-critical or passive information is being shown
  - There is no clear context or intent
  - Interruption is not necessary
  - Overuse would disrupt user flow

---

## 4. Core Behaviour (How it works)
- Trigger:
  - A condition requiring user attention occurs (e.g. confirmation, form completion, important message)
- System Response:
  - Display modal dialog overlay
  - Block interaction with underlying interface
  - Apply contextual styling based on intent (e.g. warning, error, success)
- Ongoing Behavior:
  - User interacts within the modal only
  - Content remains concise and focused
  - Actions guide user to complete or dismiss the task
  - Behaviour varies depending on modal type:
    - Passive: user dismisses
    - Transactional: user confirms or cancels
    - Acknowledgement: user accepts
    - Progress: user navigates steps
- Exit Condition:
  - User completes required action or dismisses modal
  - Modal closes and returns user to main interface

---

## 5. Rules & Constraints
- MUST:
  - Use modal dialogs for important, focused tasks such as confirming actions or completing forms
  - Ensure every modal has a clear and specific purpose
  - Use appropriate contextual styling to match message intent (e.g. warning, error, success)
  - Keep content concise and focused on the task
  - Provide clear primary and secondary actions
  - Keep modal messages short and clear — 2–3 short sentences maximum
  - Allow users to easily dismiss or cancel the modal
  - Use modals sparingly to avoid disrupting flow
  - Keep interaction within the modal until the task is complete
  - Maintain consistent structure and behaviour across modals
- SHOULD:
  - None
- MUST NOT:
  - Use modal dialogs for non-critical or passive information
  - Show modals without context or intent
  - Use incorrect or neutral styling that misrepresents the message severity
  - Overload the dialog with long or irrelevant content
  - Use vague or ambiguous action labels
  - Overload modals with excessive information
  - Trap users without a clear way to exit
  - Overuse modals, causing unnecessary interruptions
  - Allow background interaction while the modal is open
  - Create inconsistent or unpredictable modal experiences

---

## 6. Variants
- Passive Modal: When presenting important non-interactive information → user dismisses modal manually
- Transactional Modal: When user must confirm or cancel a significant change → requires explicit confirmation before closing
- Acknowledgement Modal: When user must acknowledge important information → closes immediately when accepted
- Progress Modal: When guiding users through multiple steps → tracks progression and allows navigation between steps

---

## 7. Examples (Abstract, not visual)
- Passive Modal:
  - System shows message: "System maintenance completed"
  - User reads message
  - User clicks Close
- Transactional Modal:
  - System asks: "Confirm billing information update"
  - Shows details (company name, address, payment method)
  - User selects Cancel or Update
- Acknowledgement Modal:
  - System shows: "Important security update"
  - User clicks Accept
  - Modal closes immediately
- Progress Modal:
  - System shows steps: Personal, Credentials, Preferences, Review
  - User navigates Next, Previous, or Cancel
  - Process completes on final step

---

## 8. Rationale (Why it works)
- Blocks background interaction to ensure user focus
- Reduces risk of user error during critical actions
- Provides clear decision points
- Supports structured workflows for complex tasks
- Ensures important information is acknowledged before proceeding

---

## 9. Trade-offs
- Pros:
  - Ensures user attention on critical tasks
  - Prevents errors during important actions
  - Supports structured and guided workflows
- Cons:
  - Can disrupt user flow if overused
  - Can feel intrusive
  - Overuse leads to unnecessary interruptions

---

## 10. Related Components
- Dialog component
- Button

---

## 11. Related Patterns
- Form Validation
- Error Messaging
- Progressive Disclosure
