# Button

## 1. Description

A Button is an interactive element used to trigger actions within an application. It communicates intent through its label, colour, size, and state, and may include an icon to provide additional context or reinforce meaning.

## 2. Usage

### When to Use

Use buttons to initiate actions such as submitting forms or performing contextual operations like adding, editing, deleting, or dismissing content. Always choose the correct colour and style to match the action's intent and priority.

### Do
- Use buttons to initiate or confirm actions, such as submitting a form, saving changes, or performing a task
- Use the appropriate severity based on the context of the action:
  - **Primary (Blue)** — for the main action on the screen
  - **Secondary (Gray or Outlined)** — for supporting actions that complement the primary action
  - **Success (Green)** — for positive actions to reinforce constructive intent
  - **Danger (Red)** — for negative or destructive actions to clearly signal risk
  - **Warning (Yellow)** — for cautionary actions that may lead to unintended outcomes
  - **Info (Teal)** — for neutral or informational actions
- Use the appropriate button style based on importance/prominence:
  - **Solid** — fully filled background; most prominent appearance
  - **Soft** — semi-transparent or light fill; used for mid-level visual emphasis
  - **Outlined** — transparent fill with border; used for secondary or supporting actions
  - **Text** — no border or background; very minimal; used for subtle or tertiary actions
- Include clear, concise (1 or 2 words), action-oriented labels (e.g. Add, Save, Delete, Next, Edit, Confirm)
- Order buttons from most positive to most negative, right to left, with the cancel/close button last — for example: `Cancel` | `Secondary Action` | `Primary Action`
- Use close and cancel buttons correctly:
  - **Close** — dismisses dialogs, drawers, or screens without performing an action
  - **Cancel** — discards changes in active forms and returns to previous state
- Use icon-only buttons when space is limited or the icon is universally recognised
- Use icons on primary buttons to enhance recognition
- Show disabled buttons only when users can take an action to enable them
- Use medium-sized buttons by default; use small buttons only in compact contexts like tables

### Don't
- Use buttons for navigation, toggling states, or selecting options
- Use button severities inconsistently or out of context
- Use button styles interchangeably without regard to hierarchy
- Use vague or generic labels like "OK", "Yes", or "Submit"
- Arrange buttons in a random or inconsistent order
- Use close and cancel buttons interchangeably
- Use icon-only buttons for unfamiliar or complex actions
- Use icons on secondary or tertiary buttons unnecessarily
- Display permanently disabled buttons with no way to activate them
- Mix button sizes inconsistently

## 3. Composition

The Button consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Label | Mandatory | Displays the intent of a button. Excluded when icon-only |
| Leading icon | Optional | Allows placement of an icon at the start of a button |
| Trailing icon | Optional | Allows placement of an icon at the end of a button |
| Icon-only | Optional | Displays only an icon without a text label, used for common or universally recognised actions where space is limited |

## 4. States

**Status:** Not documented in source material
