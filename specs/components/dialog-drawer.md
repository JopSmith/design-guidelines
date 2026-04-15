# DialogDrawer

## 1. Description

A DialogDrawer component is a layered interface element that appears on top of an already open Drawer or side panel. It allows a focused message, confirmation, or input request to be presented within the context of the existing Drawer, without opening a separate Dialog over the full page or navigating the user away from their current task. DialogDrawers maintain spatial continuity while clearly interrupting the flow, and they use contextual colours to signal intent, such as neutral, success, warning, or danger states.

## 2. Usage

### When to Use

Use a DialogDrawer when a user is working within a Drawer and an additional decision, confirmation, or required input must be addressed before they can continue. It is particularly useful when you want to preserve the underlying Drawer context, avoid stacking multiple full-page overlays, and keep the user anchored to their current workflow while still drawing attention to an important action.

### Do
- Use a DialogDrawer to interrupt a task within an open Drawer when a decision, confirmation, or required input is necessary
- Use contextual colours to clearly communicate intent, such as neutral, success, warning, or danger
- Keep the content focused on a single clear action or decision
- Ensure the user can clearly understand the impact of their action before proceeding
- Preserve the context of the underlying Drawer so users can easily return to their previous task
- Use concise titles and action labels that reflect the specific interruption

### Don't
- Open a full-page Dialog on top of a Drawer when a DialogDrawer would maintain better context
- Use neutral styling for destructive or high-risk actions that require stronger visual signalling
- Overload the DialogDrawer with multiple unrelated tasks or excessive content
- Present irreversible actions without clear explanation or confirmation
- Force users back to the main page unnecessarily
- Use vague language that makes the purpose of the DialogDrawer unclear

## 3. Composition

The DialogDrawer consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Title (Mandatory) | Mandatory | Displays the name of the DialogDrawer |
| Subtitle | Optional | Appears below the title and used for secondary text |

## 4. States

**Status:** Not documented in source material
