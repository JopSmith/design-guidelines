# Colour Indicators

## 1. Description

Colour indicator patterns use colour to communicate meaning across an interface, such as status, priority, actions, or data. They help users quickly interpret information at a glance, provided they are applied consistently, semantically, and with clear distinction between different types of meaning.

## 2. Usage

Use colour indicators to reinforce meaning in a way that is immediate and intuitive, such as showing status, highlighting urgency, guiding actions, or differentiating data in charts. Each type of colour usage should have a clear purpose and should not be mixed or overloaded, ensuring users can reliably interpret what colour represents in any given context.

### Do

- Use colour consistently to represent specific meanings across the UI
- Use status colours to clearly communicate the state of an item
- Use priority colours to indicate urgency or importance
- Use action colours to signal intent and consequences
- Use chart colours to differentiate data clearly
- Support colour with labels, icons, or patterns for accessibility
- Apply colour consistently across the product to build recognition and trust
- Pair colour with text, icons, or patterns to reinforce meaning
- Ensure contrast ratios meet accessibility standards
- Avoid relying solely on red and green to convey meaning
- Use patterns or additional indicators in charts when needed
- Use colour purposefully to highlight key information
- Keep semantic systems clearly separated (status, priority, action, data)
- Use colour only when it adds clear meaning

### Don't

- Change colour meanings between contexts
- Use status colours for unrelated purposes
- Confuse priority colours with status indicators
- Use neutral colours for destructive or critical actions
- Apply semantic meaning to chart colours incorrectly
- Rely on colour alone to communicate meaning
- Introduce new shades for the same meaning
- Rely solely on colour to communicate meaning
- Use colour combinations that reduce readability or accessibility
- Depend only on red and green to differentiate states
- Rely only on colour where differentiation may be insufficient
- Overuse colour, reducing its signalling power
- Mix semantic systems, such as using status colours for actions
- Use decorative colour where semantic meaning is implied

## 3. Types

### 3.1 Status Colours

Status colours communicate the current state of an item. They should be semantic, consistent, and immediately recognisable.

| Colour | Status Type | Used For |
|--------|-------------|----------|
| Red | Negative | Rejected, declined, overdue, failed |
| Green | Positive | Approved, accepted, booked, paid, completed |
| Amber | Notice | Pending, scheduled, outstanding, moved |
| Blue | Informative | In use, in progress, in review, live |
| Grey | Neutral | Draft, not started, paused, archived |

**Guidelines:**

- Use status colours only to reflect state, not importance or interactivity
- Do not repurpose status colours for decorative use
- Ensure status colour is supported by text labels. Never rely on colour alone
- Use consistent placement, such as badges, tags, or indicators adjacent to the item title
- Avoid introducing additional status colours beyond this system

### 3.2 Priority Colours

Priority colours indicate urgency or impact level. They differ from status and should not be confused with it.

| Colour | Priority Type | Used For |
|--------|---------------|----------|
| Red | High | Major, critical |
| Amber | Medium | Blocker, caution |
| Blue | Low | Minor, informational |
| Grey | Neutral | None or no priority |

**Guidelines:**

- Use priority colours sparingly to avoid visual noise
- Only apply priority colour when prioritisation affects decision making
- Do not combine priority and status colour in a way that causes ambiguity. If both are required, separate them visually
- Provide a textual priority label alongside the colour

### 3.3 Action Colours

Action colours communicate intent and consequence. They guide user behaviour.

| Colour | Action Type | Used For |
|--------|-------------|----------|
| Red | Danger | Delete, remove, reject |
| Green | Success | Save, edit, accept |
| Amber | Warning | Confirm, continue |
| Blue | Primary | Add, create, apply, import |
| Teal | Info | View, preview, show, open |
| White (+border) | Secondary | Cancel, close |

**Guidelines:**

- Reserve red strictly for destructive or irreversible actions
- Use blue for the primary action within a view
- Only one primary action should be visually dominant at a time
- Grey secondary actions should not compete visually with the primary action
- Ensure dangerous actions are supported by confirmation patterns where appropriate
- Do not use action colours for non interactive elements

### 3.4 Charting Colours

Chart colours are used for data visualisation. They are not semantic in the same way as status or action colours.

| Order | Colour |
|-------|--------|
| 1 | Navy |
| 2 | Lime |
| 3 | Orange |
| 4 | Pink |
| 5 | Teal |
| 6 | Grey |
| 7 | Purple |
| 8 | Blue |
| 9 | Yellow |
| 10 | Green |
| 11 | Red |

Each primary colour has a corresponding secondary, lighter variant for:
- Comparison overlays
- Secondary datasets

**Guidelines:**

- Follow the defined order to ensure consistency across charts
- Do not assign semantic meaning to chart order unless explicitly defined
- Avoid using red and green together where meaning could be misinterpreted as positive or negative unless that meaning is intentional
- Use secondary tones for layering, stacking, or highlighting without overwhelming the visual hierarchy
- Ensure sufficient contrast between adjacent data series
- Limit the number of visible series to maintain clarity
