# DataView

## 1. Description

A DataView is a flexible component used to display collections of data in a more visual or customised layout than a traditional table. It supports stylised formats such as cards, tiles, or custom list items, making it easier to present varied content and hierarchy, especially on smaller screens.

## 2. Usage

### When to Use

Use a DataView when data benefits from a richer, more expressive layout or needs to adapt well to mobile and responsive experiences. DataViews are better suited than tables for touch-based interaction and narrow viewports, where horizontal space is limited. They work well for content libraries, media collections, and dashboards, while still supporting filtering, sorting, pagination, and selection while allowing greater freedom in layout and presentation.

### Do
- Use a DataView for stylised or custom layouts such as cards or tiles
- Use a DataView for mobile-friendly or responsive layouts
- Maintain consistent structure and spacing across items
- Make primary information easy to scan at a glance
- Support filtering and sorting when working with larger datasets
- Use clear, discoverable actions within each item
- Ensure accessibility across custom layouts

### Don't
- Use a DataView when data requires precise comparison across columns
- Use a DataView when dense, column-based comparison is required
- Allow item layouts to vary unpredictably
- Hide key details behind excessive styling
- Force users to manually browse large collections
- Overload items with too many actions or controls
- Sacrifice usability or accessibility for visual design

## 3. Composition

The DataView consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Action | Optional | Provides item-level or bulk actions |
| Avatar | Optional | Displays a visual identifier such as a person, brand, or entity associated with the item |
| Badge | Optional | Highlights status, counts, or key metadata related to the item |
| Chip | Optional | Represents tags, categories, or filters associated with the item |
| Header | Optional | Displays controls for the DataView and can include elements such as a search input |
| Icon (leading and/or trailing) | Optional | Adds visual context or reinforces meaning before or after item content |
| Multi-select | Optional | Allows users to select multiple items for batch actions |
| Pagination | Optional | Splits large collections into pages for easier navigation and performance |
| Subtitle | Optional | Provides secondary or supporting information beneath the header |

## 4. States

**Status:** Not documented in source material
