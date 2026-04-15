# InputGroup

## 1. Description

An InputGroup enables supplementary elements to be visually connected to a text input, such as labels, icons, buttons, or controls. These elements appear directly adjacent to the field and provide contextual meaning or related actions without separating them from the input itself.

Common examples include prefix or suffix text like currency symbols or units, embedded action buttons, and icons that communicate status or initiate an action.

## 2. Usage

### When to Use

Use an InputGroup when additional context or functionality needs to be tightly associated with a specific input field. It is particularly effective when the extra element clarifies the expected format, enhances efficiency through direct actions, or reinforces meaning without interrupting the user's flow.

### Do
- Use an InputGroup when additional context or actions are directly related to the input value
- Keep grouped elements visually and functionally integrated with the input
- Use prefixes or suffixes to clarify format such as currency or units
- Ensure embedded buttons or icons have clear purpose and affordance
- Maintain consistent spacing and alignment within the group
- Preserve accessibility and keyboard interaction for all grouped elements

### Don't
- Attach elements that are unrelated to the specific field
- Separate grouped controls in a way that breaks their association
- Rely on surrounding text alone to communicate required format
- Include decorative elements that add no functional value
- Crowd the input or reduce legibility with oversized controls
- Create grouped controls that interfere with focus order or usability

## 3. Composition

The InputGroup consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Text before | Optional | Allows text on the left of a text input |
| Text after | Optional | Allows text on the right of a text input |
| Text before and after | Optional | Allows text on the left and right of a text input |
| Button before | Optional | Allows a button on the left of a text input |
| Button after | Optional | Allows a button on the right of a text input |
| Button before and after | Optional | Allows a button on the left and right of a text input |

## 4. States

**Status:** Not documented in source material
