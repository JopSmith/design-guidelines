# ToggleButton

## 1. Description

A ToggleButton component is a button-style control used to switch between two states, typically on and off. It presents clear visual labels to indicate the current state and provides immediate feedback when toggled. Unlike a simple switch, a ToggleButton often uses descriptive text within the button itself so that the active state is immediately obvious.

## 2. Usage

### When to Use

Use a ToggleButton for settings or features that require a clear binary choice and where the state needs to be highly visible, such as enabling modes, filters, or feature flags. It is particularly useful when context benefits from explicit labels rather than a minimal switch control. Avoid using it for multi-option selections or where the distinction between states is unclear.

### Do
- Use ToggleButton for feature toggles such as on/off controls for application features or settings, e.g. mute/unmute
- Use for state switching where the current state should be visually clear
- Use for preference settings that toggle between two options
- Use for mode switching between two distinct modes or states
- Use for agreement toggles such as accept/decline in forms
- Ensure the current state is clearly visible with strong visual contrast and clear labels
- Use clear, descriptive labels within the button

### Don't
- Use ToggleButton for triggering one-time actions — use a regular Button instead
- Use for navigation — use appropriate navigation components instead
- Use for more than 2 choices — use RadioButton or Select instead
- Use as a replacement for a simple Checkbox where a basic checked/unchecked state is sufficient
- Use for destructive or irreversible changes without confirmation
- Make both states visually similar or rely only on subtle colour differences
- Use ambiguous labels such as "Active" or "Enabled" without context

## 3. Composition

The ToggleButton consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Icon | Optional | An optional icon displayed alongside the label to reinforce meaning and improve recognition of the toggle state. Icons should support, not replace, clear text labels and must not be the sole indicator of state |

## 4. States

**Status:** Not documented in source material
