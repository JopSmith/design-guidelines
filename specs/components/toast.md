# Toast

## 1. Description

A Toast component is a lightweight notification that provides feedback after a system action has occurred. It appears as a temporary overlay, typically in the top right of the page, and fades in and out automatically. Toasts inform users that something has been completed or received, such as an approval, assignment, or update. They can include an icon, may contain a title and subtitle, can be dismissible or actionable, and are designed to be clear and concise without interrupting the user's workflow.

**Snackbar (solid Toast variant):** Toasts also have an alternate variant previously known as a Snackbar. This version provides immediate feedback after a user action has been performed and is typically used for soft messaging such as confirming deletion or updates. It is always placed at the bottom centre of the screen, uses a solid contextual background colour, shows one message at a time, contains a single line of text with no subtitle, and is used strictly for contextual feedback related to the current task.

Examples:
- Standard Toast: "A holiday request has been approved", "Your manager has assigned you a task"
- Snackbar: "The Dashlet has been removed", "The email has been deleted"

## 2. Usage

### When to Use

Use a **standard Toast** for background or system-generated activities that users should be informed about but that do not require immediate action, such as status changes, assignments, or updates happening outside the user's direct interaction.

Use the **Snackbar (solid variant)** for immediate feedback following a user-initiated action within the current task, such as confirming deletion, removal, or successful updates.

Neither variant should be used for critical or high-urgency information, which should instead use a Message/Alert pattern.

### Do
- Use standard Toasts for background or system-generated updates
- Use the solid Snackbar variant for immediate feedback after a user action
- Ensure Toasts fade in and out smoothly
- Keep messaging clear, concise, and contextual
- Include an icon where it reinforces meaning in standard Toasts
- Use a single line of text only for the Snackbar variant
- Allow standard Toasts to stack when necessary
- Ensure Toasts never obscure important content such as primary buttons
- Manage notifications through a notification centre where appropriate
- Use Toasts sparingly to maintain impact

### Don't
- Use Toasts for critical or high-urgency information
- Use the Snackbar variant for system events unrelated to the current task
- Display Toasts abruptly without transition
- Use vague, lengthy, or generic messaging
- Overload Toasts with excessive decorative elements
- Add subtitles or multiple lines to the Snackbar variant
- Show multiple Snackbar messages at the same time
- Position Toasts over critical interface elements
- Provide no way to review missed system Toasts
- Overuse Toasts so they lose meaning

## 3. Composition

The Toast consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Subtitle | Optional | An optional secondary line of text that provides additional context or detail about the notification. Used in standard Toasts only, not in the solid Snackbar variant |
| Action | Optional | An optional actionable element such as a button that allows users to respond directly to the notification, for example Undo or View. Actions should be relevant and lightweight |

## 4. States

**Status:** Not documented in source material
