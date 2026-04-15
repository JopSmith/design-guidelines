# Accordion

## 1. Description

An Accordion is a collapsible content container that allows users to expand or collapse sections of information. It helps reduce vertical space on a page by hiding non-critical content until needed. Accordions improve content hierarchy, letting users browse multiple sections efficiently while maintaining focus on one piece of content at a time. When expanded, an Accordion pushes surrounding content downward rather than overlaying it.

## 2. Usage

### When to Use

Use an Accordion when a page contains multiple related topics that don't all need to be visible at once. It works well for optional details, FAQs, or long lists where users can choose what to engage with based on their immediate needs. Accordions support progressive disclosure, helping users move through content at their own pace without distracting from the primary task or message of the page.

### Do
- Use Accordions to group large amounts of related content
- Write short, descriptive headings that clearly summarise the content
- Allow multiple Accordions to expand simultaneously
- Use Accordions to improve page scannability
- Make the entire Accordion header toggle the body to provide a clear and consistent interaction

### Don't
- Use Accordions as navigation or for critical information that must always be visible
- Use overly long or vague labels for Accordion headers
- Restrict users to one open Accordion at a time
- Overuse Accordions to hide too much information
- Place additional clickable elements inside the header, as this creates conflicting interactions which breaks semantics and accessibility

## 3. Composition

The Accordion consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Title (Mandatory) | Mandatory | Displays the primary heading that describes the content within the Accordion section |
| Subtitle | Optional | Provides supporting or contextual information beneath the title |
| Icon | Optional | Adds a visual cue to help identify or differentiate the section |
| Chip | Optional | Highlights status, category, or key metadata related to the section |
| Dropdown arrow or caret (Mandatory) | Mandatory | Indicates the expand and collapse behaviour and reflects the current state of the section |

## 4. States

**Status:** Not documented in source material
