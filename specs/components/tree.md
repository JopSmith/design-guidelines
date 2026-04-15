# Tree

## 1. Description

A Tree component presents a hierarchical view of information organised into multiple levels. It allows users to expand or collapse parent items to reveal or hide child items, showing only the information they need while conserving screen space. This structure makes relationships between items clear and supports efficient navigation through nested content.

## 2. Usage

### When to Use

Use a Tree when displaying data with a natural parent-and-child relationship, such as folder structures, organisational hierarchies, or case management systems. It is particularly useful when users need to explore structured data without loading separate pages. Avoid using it for flat lists or shallow content where hierarchy is unnecessary.

### Do
- Use Trees for structured data such as folders, cases, or categories
- Keep hierarchy logical and limited to 4 levels or fewer
- Place frequently used items near the top of the Treeview
- Indent sub-levels clearly to show hierarchy
- Use expand and collapse behaviour to manage space efficiently

### Don't
- Use Trees for primary navigation — use a Navigation Bar or Header instead
- Build deeply nested structures that overwhelm users
- Force users to drill down multiple levels for commonly accessed items
- Display all levels without indentation so the structure is unclear
- Show all levels expanded by default

## 3. Composition

The Tree consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Leading icon | Optional | An optional icon displayed before a tree node label to reinforce meaning, such as indicating a folder, file, or status |
| Checkbox | Optional | An optional checkbox within each node that enables selection of individual items, supporting single or multiple selection patterns within the hierarchy |
| Filter | Optional | An optional input placed above the Tree that allows users to quickly search and narrow visible nodes within large hierarchical structures |

## 4. States

**Status:** Not documented in source material
