# Panel

## 1. Description

A Panel is a collapsible content container used to group related information and actions within a bordered, elevated block. Similar to an Accordion, it allows sections to be expanded or collapsed, but only the toggle control on the right-hand side of the header triggers this behaviour rather than the entire header area. A Panel includes a header, a body area for main content, and an optional footer, creating clear visual structure and hierarchy without requiring a full page transition.

## 2. Usage

### When to Use

Use a Panel when you need to organise content into distinct, readable sections within the same page. It is particularly effective in dashboards, sidebars, summaries, and detail views where grouping related information improves clarity while maintaining continuity within the overall layout.

### Do
- Use a Panel to group content that belongs together conceptually such as a profile summary or progress overview
- Use clear, descriptive titles that reflect the content of the Panel
- Place lightweight actions in the Panel header when they apply to the entire Panel
- Use Panels to create visual separation in mixed layouts such as dashboard views
- Keep Panels focused and easy to scan
- Use a Panel when hierarchy is needed without changing page context

### Don't
- Use multiple Panels for content that should remain a continuous form or table
- Use vague or unhelpful titles such as "Info" or "Other"
- Scatter panel-level actions throughout the body content
- Nest Panels inside other Panels, as this creates visual clutter
- Overload a single Panel with excessive text or unrelated sections
- Use a Panel when a dedicated page section would provide clearer structure

## 3. Composition

The Panel consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Title (Mandatory) | Mandatory | Displays the primary heading that defines the content of the Panel |
| Subtitle | Optional | Provides supporting context or secondary information beneath the title |
| Avatar | Optional | Displays a visual identifier such as a profile image or initials when relevant to the content |
| Chip | Optional | Highlights status, category, or key metadata associated with the Panel |
| Action | Optional | Provides a lightweight control such as Edit or Download that applies to the entire Panel |
| Toggle button | Optional | Expands or collapses the Panel body when interaction is required |
| Footer | Optional | Contains secondary actions or supporting links related to the Panel content |

## 4. States

**Status:** Not documented in source material
