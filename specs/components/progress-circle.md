# ProgressCircle

## 1. Description

A ProgressCircle visually represents task completion status using a circular indicator. It displays progress as a partially filled ring, giving users an immediate understanding of how much of a process has been completed and how much remains. The component can display a percentage complete or indicate steps completed within a defined sequence, providing clear and concise feedback in a compact format.

## 2. Usage

### When to Use

Use a ProgressCircle when space is limited or when a compact visual summary of progress is required, such as in mobile layouts or within cards and dashboards. It is particularly suitable when you want to convey overall completion or step-based progress at a glance without relying solely on detailed textual feedback.

### Do
- Use to show determinate progress for time-bound or measurable tasks
- Use when space is limited or vertical layouts make a linear bar unsuitable
- Pair with a concise percentage or centred label for clarity
- Use consistent sizing across a view to maintain visual balance
- Ensure the progress value reflects real system state
- Keep the design simple and focused

### Don't
- Use when task duration is unknown — use a spinner or loader instead
- Use for large-scale dashboards where a linear bar offers clearer readability
- Display multiple progress circles together without clear labels
- Mix different sizes or stroke thicknesses arbitrarily
- Display misleading or inaccurate completion states
- Overload the circle with excessive text or decorative elements

## 3. Composition

The ProgressCircle consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Titles | Optional | Allows a title and subtitle to be displayed alongside to indicate the name of the step |

## 4. States

**Status:** Not documented in source material
