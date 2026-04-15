# Tabs

## 1. Description

A Tabs component organises related content into labelled sections that can be switched without leaving the current page. Each tab reveals its associated content within the same view, allowing users to move between sections quickly and without a full page refresh. Tabs are always displayed horizontally and include a clear active state to indicate which section is currently visible.

## 2. Usage

### When to Use

Use Tabs to break related information into manageable sections where users benefit from comparing or switching between content in place. They are well suited to dashboards, settings pages, or detail views that contain grouped information. Avoid using Tabs for unrelated content, deep hierarchical navigation, or when too many sections would reduce clarity and overwhelm the interface.

### Do
- Use Tabs for switching between related sections on the same page
- Keep Tab titles short, ideally 1 to 2 words, and clear
- Use horizontal Tabs for related content
- Limit to 2 to 8 Tabs for clarity
- Arrange Tabs in a logical order with the most used first
- Ensure Tabs are large enough for touch interaction on mobile
- Allow swipe scrolling on mobile when Tabs overflow

### Don't
- Use Tabs as a replacement for navigation or breadcrumbs
- Use vague or lengthy Tab titles
- Mix unrelated content in the same Tab
- Add more than 8 Tabs in a single row
- Order alphabetically if it reduces usability
- Shrink Tabs below an accessible size
- Leave overflowing Tabs inaccessible

## 3. Composition

The Tabs consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Icons | Optional | Optional icons displayed alongside tab labels to support quick recognition and reinforce meaning |
| Badges | Optional | Optional badges shown against individual tabs to indicate counts, status, or notifications such as errors or updates |
| Card | Optional | Tabs can be displayed within a card layout to visually group related content and provide structural separation from the surrounding page |
| Card Footer | Optional | An optional footer within the card that can contain supporting actions, summaries, or secondary controls related to the tab content |

## 4. States

**Status:** Not documented in source material
