# StatusButton

## 1. Description

A StatusButton component combines a standard action button with a visible status indicator or dropdown affordance. It communicates both an actionable state such as Start, Stop, Approve, or Open, and the current status of a process or item such as Active, Pending, or Completed.

This allows users to understand the present state while also having a clear path to interact with or change it.

## 2. Usage

### When to Use

Use a StatusButton when users need to both see a status and take action from the same control. It is particularly useful in workflows, dashboards, or management interfaces where state and action are closely linked. Avoid using it when status is purely informational with no associated action, or when a simple button or badge would communicate the intent more clearly.

### Do
- Use to display a state and trigger a related action
- Use consistent colour associations with system status tokens such as blue for primary and green for success
- Include an icon that visually reinforces the state or action
- Use clear and concise verbs for the button label such as Open, Start, or Retry
- Maintain accessible colour contrast for all states

### Don't
- Use for purely informational badges — use a Chip or Tag instead
- Mix inconsistent colours that misrepresent meaning
- Use overly detailed or decorative icons that distract from the label
- Use ambiguous or passive text such as "It is done" or "Maybe"
- Rely solely on colour to convey meaning

## 3. Composition

**Status:** Not documented in source material

## 4. States

**Status:** Not documented in source material
