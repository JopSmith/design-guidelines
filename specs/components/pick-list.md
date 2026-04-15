# PickList

## 1. Description

A PickList is a multi-selection control that displays two side-by-side lists — one showing available options and the other showing selected items. Users can move items between the two lists to build and manage their chosen set. This layout provides clear visual distinction between what is available and what has already been selected, making selection state easy to understand.

## 2. Usage

### When to Use

Use a PickList when users need to select multiple items from a predefined set and it is important to clearly differentiate selected items from remaining options. It is particularly suitable for configuration tasks, assigning roles or permissions, or managing grouped resources where visibility of both states supports accuracy and control.

### Do
- Use PickList for multi-selection tasks where clarity is essential
- Clearly label the overall PickList and each list box
- Allow users to move multiple items at once using checkboxes
- Ensure items appear only once across the two lists
- Sort items logically, such as alphabetically
- Provide filters when large numbers of items are present

### Don't
- Use PickList for single selections — use a Dropdown or Radio instead
- Leave lists unlabelled or ambiguous
- Force users to move items one at a time
- Allow duplicates between available and selected lists
- Display items in a random or unclear order
- Overload users with long unsorted lists without filtering

## 3. Composition

The PickList consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| List title | Optional | Displays a clear heading above each list to indicate whether items are available or selected |
| Item subtitle | Optional | Provides supporting information beneath the primary item label |
| Leading icon | Optional | Displays a visual cue at the start of a list item to aid recognition |
| Avatar | Optional | Shows a profile image or initials when items represent people or entities |
| Trailing badge | Optional | Highlights status, count, or category information associated with the item |
| Trailing icon | Optional | Indicates an action, state, or additional meaning related to the item |

## 4. States

**Status:** Not documented in source material
