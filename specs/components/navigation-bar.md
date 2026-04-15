# NavigationBar

## 1. Description

A NavigationBar is a bottom navigation element that provides access to the primary destinations within an application. It is designed primarily for mobile devices, where it appears fixed at the bottom of the screen and presents destinations using both icons and labels to ensure clarity and accessibility. On larger screens, it adapts into a NavigationRail to better suit expanded layouts while maintaining consistent navigation structure.

## 2. Usage

### When to Use

Use a NavigationBar when you need to provide quick access to a small set of core sections within a mobile experience. It is particularly appropriate when destinations are of equal importance and should remain persistently accessible, supporting efficient movement between primary areas of the application.

### Do
- Use a NavigationBar for primary destinations of equal importance
- Limit the number of destinations to maintain clarity and usability — maximum 5, with the fifth becoming a "More" button to route to additional items
- Include both icons and labels for clear recognition
- Clearly indicate the active destination
- Keep the NavigationBar fixed and consistently visible on mobile
- Adapt the component appropriately for larger screens as a NavigationRail

### Don't
- Include secondary or rarely used links
- Overcrowd the NavigationBar with more than 5 items
- Rely on icons alone to communicate meaning
- Leave users uncertain about their current location
- Allow it to scroll out of view during primary navigation
- Use the mobile layout unchanged on desktop interfaces

## 3. Composition

The NavigationBar consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Badge | Optional | Allows notifications to be indicated |

## 4. States

**Status:** Not documented in source material
