# RadioButton

## 1. Description

A RadioButton component is a form control that allows users to select a single option from a set of mutually exclusive choices. Within a group, only one radio button can be selected at any time, ensuring that the user makes a clear and deliberate choice. Unlike checkboxes, which allow multiple selections, radio buttons enforce a single selection across the group.

## 2. Usage

### When to Use

Use a RadioButton when presenting a short list of options where only one selection is valid. They are ideal for clear multiple-choice inputs in forms, settings, or configuration panels where all available options should be visible at once and the user must choose just one.

### Do
- Use when there are 5 or fewer options
- Group related options together in a Fieldset with a legend
- Provide clear and concise labels for each option
- Use segmented controls for view toggles
- Use Checkboxes when multiple selections are allowed
- Consider whether a default selection is appropriate based on context — it is acceptable to have no default selection when neutrality or deliberate choice is important
- Arrange options in a logical order such as most common first or alphabetical
- Ensure the entire label is clickable for better accessibility
- Use vertical alignment for better scanning and readability

### Don't
- Use for long lists — use a Select instead
- Present radio buttons without context or grouping
- Use vague or redundant labels
- Use standard radio buttons for view toggles
- Use radio buttons when users need to pick more than one option
- Force a default selection when the user should make an explicit choice
- Preselect an option that could bias or mislead the user
- Present options in a random or inconsistent order
- Make only the small control clickable
- Align options horizontally

## 3. Composition

**Status:** Not documented in source material

## 4. States

**Status:** Not documented in source material
