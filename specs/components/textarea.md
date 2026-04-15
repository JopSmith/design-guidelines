# Textarea

## 1. Description

A Textarea component is a form input that allows users to enter multiple lines of plain text. It supports unstyled content only and does not provide formatting controls or rich editing features. Textareas are designed for longer written responses where users need more space than a single-line input field provides.

## 2. Usage

### When to Use

Use a Textarea when capturing extended input such as comments, explanations, descriptions, or reasons for a request. It is appropriate when formatting is not required and when users may need flexibility to write freely across several lines. Avoid using it for short single-line responses or when structured or formatted content is needed.

### Do
- Use Textareas for multi-line inputs such as reasons or comments
- Set an initial height appropriate to the expected content
- Allow vertical resizing so users can expand if needed
- Provide labels, help text, or counters when relevant
- Use validation for mandatory or character-limited Textareas

### Don't
- Use Textareas for single words or short values — use an Input instead
- Make all Textareas full width and full height without context
- Restrict resizing when large amounts of text may be needed
- Rely only on placeholder text for guidance
- Allow unchecked, unclear, or over-limit entries

## 3. Composition

The Textarea consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| AI aura | Optional | An optional visual treatment that indicates AI is generating or processing content. This style differentiates AI-driven activity from standard Textareas |

## 4. States

**Status:** Not documented in source material
