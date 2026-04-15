# Slider

## 1. Description

A Slider component allows users to select a numeric value or range within a defined scale by moving a handle along a horizontal track. It provides immediate visual feedback, showing the current value in relation to its minimum and maximum limits. Sliders make proportions and relative position easy to understand at a glance, particularly when interacting through touch.

## 2. Usage

### When to Use

Use a Slider when approximate precision is acceptable and when visualising proportion enhances understanding, such as for volume, percentages, pricing ranges, or thresholds. It is especially effective on touch devices where dragging is quicker than typing. Avoid using a Slider when exact numeric input is required or when the range is too large to control comfortably through a single continuous scale.

### Do
- Use a Slider when users need to select from a continuous or evenly spaced range such as 0 to 100
- Use when visualising magnitude or proportion is helpful such as intensity, opacity, or price range
- Show minimum and maximum values for context when appropriate
- Ensure the track and handle have clear contrast and sufficient size for touch
- Combine with an input field when exact values need fine adjustment

### Don't
- Use when exact numeric input is required — use a numeric input field instead
- Use for categorical values — use radio buttons or a Select component instead
- Omit value indicators entirely so users lose reference points
- Make the handle too small to grasp or the track too thin to see
- Use sliders where keyboard-only users cannot reach or adjust them

## 3. Composition

The Slider consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Labels | Optional | Optional labels displayed at either end of the track, such as 0 and 100, to clarify the minimum and maximum values and provide context for the selected position |
| Input | Optional | An optional numeric input field attached to the Slider that allows users to enter a precise value manually, supporting fine adjustment alongside drag interaction |

## 4. States

**Status:** Not documented in source material
