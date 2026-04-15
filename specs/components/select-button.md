# SelectButton

## 1. Description

A SelectButton component, also known as a SegmentedButton, is a group of horizontally arranged options presented as connected buttons within a single control. Each segment represents a mutually exclusive choice and behaves like a button with a selected or not-selected state. The group functions as one unified input, allowing users to switch quickly between options without opening a separate menu.

## 2. Usage

### When to Use

Use a SelectButton for view switching, quick filters, sort order, time ranges, or other mutually exclusive modes within a page or panel. It is particularly effective when there are a small number of options that benefit from being visible at all times and easily comparable. Avoid using it for long lists or complex selections where a Select or another form control would be more appropriate.

### Do
- Use SelectButtons when the number of available options is small and known such as Day, Week, or Month
- Use when users can switch instantly between views or modes with minimal friction
- Keep labels short, ideally 1 to 2 words
- Use icon-only segments where meaning is clear such as a List or Grid view switcher
- Support multi-select where the use case requires selecting more than one active state
- Visually highlight the selected segment clearly so users always know which mode they are in
- Use consistent segment sizing and spacing across the group
- Use SelectButtons inline with content such as filters above a table or a view toggle in a dashboard

### Don't
- Use SelectButtons for long option lists — use a Select or Dropdown instead
- Use when the action is destructive such as Delete or Reset
- Use long labels or multiline text inside segments
- Use unclear or ambiguous icons without supporting meaning
- Use multi-select when options are mutually exclusive
- Rely only on subtle colour differences to indicate the active item
- Mix icon-only segments and text-only segments in the same group unless it is intentional and documented
- Hide core navigation behind SelectButtons at a global or top-level app navigation scale

## 3. Composition

**Status:** Not documented in source material

## 4. States

**Status:** Not documented in source material
