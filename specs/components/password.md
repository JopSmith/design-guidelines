# Password

## 1. Description

A Password component is a form field used to securely capture a user's password. It functions like a standard text input but masks entered characters by default to protect sensitive information. The component may include optional features such as a visibility toggle, password strength indicators, or guidance messaging that outlines requirements such as length or complexity.

## 2. Usage

### When to Use

Use a Password component whenever users must create, confirm, or enter a secure credential, such as during sign-in, account registration, or password reset flows. It is particularly important when validation rules must be communicated clearly to help users meet security requirements while maintaining a smooth and secure experience.

### Do
- Use the Password component whenever a user must create, update, or confirm credentials
- Show clear requirements before the user submits the form
- Provide an accessible show/hide password control to reduce entry errors
- Mark required fields clearly and consistently
- Use helper text for strength guidance or security hints
- Use consistent error styling if validation fails

### Don't
- Use a generic text input for password entry
- Wait until after submission to indicate the password is invalid
- Force masking only, particularly on mobile devices
- Rely solely on placeholder text instead of a visible label
- Expose sensitive information such as a user's current password
- Change layout between states in a way that causes the field to shift unexpectedly

## 3. Composition

The Password consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Mask | Optional | Masks entered characters to protect sensitive information, with an optional control to toggle visibility |
| Meter | Optional | Visually indicates the strength of the entered password based on defined security criteria |

## 4. States

**Status:** Not documented in source material
