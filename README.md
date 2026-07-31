# Design Guidelines

> Structured documentation for the IX made LLM-readable

## Overview

This repository contains comprehensive, structured documentation for design system components, patterns, and templates. The goal is to make design system knowledge accessible to AI assistants so they can help developers build IX-compliant applications.

## 📁 Repository Structure

```
design-guidelines/
├── specs/
│   ├── components/        # 94 component specifications
│   ├── patterns/          # 26 design pattern specifications
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

### Patterns (26 specs)
Interaction and UI patterns including:
- **Colour Indicators** - Status, priority, action, and charting colours
- **Context Panel** - Persistent conversation history and cross-session navigation
- **Contextual Indicators** - System action transparency during tool usage
- **Conversation Branching** - Alternative conversation path exploration
- **Conversation Memory Indicators** - Stored data awareness and user control
- **Conversation Starters** - Predefined prompts to reduce new-session friction
- **Editing Controls** - Modify or retry interactions in iterative workflows
- **Empty States** - 12 variants for different no-content scenarios
- **Empty States (API Errors)** - 7 API error states (502, 503, 504, 500, 401, offline, general)
- **Feedback Loop** - User feedback collection on system outputs
- **Follow-up Prompts** - Contextual suggestions to guide continued interaction
- **Generative AI** - AI interaction patterns with AILabel, AIButton, and AI Aura
- **Inline Actions** - Per-message controls (copy, edit, regenerate)
- **Inline Forms** - Structured input fields within conversation flow
- **Input Composer** - Multi-modal input area (text, voice, files, images, commands)
- **Instruction Banners** - Dynamic system capability and constraint communication
- **Message Bubbles** - Chronological, role-separated conversation structure
- **Modal Dialogs** - 4 focused overlay types (passive, transactional, acknowledgement, progress)
- **Mode Switcher** - System behaviour and role switching
- **Multi-Media Blocks** - Non-text input and output rendering
- **Non-Modal Dialogs** - 2 lightweight contextual overlays (passive, transactional)
- **Quick Reply Chips** - Predefined tappable response options
- **Rich Content Cards** - Structured data rendered as interactive cards
- **Social Media Interactions** - News and chat interaction actions (like, comment, save, copy)
- **Split View** - Simultaneous conversation and output display
- **Stateful Task Panel** - Multi-step task progress tracking
- **Typing Indicator** - Active response generation signal

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

When building with IX, always refer to the relevant specs:

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

## 🏢 About

This repository contains comprehensive documentation that provides a consistent framework for building user interfaces across applications.

---

**Note:** This repository contains structured markdown specifications derived from experience and best practice. Always refer to these specs as the source of truth for component behavior, pattern usage, and layout structures.
