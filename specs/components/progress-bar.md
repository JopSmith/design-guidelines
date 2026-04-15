# ProgressBar

## 1. Description

A ProgressBar visually communicates the completion status of an operation or process. It displays progress as a filled portion of a horizontal bar, indicating how much of the task has been completed and how much remains. A ProgressBar reassures users that the system is active and provides a clear sense of advancement towards completion.

## 2. Usage

### When to Use

Use a ProgressBar when an action takes noticeable time to complete, such as file uploads, form submissions, data processing, or system updates. It is particularly helpful for long-running operations where visibility of progress reduces uncertainty and improves user confidence in the system.

### Do
- Use for operations with visible progress such as uploads, saves, or updates
- Use determinate bars when progress can be measured from zero to one hundred percent
- Use indeterminate bars when progress cannot be tracked
- Place the ProgressBar beneath or near the process being tracked
- Use ProgressBars sparingly to maintain perceived performance
- Ensure progress feedback aligns with actual system behaviour

### Don't
- Show a ProgressBar for tasks under ten seconds — use a Spinner instead
- Show determinate bars when duration cannot be estimated
- Leave users uncertain whether the system is working
- Position it far from the relevant context
- Overuse them for small or frequent actions
- Display misleading or inaccurate progress indicators

## 3. Composition

The ProgressBar consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Title | Optional | Displays a clear label describing the task or process being tracked |
| Subtitle | Optional | Provides supporting context or secondary information about the operation |
| Percentage complete | Optional | Shows the numeric progress value to indicate how much of the task has been completed |
| Description | Optional | Offers additional detail about the current state or next steps in the process |

## 4. States

**Status:** Not documented in source material
