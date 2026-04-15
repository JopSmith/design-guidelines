# ErrorCard

## 1. Description

An ErrorCard is a high-visibility message used to communicate that something has gone wrong and to guide the user towards recovery. It typically appears at page level or across the whole application, making the issue clear and prominent. An ErrorCard usually includes a concise explanation of the problem, relevant context where possible, and a clear action that helps the user resolve or move past the error.

## 2. Usage

### When to Use

Use an ErrorCard when a significant failure prevents the user from completing their task, such as a system error, failed data load, or permission issue. It is appropriate when the impact affects an entire page or core workflow and requires immediate attention, rather than being handled through inline validation or subtle messaging.

### Do
- Use an ErrorCard for significant issues that affect an entire page or core workflow
- Clearly explain what has gone wrong in plain language
- Provide a clear recovery action such as retry, refresh, or contact support
- Make the ErrorCard highly visible within the layout
- Keep the tone calm, supportive, and reassuring
- Include relevant context when available to help users understand the impact

### Don't
- Use an ErrorCard for minor or inline validation errors
- Use technical jargon or internal system codes
- Present an error without a path forward
- Allow the message to be overlooked or visually buried
- Assign blame to the user
- Overwhelm users with unnecessary detail or excessive information

## 3. Composition

The ErrorCard consists of the following accessories:

| Accessory | Required | Description |
|---|---|---|
| Logo | Optional | Displays the brand logo for when an error is shown outside the core app, i.e. when there's a serious error and no other branding is present |

## 4. States

**Status:** Not documented in source material
