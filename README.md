# MDS Guidelines

> Structured documentation for the Mosaic Design System (MDS) made LLM-readable

## Overview

This repository contains comprehensive, structured documentation for the Mosaic Design System covering components, patterns, and templates. The goal is to make design system knowledge accessible to AI assistants so they can help developers build MDS-compliant applications.

## 📁 Repository Structure

```
mds-guidelines/
├── specs/
│   ├── components/        # 94 component specifications
│   ├── patterns/          # 7 design pattern specifications
│   └── templates/         # 1 layout template specification
├── CLAUDE.md              # AI assistant instructions
├── README.md              # This file
└── .gitignore
```

## 📚 Documentation Coverage

### Components (94 specs)
Detailed specifications for all MDS UI components including:
- Form controls (Button, Input, Select, Checkbox, etc.)
- Navigation (Menu, Tabs, Breadcrumb, etc.)
- Data display (Table, Card, List, etc.)
- Feedback (Toast, Dialog, Message, etc.)
- And many more...

### Patterns (7 specs)
Interaction and UI patterns including:
- **Colour Indicators** - Status, priority, action, and charting colours
- **Empty States** - 12 variants for different scenarios
- **Empty States (API Errors)** - 7 API error states
- **Generative AI** - AI interaction patterns
- **Modal Dialogs** - 4 modal dialog types
- **Non-Modal Dialogs** - 2 non-modal dialog types
- **Social Media Interactions** - News and chat interactions

### Templates (1 spec)
Structural layout templates including:
- **Shell** - Tri-pane and Rail shell layouts

## 🎯 Purpose

Each specification follows a consistent structure:

**Components:**
1. Description
2. Usage (When to Use, Do/Don't)
3. Composition (Accessories and requirements)
4. States (Interactive states and behaviors)

**Patterns & Templates:**
1. Description
2. Usage (Do/Don't guidelines)
3. Types (Variants and examples)

## 🤖 For AI Assistants

See [CLAUDE.md](./CLAUDE.md) for detailed instructions on:
- Converting source documents to specs
- Spec templates and quality standards
- Building MDS-compliant applications
- Understanding the distinction between components, patterns, and templates

## 📖 Usage

When building with MDS, always refer to the relevant specs:

1. **Components** (`specs/components/`) - For individual UI element guidance
2. **Patterns** (`specs/patterns/`) - For interaction paradigms and UI conventions
3. **Templates** (`specs/templates/`) - For layout and structural guidance

## 🔍 Quality Standards

All specs adhere to strict quality standards:
- ✅ Clear, concise language
- ✅ Preserved terminology from source documents
- ✅ Consistent formatting
- ✅ Complete information extraction
- ✅ Structured data in tables
- ⛔ No added information beyond source documents
- ⛔ No simplified or removed guidelines

## 📝 Contributing

When adding or updating specs:
1. Follow the spec templates in CLAUDE.md
2. Extract all information from source documents
3. Maintain consistent formatting
4. Mark incomplete sections appropriately
5. Clean up temporary files after conversion

## 🏢 About Mosaic Design System

The Mosaic Design System (MDS) is a comprehensive design system that provides a consistent framework for building user interfaces across applications.

---

**Note:** This repository contains structured markdown specifications derived from official MDS documentation. Always refer to these specs as the source of truth for component behavior, pattern usage, and layout structures.
