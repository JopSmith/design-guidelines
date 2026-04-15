# OrderList

## 1. Description

An OrderList is a vertically stacked list of items that users can reorder to define sequence or priority. It visually displays the current order and typically includes a vertical control column with icon buttons that allow items to be moved up or down. Alongside these controls, a list panel presents the ordered items clearly, making the sequence easy to understand and adjust.

## 2. Usage

### When to Use

Use an OrderList when the position of items directly affects behaviour, priority, or execution order, such as notification rules, processing pipelines, task sequences, or step configurations. It is particularly appropriate when users must actively manage and refine order rather than simply select or edit items.

### Do
- Use an OrderList when order has meaning and affects behaviour, priority, or execution
- Clearly label each row with concise, meaningful text
- Keep items short enough to fit comfortably within a single line
- Provide obvious controls to move items up and down
- Use disabled states for controls that cannot act
- Use this pattern for manual prioritisation, sequencing steps, or ranking

### Don't
- Use an OrderList if item order does not matter and a standard list or table would suffice
- Use vague or duplicated labels that make items difficult to distinguish
- Allow long or multiline content that disrupts row consistency
- Hide reordering controls or rely solely on drag and drop without an accessible alternative
- Allow users to attempt impossible or confusing actions
- Use it as a general navigation list for browsing content

## 3. Composition

The OrderList consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Title | Optional | Displays a name for the OrderList |
| Subtitle | Optional | Appears below each list item and used for secondary text |
| Icons | Optional | A leading or trailing icon used to add visual interest |
| Avatar | Optional | Allows a user avatar to appear |
| Badge | Optional | Allows a badge to display a count or notification |

## 4. States

**Status:** Not documented in source material
