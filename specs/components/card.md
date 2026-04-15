# Card

## 1. Description

A Card is a flexible container used to display structured content such as summaries, lists, charts, or forms. Cards act as self-contained visual blocks that can be used across dashboards, forms, and pages to group related content.

## 2. Usage

### When to Use

Use Cards to group related UI elements in a way that is visually distinct but consistent across the application. They help organise layouts and support clear, readable interfaces.

### Do
- Use Cards to visually separate different types of content
- Maintain consistent padding and layout structure
- Use Cards as containers for components like charts, tables, etc
- Include a header and footer when appropriate
- Use scrollable body sections when content overflows
- Respect Card density (default or compact) for consistent spacing

### Don't
- Use Cards as a replacement for modals or dialogs
- Overcrowd Cards with too much unrelated content
- Use Cards for decorative purposes only
- Leave footer actions floating, misaligned, or outside the footer slot
- Let overflowing content break the layout or hide important info
- Mix densities inconsistently within the same layout

## 3. Composition

The Card consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Title (Mandatory) | Mandatory | Displays the name of the card |
| Subtitle | Optional | Appears below the title and used for secondary text |
| Leading item(s) | Optional | Allows placement of elements at the start of the header, such as an Avatar or an icon |
| Trailing item(s) | Optional | Allows placement of elements at the end of the header, such as actions |
| Action(s) | Optional | Allows placement of elements in the footer such as footnotes or actions |

## 4. States

**Status:** Not documented in source material
