# Design Guidelines - AI Instructions

## Project Overview

This directory contains structured documentation for the design system components, patterns, and templates. The goal is to make design system knowledge LLM-readable so that AI assistants can help developers build IX-compliant applications.

## Directory Structure

```
design-guidelines/
├── specs/
│   ├── components/        # Structured markdown specs for each component (94 specs)
│   ├── patterns/          # Structured markdown specs for design patterns (7 specs)
│   └── templates/         # Structured markdown specs for layout templates (1 spec)
├── CLAUDE.md             # This file - AI instructions
└── [source files]        # Temporary .doc/.docx/.pdf files during conversion
```

## Working with Specs

### Converting Source Documents to Specs

When provided with component, pattern, or template guideline documents (typically .doc or .docx files from Confluence):

1. **Convert binary formats to readable formats:**
   - Use PowerShell Word COM automation to convert .doc → .pdf for reading
   - Extract all content from the document

2. **Create structured markdown spec** in the appropriate directory following the templates below:
   - Components: `specs/components/[ComponentName].md`
   - Patterns: `specs/patterns/[pattern-name].md`
   - Templates: `specs/templates/[template-name].md`

3. **Clean up source files** after successful conversion (remove .doc, .docx, .pdf files)

### Spec Templates

#### Component Spec Template

Every component spec MUST follow this structure:

```markdown
# [Component Name]

## 1. Description

[Clear description of what the component is and its purpose. Include behavioral characteristics.]

## 2. Usage

### When to Use

[Describe scenarios where this component should be used]

### Do

- [Guideline 1]
- [Guideline 2]
- [Guideline 3]

### Don't

- [Anti-pattern 1]
- [Anti-pattern 2]
- [Anti-pattern 3]

## 3. Composition

The [Component Name] consists of the following accessories:

| Accessory | Required | Description |
|-----------|----------|-------------|
| [Name] | Mandatory/Optional | [Description] |

## 4. States

**Status:** [Documented/Not documented in source material]

- **[State Name]** - [Description]
- **[State Name]** - [Description]

Common states to document:
- Default
- Hover
- Active
- Focus
- Disabled
- Read-only

```

#### Pattern Spec Template

Every pattern spec MUST follow this structure:

```markdown
# [Pattern Name]

## 1. Description

[Clear description of what the pattern is and its purpose.]

## 2. Usage

[Describe when and how to use this pattern]

### Do

- [Guideline 1]
- [Guideline 2]
- [Guideline 3]

### Don't

- [Anti-pattern 1]
- [Anti-pattern 2]
- [Anti-pattern 3]

## 3. Types

[If applicable, describe different variants or types of this pattern]

### 3.1 [Type Name]

[Description and specifications for this type]
```

#### Template Spec Template

Every template spec MUST follow this structure:

```markdown
# [Template Name]

## 1. Description

[Clear description of what the template is and its purpose.]

## 2. Usage

[Describe when and how to use this template]

### Do

- [Guideline 1]
- [Guideline 2]
- [Guideline 3]

### Don't

- [Anti-pattern 1]
- [Anti-pattern 2]
- [Anti-pattern 3]

## 3. Types

[If applicable, describe different variants or layout types]

### 3.1 [Type Name]

[Description and specifications for this type]
```

### Spec Quality Standards

- ✅ Use clear, concise language
- ✅ Preserve exact terminology from source documents
- ✅ Use consistent formatting (headings, tables, lists)
- ✅ Mark incomplete sections with "**Status:** Not documented in source material"
- ✅ Extract ALL information from source documents
- ✅ Use tables for structured data (Composition, States)
- ⛔ Do NOT add information not present in source documents
- ⛔ Do NOT remove or simplify documented guidelines
- ⛔ Do NOT create specs without source documentation

## Building MDS-Compliant Applications

When building applications using MDS:

1. **Always read the relevant specs first** from:
   - `specs/components/` for component-specific guidance
   - `specs/patterns/` for interaction and UI patterns
   - `specs/templates/` for layout and structural guidance
2. **Follow composition rules** - only use documented accessories and structures
3. **Respect Do/Don't guidelines** - these are design system rules, not suggestions
4. **Use mandatory accessories** - never omit required elements
5. **Consider states** - ensure all interactive states are implemented
6. **Apply patterns consistently** - use established patterns for common interactions
7. **Use appropriate templates** - select the right shell and layout structure for your use case
8. **Reference related components and patterns** - suggest appropriate alternatives when needed

## Guidelines Sources

Primary sources: Word documents
- Components: C:\Users\Jonathan.Smith\design-guidelines\component-guidelines.docx
- Patterns: C:\Users\Jonathan.Smith\design-guidelines\pattern-guidelines.docx
- Templates: C:\Users\Jonathan.Smith\design-guidelines\template-guidelines.docx

## Notes for AI Assistants

- These specs are the source of truth for components, patterns, and templates
- When in doubt about usage, refer to the relevant spec (component, pattern, or template)
- If a spec is missing or incomplete, ask the user for the source document
- Keep specs up-to-date as guidelines evolve
- Suggest creating new specs when encountering undocumented components, patterns, or templates
- Before presenting or serving up these guidelines, read the relevant spec file in specs/ for accuracy and updates. Ensure zero differences
- **Components** define individual UI elements and their behavior
- **Patterns** define interaction paradigms and UI conventions
- **Templates** define structural layouts and application frameworks
