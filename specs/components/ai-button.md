# AIButton

## 1. Description

An AIButton is a clickable UI element used to trigger AI actions within an application. They communicate intent through a special combination of label, colour, size, and interaction state. They also include a specific icon for additional context.

## 2. Usage

### When to Use

Use an AIButton when you want to give users a clear, intentional way to initiate an AI-driven feature or workflow such as drafting feedback, summarising content, comparing documents, etc. It should be placed where the action feels timely and relevant, such as next to content it will affect or at a natural decision point in a task. AIButtons work best when there is a single, well-defined outcome, helping users understand what will happen when they interact with it and encouraging confident engagement with AI functionality.

### Do
- Include clear, action-oriented labels
- Apply hover, focus, and active states for better interaction UX
- Ensure icon alignment and spacing is consistent
- Use standard button label styling for visual consistency

### Don't
- Use vague labels like "OK" or "Submit" without context
- Forget to define states like disabled or focused
- Add both leading and trailing icons without visual balance
- Mix different font sizes across buttons

## 3. Composition

The AIButton consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Label | Optional | Displays the intent of a button |
| Leading icon | Optional | Allows placement of an icon at the start of a button |
| Trailing icon | Optional | Allows placement of an icon at the end of a button |
| Icon-only | Optional | Displays only an icon without a text label, used for common or universally recognised actions where space is limited |

## 4. States

**Status:** Not documented in source material
