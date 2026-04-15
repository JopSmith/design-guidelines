# Non-Modal Dialogs

## 1. Description

Non-modal dialog patterns are lightweight, contextual overlays used to present supporting information or optional actions without interrupting the user's workflow. They allow users to continue interacting with the underlying interface, providing flexibility and maintaining flow.

## 2. Usage

Use non-modal dialogs for contextual assistance, secondary actions, or guidance that does not require full user attention. They are well suited for tooltips, side panels, or inline overlays where users may need additional information or controls while continuing their primary task.

### Do

- Use non-modal dialogs for supplementary or non-critical interactions
- Allow users to continue interacting with the underlying interface
- Use appropriate contextual styling (e.g. info for passive content, primary for transactional actions)
- Keep content lightweight and context-specific
- Position the dialog close to the triggering element
- Allow easy dismissal without disrupting the workflow
- Use non-modals for guidance, hints, or secondary actions
- Maintain consistent styling and behaviour across patterns
- Ensure the dialog does not obscure critical content

### Don't

- Use non-modal dialogs for high-risk or destructive actions
- Block interaction with the page like a modal
- Use incorrect or misleading styling that does not match intent
- Overload the dialog with complex or unrelated content
- Place it far from the relevant context
- Make it difficult to close or persist unnecessarily
- Use them for primary tasks that require full attention
- Create inconsistent or unpredictable experiences
- Cover important UI elements without user control

## 3. Types

Non-modal dialogs use the Dialog component base structure, positioned contextually relative to a trigger, e.g. button, icon, or content area.

### 3.1 Passive Non-Modal

Passive non-modal dialogs are used to present informational or supportive content that does not require immediate action. They provide context, guidance, or feedback while allowing users to continue their task uninterrupted. These dialogs are typically low emphasis and use neutral or informational styling.

| Element | Specification |
|---------|---------------|
| **Purpose** | Provides additional information relevant to the user's current workflow. Contains no required actions. |
| **Context** | Info |
| **Title** | Optional short title describing the context (e.g., "About this feature") |
| **Message** | Concise supporting text explaining a function or state. |
| **Actions** | Single Close button (Info context). |
| **Tone** | Neutral, helpful, and non-disruptive. |
| **Behaviour** | Can remain open until closed by the user. Does not block or obscure important interface elements. |
| **Use case** | Inline help messages, feature guidance, contextual explanations, or status notes. |

### 3.2 Transactional Non-Modal

Transactional non-modal dialogs are used when users can take action directly within the dialog, such as confirming a choice, making a selection, or triggering a process. While still non-blocking, they carry more intent and are styled with higher emphasis to signal interactivity and encourage engagement.

| Element | Specification |
|---------|---------------|
| **Purpose** | Offers optional, repeatable actions without interrupting workflow. Allows users to perform a contextual task inline. |
| **Context** | Primary |
| **Title** | "Add or modify item" (contextual to the action) |
| **Message** | Short explanatory text describing the available action. |
| **Actions** | Two buttons:<br>• Cancel (Outline)<br>• Primary Action (Primary) |
| **Tone** | Supportive and instructional. |
| **Behaviour** | Users can repeat actions without closing the dialog. Can remain open as long as relevant. |
| **Use case** | Adding items, tagging records, editing contextual data, applying filters, or previewing content. |
