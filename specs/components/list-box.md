# ListBox

## 1. Description

A ListBox component is a selection control that displays a visible list of options directly within the page layout, allowing users to select one or multiple items. Unlike a dropdown or select menu, the options remain expanded and accessible without requiring an additional click to reveal them. A ListBox supports clear selection states, keyboard interaction, and scrolling when needed, making it suitable for structured option sets presented inline.

## 2. Usage

### When to Use

Use a ListBox when users need to select from a predefined list that should remain visible within the interface rather than hidden inside a dropdown. It is particularly appropriate when space allows options to be displayed openly, when selection is a primary task on the page, or when multiple selections are required without collapsing the list after each choice.

### Do
- Use a ListBox when options should remain visible within the page layout
- Support both single and multiple selection where appropriate
- Make selected states clear and easy to distinguish
- Keep the list structured and logically ordered
- Enable keyboard navigation and focus management
- Use scrolling when the list exceeds available space

### Don't
- Hide primary selections inside a dropdown when visibility improves usability
- Restrict selection behaviour without clear reason
- Rely on subtle styling that makes selection hard to recognise
- Present options in a random or confusing sequence
- Design the ListBox to be mouse-dependent
- Allow the ListBox to expand indefinitely and disrupt the page layout

## 3. Composition

The ListBox consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Header | Optional | Can be used to allow users to filter the list |
| Group | Optional | Allows the list to be segmented by showing group subheadings |

## 4. States

**Status:** Not documented in source material
