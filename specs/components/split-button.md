# SplitButton

## 1. Description

A SplitButton component combines a primary action and a secondary menu trigger within a single joined control. The main labelled segment performs the most common or recommended action immediately, while the adjacent icon segment opens a menu of related alternative actions. This structure keeps the interface compact while clearly signalling that additional options are available.

## 2. Usage

### When to Use

Use a SplitButton when there is a clear default action that most users will take, but where related variations or secondary actions must also be accessible. It is particularly effective for repetitive or task-focused workflows where efficiency matters. Avoid using it when there is no obvious primary action, when options are unrelated, or when a simple button or standalone menu would provide clearer intent.

### Do
- Use a SplitButton when there is one clearly primary action and a small set of related secondary actions
- Use when speed matters such as Save with quick access to Save as draft or Save and share
- Keep the main label action verb-led and unambiguous
- Limit the dropdown menu to 3 to 6 meaningful alternatives
- Use consistent styling between the main and trigger segments so they read as one control
- Make the caret trigger clearly clickable and give it its own focus state
- Separate destructive or high-risk actions and require confirmation where appropriate

### Don't
- Use when actions are unrelated — users will assume the menu contains variations of the same task
- Use when there is only one possible action — use a normal button instead
- Use vague or overloaded labels such as "Go" or "More"
- Overcrowd the menu with too many options
- Visually style the two segments differently so they look like unrelated buttons
- Hide the caret affordance so users cannot see that more options are available
- Place destructive actions in the menu where they are easy to mis-tap without confirmation

## 3. Composition

**Status:** Not documented in source material

## 4. States

**Status:** Not documented in source material
