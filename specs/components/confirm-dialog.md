# ConfirmDialog

## 1. Description

A ConfirmDialog is a specialised Dialog component used to confirm destructive, irreversible, or high-consequence actions. It builds on the standard Dialog pattern but has a focused purpose: to ensure users explicitly acknowledge the impact of an action before it proceeds.

## 2. Usage

### When to Use

Use a ConfirmDialog when an operation cannot be easily undone, affects important data, or carries meaningful risk. Unlike general Dialogs, ConfirmDialogs should be narrowly scoped, clearly describing the action and its consequences. They should interrupt the flow only when necessary, reinforcing the seriousness of the decision without overuse.

### Do
- Use a ConfirmDialog for destructive, irreversible, or high-impact actions
- Clearly describe what will happen if the user confirms
- Make the destructive action visually distinct
- Provide a clear cancel or safe exit option
- Keep the message concise and action-focused
- Require deliberate user intent before proceeding

### Don't
- Use a ConfirmDialog for informational or low-risk interactions
- Use generic or unclear confirmation messaging
- Style confirm and cancel actions the same
- Prevent users from backing out
- Add unnecessary detail or unrelated information
- Allow high-risk actions without explicit confirmation

## 3. Composition

**Status:** Not documented in source material

## 4. States

**Status:** Not documented in source material
