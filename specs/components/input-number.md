# InputNumber

## 1. Description

An InputNumber is a numeric input control that allows users to type a value manually or modify it using stepper controls such as increase and decrease buttons. It is designed for entering structured numeric data where values may be limited by defined rules or ranges, such as quantities, counts, percentages, or threshold values.

## 2. Usage

### When to Use

Use an InputNumber when users need to enter whole numbers or fixed numeric increments within a controlled range. It is particularly appropriate when validation, minimum and maximum limits, or precise step adjustments are required to prevent invalid input.

### Do
- Use an InputNumber when values must be numeric and constrained within a defined range
- Set clear minimum, maximum, and step values where appropriate
- Ensure increment and decrease controls are easy to use and clearly visible
- Match the step value to the expected precision such as whole numbers or fixed increments
- Provide clear validation and feedback for invalid entries
- Ensure accessibility through keyboard input and focus support
- Disable the relevant arrow button if the min or max is reached

### Don't
- Use a generic text input for structured numeric data
- Allow unrestricted input when limits are required
- Make stepper controls too small or difficult to interact with
- Use inappropriate step intervals that confuse users
- Silently correct or reject values without explanation
- Rely solely on mouse interaction for adjusting values
- Let users click "+" above the max or "–" below the min with no feedback

## 3. Composition

**Status:** Not documented in source material

## 4. States

**Status:** Not documented in source material
