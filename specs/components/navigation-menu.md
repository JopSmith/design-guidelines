# NavigationMenu

## 1. Description

A NavigationMenu is a vertical panel typically positioned on the left-hand side of an application. It forms part of the application shell and must be present to provide consistent structural navigation across the product. The NavigationMenu presents links in a clear, hierarchical list, often with expandable sections to organise related destinations and support intuitive wayfinding. It can be toggled in and out of view to maximise available space, and on mobile devices it transitions into a Drawer component to maintain usability within smaller layouts.

## 2. Usage

### When to Use

Use a NavigationMenu when an application contains multiple sections that require persistent and visible navigation. It is particularly suitable for desktop or larger screen layouts where space allows for a dedicated navigation area, and where users need reliable access to primary and secondary sections from any point within the experience.

### Do
- Keep the NavigationMenu as a persistent part of the application shell
- Structure links hierarchically to support clear wayfinding
- Allow the NavigationMenu to be toggled in and out of view to optimise space
- Clearly indicate the active section or page
- Ensure smooth transition to a Drawer pattern on mobile devices
- Keep labels concise and meaningful
- Limit NavigationMenu hierarchy to no more than 5 levels to maintain clarity and usability
- Group related links using menu groups and clear subheadings
- Use parent menu items solely to expand or collapse their related sub-items
- Use icons for top-level menu items only to aid quick recognition
- Include only one Home menu item at the top level of the NavigationMenu

### Don't
- Remove it on standard application views
- Present a flat, unorganised list of destinations
- Force it to remain expanded when space is limited
- Leave users uncertain about their current location
- Use the desktop layout unchanged on small screens
- Rely on icon-only navigation without visible text labels
- Create deeply nested structures beyond 5 levels
- List too many unrelated items without structure
- Assign direct navigation links to parent items that contain sub-menus
- Add icons to lower-level menu items or omit icons from level-one items
- Label the first item inside collapsible sections or groups as "Home", as this creates confusion

## 3. Composition

The NavigationMenu consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Header | Optional | Displays the brand logo and product name |
| Icon | Optional | A leading or trailing icon used to add visual interest to top-level menu items |
| Chip | Optional | Allows a status or count to be displayed |
| Groups | Optional | Allows the list to be segmented by showing group subheadings |
| Dropdown | Optional | Enables groups to be expanded and collapsed |
| Footer | Optional | A slot at the bottom of the menu for persistent, lower-priority items such as settings, actions, or version information |

## 4. States

**Status:** Not documented in source material
