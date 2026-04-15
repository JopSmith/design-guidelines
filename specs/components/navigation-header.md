# NavigationHeader

## 1. Description

A NavigationHeader is the top-level container for global navigation elements within an application. It forms part of the application shell and must always be present to provide consistent structure and orientation. Positioned at the top of the screen, it offers persistent access to essential features such as search, user profile, and application-level tools, reinforcing brand presence and navigation clarity.

## 2. Usage

### When to Use

Use a NavigationHeader when you need to provide stable, global access to core navigation and system-level actions across the entire product. It is particularly appropriate in applications where users regularly move between major sections, access account settings, or rely on shared tools from any page within the experience.

### Do
- Keep the NavigationHeader persistent as part of the application shell
- Include only global navigation and system-level actions, e.g. Search, Product Hub, Profile
- Maintain consistent layout and behaviour across the product
- Ensure clear branding and orientation within the header
- Support accessibility with proper semantic structure and keyboard navigation
- Optimise for responsive behaviour across screen sizes
- Use clearly labelled buttons alongside icons for clarity

### Don't
- Remove or hide it on standard application pages
- Place page-specific or contextual controls in the NavigationHeader
- Alter structure or positioning between sections
- Overcrowd the space with unnecessary elements
- Rely solely on visual cues to communicate function
- Allow elements to overlap, truncate incorrectly, or break layout on smaller screens
- Rely on icon-only buttons without visible labels

## 3. Composition

The NavigationHeader consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Brand | Optional | Shows the brand logo and product name |
| Chip | Optional | Allows the currently logged-in organisation to be shown, e.g. Feversham Academy |
| Actions | Optional | Right-aligned buttons for global navigation |

## 4. States

**Status:** Not documented in source material
