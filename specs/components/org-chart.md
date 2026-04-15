# OrgChart

## 1. Description

An OrgChart component, or organisation chart, visually represents hierarchical relationships between people, teams, or roles within an organisation. It arranges repeating nodes horizontally and/or vertically, connected by lines to show reporting structure and relative position. Each node is typically presented as a card displaying a name and optionally a role or title, enabling users to understand structure and relationships at a glance.

## 2. Usage

### When to Use

Use an OrgChart when users need to explore reporting lines, areas of responsibility, or team structure in a clear visual format. It is particularly useful for supporting decisions related to ownership, escalation paths, workload distribution, or communication flow within an organisation.

### Do
- Use an OrgChart to communicate reporting structure such as who reports to whom
- Use consistent node sizing and spacing to make hierarchy easy to scan
- Show clear connectors between levels to indicate relationships
- Include role or position where it helps interpret responsibility
- Keep charts focused on a single functional area or team when displayed inline
- Ensure the layout remains clear and readable at a glance

### Don't
- Use an OrgChart to visualise processes or workflows — this requires a flowchart
- Mix different card styles, sizes, or typography within the same chart
- Place nodes without connecting lines, as this creates ambiguity
- Overload nodes with excessive details such as contact information, metrics, or status indicators
- Attempt to display an entire organisation in one dense view
- Compromise clarity by compressing spacing or crowding nodes

## 3. Composition

The OrgChart consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Title (Mandatory) | Mandatory | Displays the primary name of the person or position represented by the node |
| Subtitle | Optional | Provides supporting information such as role, department, or responsibility |
| Avatar | Optional | Displays a visual representation of the individual, typically a profile image or initials |

## 4. States

**Status:** Not documented in source material
