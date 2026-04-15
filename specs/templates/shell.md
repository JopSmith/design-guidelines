# Shell

## 1. Description

Shell patterns define the structural layout of an application, providing a consistent framework for key UI regions such as navigation, headers, and content areas. They act as the outer container that ensures visual and functional consistency across pages.

## 2. Usage

Use a Shell to establish the global layout of an application, creating a stable and predictable structure for navigation and content. Shells are essential for maintaining consistency across screens, helping users orient themselves and move efficiently through the product.

### Do

- Use a Shell to provide a consistent layout across the application
- Clearly define areas for navigation, header, and content
- Keep navigation placement consistent across views
- Ensure the Shell supports responsive behaviour across devices (Mobile ≤768px, Tablet ≤1279px, Desktop ≥1280px)
- Use the Shell as a stable foundation for page-level content
- Maintain visual and functional consistency across all pages
- Keep navigation open by default

### Don't

- Create different layouts for similar pages without reason
- Blur boundaries between layout regions
- Move navigation elements unpredictably
- Use a fixed layout that does not respond to different screen sizes
- Override or ignore the Shell structure at the page level
- Introduce one-off layout variations that disrupt user expectations
- Collapse or hide navigation unless explicitly required or performed by the user

## 3. Types

Different Shell layouts are needed to accommodate varying levels of navigation complexity, content density, and device constraints, ensuring the interface remains clear, efficient, and scalable across contexts.

### 3.1 Tri-pane Shell

A traditional tri-pane Shell organises the interface into three primary regions: a global header, a side navigation panel, and a main content area. The header typically contains global actions and context, while the side navigation provides access to primary sections of the application. This structure is well suited to complex applications with deep navigation, offering clear separation between global controls, navigation, and content.

**Key characteristics:**

- **Global header** - Contains global actions and context
- **Side navigation panel** - Provides access to primary sections
- **Main content area** - Houses the primary page content
- **Best for** - Complex applications with deep navigation hierarchies
- **Structure** - Clear separation between global controls, navigation, and content

### 3.2 Rail Shell

A rail Shell organises the interface into a global header, a compact navigation rail (with an associated side menu), and a main content area. The header provides global context and actions, while the rail enables quick switching between primary sections, with the side menu adapting to show relevant navigation for the selected section. This pattern is space-efficient and well suited to responsive layouts, supporting efficient navigation without overwhelming the interface.

**Key characteristics:**

- **Global header** - Provides global context and actions
- **Compact navigation rail** - Enables quick switching between primary sections
- **Associated side menu** - Adapts to show relevant navigation for the selected section
- **Main content area** - Houses the primary page content
- **Best for** - Space-efficient and responsive layouts
- **Structure** - Efficient navigation without overwhelming the interface
