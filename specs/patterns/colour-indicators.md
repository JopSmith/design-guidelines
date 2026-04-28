# UI Pattern Spec (LLM-Friendly Template)

## 1. Pattern Name
Colour Indicators

---

## 2. Intent (Why this exists)
Colour indicator patterns use colour to communicate meaning across an interface, such as status, priority, actions, or data. They help users quickly interpret information at a glance, provided they are applied consistently, semantically, and with clear distinction between different types of meaning.

---

## 3. Context of Use
- Use when:
  - Showing status
  - Highlighting urgency
  - Guiding actions
  - Differentiating data in charts
  - Reinforcing meaning in a way that is immediate and intuitive
- Avoid when:
  - Colour meaning would be mixed or overloaded
  - Colour does not add clear meaning
  - Semantic systems (status, priority, action, data) are not clearly separated

---

## 4. Core Behaviour (How it works)
- Trigger:
  - A UI element requires communication of meaning such as status, priority, action, or data differentiation
- System Response:
  - Apply a specific colour mapped to a defined meaning (status, priority, action, or chart data)
  - Ensure the colour use is consistent and semantically correct
- Ongoing Behavior:
  - Maintain consistent colour usage across the UI
  - Reinforce meaning with labels, icons, or patterns
  - Ensure accessibility through contrast and non-colour indicators
- Exit Condition:
  - Colour is removed or changed when the meaning (status, priority, action, or data context) changes

---

## 5. Rules & Constraints

- MUST:
  - Use colour consistently to represent specific meanings across the UI
  - Use status colours to clearly communicate the state of an item
  - Use priority colours to indicate urgency or importance
  - Use action colours to signal intent and consequences
  - Use chart colours to differentiate data clearly
  - Support colour with labels, icons, or patterns for accessibility
  - Apply colour consistently across the product to build recognition and trust
  - Pair colour with text, icons, or patterns to reinforce meaning
  - Ensure contrast ratios meet accessibility standards
  - Use patterns or additional indicators in charts when needed
  - Use colour purposefully to highlight key information
  - Keep semantic systems clearly separated (status, priority, action, data)
  - Use colour only when it adds clear meaning
  - Ensure status colour is supported by text labels
  - Use consistent placement for status indicators (badges, tags, or indicators adjacent to the item title)
  - Avoid introducing additional status colours beyond the defined system
  - Use priority colours sparingly to avoid visual noise
  - Only apply priority colour when prioritisation affects decision making
  - Provide a textual priority label alongside the colour
  - Reserve red strictly for destructive or irreversible actions
  - Use blue for the primary action within a view
  - Ensure only one primary action is visually dominant at a time
  - Ensure dangerous actions are supported by confirmation patterns where appropriate
  - Follow defined order for chart colours
  - Use secondary tones for layering, stacking, or highlighting in charts
  - Ensure sufficient contrast between adjacent data series
  - Limit the number of visible chart series to maintain clarity

- SHOULD:
  - Avoid relying solely on red and green to convey meaning
  - Avoid using red and green together in charts unless meaning is intentional

- MUST NOT:
  - Change colour meanings between contexts
  - Use status colours for unrelated purposes
  - Confuse priority colours with status indicators
  - Use neutral colours for destructive or critical actions
  - Apply semantic meaning to chart colours incorrectly
  - Rely on colour alone to communicate meaning
  - Introduce new shades for the same meaning
  - Use colour combinations that reduce readability or accessibility
  - Depend only on red and green to differentiate states
  - Overuse colour, reducing its signalling power
  - Mix semantic systems (e.g. using status colours for actions)
  - Use decorative colour where semantic meaning is implied
  - Repurpose status colours for decorative use
  - Combine priority and status colour in a way that causes ambiguity
  - Use action colours for non interactive elements
  - Assign semantic meaning to chart order unless explicitly defined

---

## 6. Variants

- Status Colours:
  - Red → Negative → Rejected, declined, overdue, failed
  - Green → Positive → Approved, accepted, booked, paid, completed
  - Amber → Notice → Pending, scheduled, outstanding, moved
  - Blue → Informative → In use, in progress, in review, live
  - Grey → Neutral → Draft, not started, paused, archived

- Priority Colours:
  - Red → High → Major, critical
  - Amber → Medium → Blocker, caution
  - Blue → Low → Minor, informational
  - Grey → Neutral → None or no priority

- Action Colours:
  - Red → Danger → Delete, remove, reject
  - Green → Success → Save, edit, accept
  - Amber → Warning → Confirm, continue
  - Blue → Primary → Add, create, apply, import
  - Teal → Info → View, preview, show, open
  - White (+border) → Secondary → Cancel, close

- Charting Colours (ordered):
  1. Navy
  2. Lime
  3. Orange
  4. Pink
  5. Teal
  6. Grey
  7. Purple
  8. Blue
  9. Yellow
  10. Green
  11. Red

- Chart Secondary Variants:
  - Each primary colour has a corresponding secondary, lighter variant for:
    - Comparison overlays
    - Secondary datasets

---

## 7. Examples (Abstract, not visual)

- Status Example:
  - Item is marked as “Approved”
  - System applies green status colour
  - Label “Approved” is displayed alongside colour indicator

- Priority Example:
  - Task is marked as “High priority”
  - System applies red priority colour
  - Text label “High” is shown next to the indicator

- Action Example:
  - User sees a delete button
  - System displays button in red
  - Confirmation pattern is triggered before completion

- Chart Example:
  - Multiple datasets are displayed
  - System assigns colours in defined order (Navy, Lime, Orange, etc.)
  - Secondary tones are used for overlays

---

## 8. Rationale (Why it works)
- Helps users quickly interpret information at a glance
- Builds recognition and trust through consistency
- Reduces ambiguity by separating semantic systems
- Improves accessibility when combined with labels, icons, or patterns
- Supports clear decision making through visual cues

---

## 9. Trade-offs

- Pros:
  - Immediate recognition of meaning
  - Faster interpretation of status, priority, and actions
  - Scalable across complex interfaces

- Cons:
  - Misuse can create confusion if meanings are inconsistent
  - Overuse reduces effectiveness of colour as a signal
  - Reliance on colour alone can reduce accessibility

---

## 10. Related Components
- Button
- Badge
- Tag
- Icon
- Chart

---

## 11. Related Patterns
- Status Indicators
- Priority Indicators
- Action Feedback
- Data Visualisation

---

## One-line summary
A structured system for using colour to communicate status, priority, actions, and data clearly and consistently across an interface.
