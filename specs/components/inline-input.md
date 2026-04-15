# InlineInput

## 1. Description

An InlineInput is a collection of related input fields arranged horizontally within a single row. It is intended for short inputs that are logically connected and usually completed together, such as first, middle, and last name, start and end dates, or minimum and maximum values like price or age ranges. InlineInput aligns labels, fields, and optional help text within one cohesive visual grouping, creating a compact and organised layout.

## 2. Usage

### When to Use

Use an InlineInput when multiple brief fields form part of a single concept and benefit from being understood together. It is particularly effective in structured forms where reducing vertical length improves flow and scannability, while still maintaining clarity and logical grouping.

### Do
- Use an InlineInput for short, closely related fields that form a single concept
- Keep the number of fields manageable to maintain clarity, ideally 2–3
- Ensure each field has a clear label or accessible description
- Maintain consistent spacing and alignment across the grouped inputs
- Use InlineInput to reduce unnecessary vertical form length
- Ensure the layout adapts responsively on smaller screens
- Use consistent widths for similar inputs, e.g. both date fields the same width
- Show one shared help message below the group if needed
- Show individual validation messages stacked below the group if needed

### Don't
- Group unrelated inputs on the same row
- Overcrowd the row with too many inputs
- Rely solely on visual proximity to communicate meaning
- Allow uneven widths or misalignment to reduce readability
- Prioritise compactness over usability or clarity
- Force horizontal layouts that break or become cramped on narrow viewports
- Let widths vary wildly, creating visual imbalance
- Repeat the same help message under every single field
- Show one shared validation message below the group when individual messages are needed

## 3. Composition

The InlineInput consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Help | Optional | Allows optional helper or validation text to be displayed |

## 4. States

**Status:** Not documented in source material
