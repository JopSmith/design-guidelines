# PageHeader

## 1. Description

A PageHeader sits directly below the NavigationHeader and defines the top of a page. It clearly communicates the page's purpose through its title, subtitle, and supporting elements such as breadcrumbs, chips, or contextual actions. The PageHeader provides structure, reinforces hierarchy, and ensures users always understand where they are within a product.

## 2. Usage

### When to Use

Use a PageHeader to clearly establish a page's identity and present key contextual information and actions. It should be visible on every page to maintain consistency and orientation, especially in applications with multi-level navigation or structured, task-based workflows.

### Do
- Use a single PageHeader on every page that users navigate to
- Always include a title and optionally a subtitle where secondary text is required, e.g. a reference number
- Use concise, descriptive page titles that clearly communicate the page's purpose or content
- Align the page title to the left and place actions to the right to create clear visual hierarchy
- Use a single primary button to highlight the main call-to-action, and outlined buttons for any secondary actions
- Include a leading icon on the primary button to enhance visual hierarchy and make the key action instantly recognisable
- Limit header actions to a maximum of four buttons — if additional actions are needed, use a "More" button with a dropdown menu
- Use a More button with a trailing dropdown icon when space is limited or when more than four page-level actions are needed
- Use buttons with clear, descriptive labels so users can easily understand each action's purpose
- Stack the page title above the subtitle, chip, and breadcrumbs on smaller screens
- Collapse actions into a single outlined button on smaller screens, which opens an overflow menu
- Use responsive wrapping of text where titles are wider than space allows
- Keep the header sticky as it provides key context and actions that must be visible when scrolling content
- Order buttons from most positive to most negative, right to left, with the cancel/close button last

### Don't
- Skip the PageHeader or use multiple instances in the same page
- Omit the title or replace it with a subtitle alone
- Use vague, lengthy, or generic titles
- Centre or mix the alignment of titles and actions
- Use multiple primary buttons or make secondary actions visually equal to the primary one
- Omit the leading icon or use icons inconsistently
- Overload the header with too many buttons
- Add additional buttons beyond the limit or use a More button without an indicator icon
- Use icon-only buttons (unless universally recognised) or omit labels
- Keep all elements inline as on desktop on smaller screens
- Leave multiple action buttons visible on smaller screens
- Display all actions and elements at once on smaller screens
- Truncate important text unnecessarily
- Let the header scroll out of view when it contains important context or actions
- Arrange buttons in a random or inconsistent order

## 3. Composition

The PageHeader consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Page title (Mandatory) | Mandatory | Displays the name of the page |
| Subtitle | Optional | Appears below the page title and used for secondary text |
| Chip | Optional | Placed alongside the subtitle for additional context, such as showing a status |
| Breadcrumbs | Optional | Placed underneath the subtitle, providing a contextual navigation trail |
| Leading item(s) | Optional | Allows placement of elements at the start of the header, such as a Back button, an Avatar, or an icon |
| Action(s) | Optional | Right-aligned buttons for page-level actions |

## 4. States

**Status:** Not documented in source material
