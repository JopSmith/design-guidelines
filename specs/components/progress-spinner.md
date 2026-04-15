# ProgressSpinner

## 1. Description

A ProgressSpinner is an animated visual indicator that signals a process is taking place in the background. Unlike a ProgressBar, it does not display a percentage or indicate how much of the task has been completed. Instead, it provides reassurance that the system is active and responding, helping to reduce uncertainty while users wait.

## 2. Usage

### When to Use

Use a ProgressSpinner when retrieving data or running calculations that take more than three seconds, when you need to reassure users that the interface has not frozen, or when showing temporary waiting states within components such as buttons or snackbars. Avoid using it for processes shorter than three seconds (creates unnecessary visual noise) or for processes longer than ten seconds where a ProgressBar is more appropriate.

### Do
- Use for short waits where progress cannot be measured
- Keep sizes consistent across products such as 24px, 32px, 48px, and 64px
- Use the default colour unless embedded in a component
- Use contextual colour if the spinner is embedded in a component

### Don't
- Use for long waits greater than ten seconds
- Display spinners for every minor action as this adds friction
- Overuse colours inconsistently
- Show multiple spinners on the same element

## 3. Composition

The ProgressSpinner consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Label | Optional | An optional text label that reads "Loading…" — helps users understand what the spinner is doing |
| AI aura | Optional | An optional visual treatment that indicates AI is generating or processing content — differentiates AI-driven activity from standard system loading states |

## 4. States

**Status:** Not documented in source material
