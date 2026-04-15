# NavigationRail

## 1. Description

A NavigationRail is a vertical navigation element positioned along the side of an interface, typically used on larger screens. It presents primary destinations in a compact column, usually with icons and optional labels, providing structured access to key sections of an application. It can be combined with a NavigationMenu component to support deeper hierarchical navigation while preserving horizontal space for main content.

## 2. Usage

### When to Use

Use a NavigationRail when designing for tablet or desktop layouts where persistent access to primary destinations is required but a full NavigationMenu would occupy too much space. It transitions to a NavigationBar with a Drawer on mobile devices, ensuring consistent navigation patterns across screen sizes.

### Do
- Use a NavigationRail for primary destinations on tablet and desktop layouts
- Make the first rail item Home to provide a consistent entry point
- Ensure the Home item routes to a single destination
- Limit the number of destinations to a small set of core sections — maximum 8, with the eighth becoming a "More" button if more are needed
- Combine with a NavigationMenu when deeper navigation is required
- Clearly indicate the active destination with distinct styling
- Use icons with clear meaning and provide labels when space allows
- Ensure smooth transition to a NavigationBar with Drawer on mobile devices

### Don't
- Use it for deep hierarchical navigation on its own
- Position Home elsewhere in the rail or duplicate it
- Associate a Menu or secondary navigation with the Home item
- Overcrowd the rail with too many items
- Attempt to nest multiple levels directly within the rail
- Leave users uncertain about their current location
- Rely on unclear or decorative icons
- Keep the desktop rail pattern unchanged on small screens

## 3. Composition

**Status:** Not documented in source material

## 4. States

**Status:** Not documented in source material
