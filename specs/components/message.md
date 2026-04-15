# Message

## 1. Description

A Message, also known as an Alert, is a feedback component used to communicate important information to the user within the context of the current page or section. It typically appears inline and uses visual cues such as colour and iconography to convey meaning, such as success, information, warning, or error. A Message is designed to be noticeable without interrupting the overall flow of the interface.

## 2. Usage

### When to Use

Use a Message when you need to provide contextual feedback, status updates, or guidance that affects a system, page, feature, or form. It may or may not be specific to a task. It is appropriate for communicating validation outcomes, system responses, or helpful notices that users should be aware of, but which do not require a blocking interaction such as a Dialog.

Examples:
- "The system will be unavailable between 4–5 PM"
- "You do not have permissions to view this page"
- "Version 2 is now available. Upgrade now!"

### Do
- Place the Message inline at the top of a page, Dialog, Drawer, or form where the information is immediately relevant
- Keep the Message fixed in place so it remains visible and does not fade in or out
- Ensure the content is clear, concise, and contextual to the user's current task
- Show only one Message at a time to maintain clarity and priority
- Use contextual styling and optional icons to reinforce meaning
- Allow dismissal or provide clear actions when appropriate

### Don't
- Position Messages far from the content they relate to
- Use transient behaviour that causes important information to disappear
- Include vague, lengthy, or unrelated information
- Stack multiple Messages in the same space
- Use incorrect variants that misrepresent urgency or intent
- Make the Message blocking unless a Dialog is more suitable

## 3. Composition

The Message consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Title (Mandatory) | Mandatory | Displays the title of the message |
| Subtitle | Optional | Appears below the title and used for the actual message itself |
| Action | Optional | Allows a button to be included for a related action or simply to dismiss the message |
| Close | Optional | Allows the message to be dismissed/closed |

## 4. States

**Status:** Not documented in source material
