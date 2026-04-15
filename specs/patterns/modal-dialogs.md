# Modal Dialogs

## 1. Description

Modal dialog patterns are focused overlays that interrupt the user's current workflow to present important information, confirm actions, or guide users through tasks. They block interaction with the underlying interface, ensuring user attention is directed toward a specific purpose.

## 2. Usage

Use modal dialogs when user focus is required to complete a task, acknowledge important information, or confirm an action. They are best suited for critical moments such as confirmations, form entry, or multi-step flows, and should only be used when interruption is necessary to maintain clarity and prevent errors.

### Do

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

### Don't

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

## 3. Types

Each variant uses the Dialog component base structure and adjusts content, context, and actions based on purpose.

### 3.1 Passive Modal

Passive modal dialogs are used to present important information that requires user acknowledgment before continuing, but does not involve taking a meaningful action. They interrupt the flow to ensure the message is seen, often for alerts, warnings, or critical updates, and typically require a simple dismissal.

| Element | Specification |
|---------|---------------|
| **Purpose** | Presents non-interactive information users need to be aware of concerning their workflow. |
| **Context** | Info |
| **Title** | "System maintenance completed" |
| **Message** | "Scheduled system maintenance has been successfully completed. Your system is now up-to-date and running smoothly." |
| **Actions** | Single Close button (Info context). |
| **Tone** | Neutral, reassuring, and concise. |
| **Behaviour** | User closes the dialog manually. No destructive or confirm actions are present. |
| **Use case** | Informational updates, background process notifications, completion summaries. |

### 3.2 Transactional Modal

Transactional modal dialogs are used when users must complete or confirm an action before proceeding, such as submitting a form, confirming a deletion, or completing a step in a process. They require deliberate interaction and are designed to guide users through a clear decision or task before returning to the main interface.

| Element | Specification |
|---------|---------------|
| **Purpose** | Requires the user to confirm or cancel a significant system or data change. |
| **Context** | Primary, Warning, or Danger |
| **Title** | "Confirm billing information update" |
| **Message** | "Are you sure you want to update your billing information? The following changes will take effect immediately, and your next invoice will reflect these details." |
| **Supporting details** | "Company Name: Bright Horizons Ltd"<br>"Billing Address: 45 Elmwood Avenue, Kensington, London SW7 3RT"<br>"Payment Method: Visa ending in 1234" |
| **Actions** | Two buttons:<br>• Cancel (Outline)<br>• Update (Primary) |
| **Tone** | Serious, clear, and instructional. |
| **Behaviour** | Requires explicit confirmation before closing. |
| **Use case** | Confirmations, approvals, data edits, or destructive actions. |

### 3.3 Acknowledgement Modal

| Element | Specification |
|---------|---------------|
| **Purpose** | Requires the user to acknowledge important information before continuing. |
| **Context** | Success |
| **Title** | "Important security update" |
| **Message** | "Our security protocols have been updated. Please review the changes to ensure compliance." |
| **Actions** | Single Accept button (Success context). Never use "OK". |
| **Tone** | Positive, informative, and professional. |
| **Behaviour** | Closes immediately when accepted. |
| **Use case** | Confirmation of completed updates, compliance acknowledgements, success notifications. |

### 3.4 Progress Modal

| Element | Specification |
|---------|---------------|
| **Purpose** | Guides users through multiple sequential steps within a process. |
| **Context** | Primary |
| **Title** | "Account setup" |
| **Message** | Includes step labels such as "Personal", "Credentials", "Preferences", and "Review". |
| **Actions** | Three buttons:<br>• Cancel (Outline)<br>• Previous (Outline)<br>• Next / Complete (Primary) |
| **Tone** | Supportive, sequential, and instructional. |
| **Behaviour** | Tracks step progression; users can navigate between steps and exit anytime via Cancel. |
| **Use case** | Onboarding flows, setup wizards, multi-step forms, and configuration processes. |
