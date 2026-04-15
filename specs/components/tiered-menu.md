# TieredMenu

## 1. Description

A TieredMenu, also known as a FlyoutMenu, is a hierarchical navigation control that reveals submenus beside the parent item, typically to the right. Submenus can be revealed on click or on hover depending on the interaction model and device context. As users move through the menu, each level remains visible while exposing deeper categories. Only items without further submenus act as final destinations, allowing users to understand the structure before making a selection.

## 2. Usage

### When to Use

Use a TieredMenu when users need to browse categories with one or two nested levels and select a final destination without leaving the current page until a choice is made. It is well suited to structured navigation systems where relationships between categories should remain visible and where submenus can be revealed on click or hover as appropriate. Avoid using it for deeply nested hierarchies or complex information architectures that would overwhelm the interface.

### Do
- Use for multi-level navigation where breadth is greater than depth
- Clearly distinguish parent items from destination items
- Reveal submenus on click or hover based on device and accessibility needs
- Open submenus next to the parent and preserve context
- Limit depth to 3 or fewer levels and group items logically
- Provide generous hover or tap targets and predictable alignment

### Don't
- Use for simple single-level lists — use a Menu or Dropdown instead
- Add the same submenu affordance to destination items
- Rely only on hover interactions where click support is required
- Replace the whole menu on each level — that is a Drilldown pattern
- Create sprawling trees that require precise hover or complex cursor movement
- Let submenus overlap critical interface elements or render off-screen

## 3. Composition

**Status:** Not documented in source material

## 4. States

**Status:** Not documented in source material
