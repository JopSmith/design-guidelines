# Fieldset

## 1. Description

A Fieldset is a structural container used to group related form controls within a form. It visually and semantically connects inputs that belong together, often supported by a shared heading or label that describes the purpose of the group. A Fieldset improves clarity, accessibility, and organisation by helping users understand how different inputs are related.

## 2. Usage

### When to Use

Use a Fieldset when multiple form elements contribute to a single concept or decision, such as contact details, billing information, or preference settings. It is particularly useful in longer or more complex forms where grouping inputs reduces cognitive load and supports clearer navigation through the content.

### Do
- Use a Fieldset to group related form controls that belong to the same concept
- Provide a clear and descriptive label to explain the purpose of the group
- Use Fieldsets to improve structure in longer or more complex forms
- Ensure the visual grouping reflects the logical relationship of the inputs
- Maintain consistent spacing and alignment within the Fieldset
- Support accessibility by ensuring screen readers can interpret the grouping correctly

### Don't
- Group unrelated inputs within the same Fieldset
- Leave a Fieldset without a meaningful label
- Use a Fieldset for very short forms where grouping adds no value
- Rely solely on visual styling without semantic structure
- Create crowded or uneven layouts inside the group
- Break accessibility by removing proper semantic markup

## 3. Composition

The Fieldset consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Title (Mandatory) | Mandatory | Displays the name of the Fieldset |
| Subtitle | Optional | Appears below the title and used for secondary text |
| Expand/collapse | Optional | Used for optional or advanced sections that can be shown/hidden; the header acts as a toggle |

## 4. States

**Status:** Not documented in source material
