# InputOTP

## 1. Description

An InputOTP is a specialised input control designed for entering a short verification code made up of numbers or characters. It often presents separate input fields for each digit or character, automatically advancing focus as the user types to create a smooth and guided experience. The component is commonly used as part of authentication or verification flows to confirm a user's identity.

## 2. Usage

### When to Use

Use an InputOTP component when users must enter a temporary verification code sent via text message, email, or authentication app. It is particularly appropriate in sign-in, account recovery, or sensitive action confirmation flows where an additional layer of security is required.

### Do
- Use an InputOTP for short verification codes required for authentication or confirmation
- Keep all boxes the same width so the user can instantly see how many characters are required
- Automatically move focus to the next field as users enter each character
- Support pasting a full code into the component
- Clearly indicate the number of characters required
- Provide clear error messaging for invalid or expired codes
- Ensure accessibility and keyboard support across all fields

### Don't
- Use a standard text input when a structured code entry experience is expected
- Mix different widths or allow the layout to break, which creates uncertainty
- Require users to manually select each field
- Block paste behaviour when users copy codes from messages or email
- Leave users guessing how many digits or characters to enter
- Silently reject incorrect entries
- Create focus traps or inconsistent tab behaviour

## 3. Composition

**Status:** Not documented in source material

## 4. States

**Status:** Not documented in source material
