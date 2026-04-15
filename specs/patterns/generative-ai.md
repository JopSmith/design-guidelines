# Generative AI

## 1. Description

Generative AI patterns define how AI-driven features are presented and interacted with across an interface. They focus on ensuring transparency, clarity, and consistency, helping users understand when content is AI-generated, how it was produced, and what role the user plays in the interaction.

## 2. Usage

Use generative AI patterns in any experience where AI creates, modifies, or suggests content. These patterns should make AI involvement explicit, provide appropriate context, and support user control and understanding. They are essential in building trust, especially in scenarios where outputs may influence decisions, workflows, or user-generated content.

### Do

- Always use the AILabel component to identify AI-generated content or actions
- Provide quick, in-context explanations via the explainability popover attached to the AILabel
- Use the AIButton component to trigger any AI action
- Use the AI Aura styling to indicate when AI is actively generating content
- Place the AILabel near the element it relates to
- Make AI-generated content editable after creation
- Use consistent visual cues and patterns for AI interactions
- Allow users to review, edit, or refine AI outputs
- Set appropriate expectations around accuracy and limitations
- Design for trust through transparency and clarity

### Don't

- Hide AI usage or generate content without clear labelling
- Require users to leave the current context to understand AI behaviour
- Repurpose standard buttons for AI generation
- Apply AI Aura visuals to non-AI components
- Separate the label far from the AI-triggered component
- Lock AI content without user control or feedback
- Introduce inconsistent or unclear AI indicators
- Treat AI outputs as final with no user control
- Imply AI outputs are always correct or authoritative
- Hide or obscure how AI contributes to the experience

## 3. Types

### 3.1 Input-Level

AI generation that occurs at input-level, e.g. generating draft feedback directly or summarising notes based on the user's written content in a Textarea.

| Element | Specification |
|---------|---------------|
| **Purpose** | To generate text or suggestions directly within a single input (e.g., Textarea or InputText). |
| **Trigger** | AIButton component placed beneath or adjacent to the Textarea. |
| **Context** | AIButton triggers content generation inside the Textarea. |
| **Behaviour** | When clicked, the Textarea transitions into the AI Aura style, indicating active AI generation. |
| **Label** | AILabel positioned adjacent to the form label, providing an explainability popover to describe the AI's function. |
| **Explainability** | The attached popover should briefly explain *why* or *how* AI is generating content (e.g., "This feedback draft was generated using AI based on your recent goals and comments."). |
| **Visual cue** | The AI Aura style provides soft gradients and border highlights to signify AI activity. |
| **Example** | Generating a feedback draft, creating a summary, or rewriting user text. |

### 3.2 Form-Level

AI generation that occurs at form-level, e.g. generating a structured meeting agenda or drafting a project brief in an entire Dialog.

| Element | Specification |
|---------|---------------|
| **Purpose** | To generate multiple pieces of content or a larger structured output within a form flow. |
| **Trigger** | AIButton component opens a Dialog that supports AI generation. |
| **Context** | The Dialog itself adopts the AI Aura styling once active. |
| **Label** | AILabel positioned adjacent to the Dialog title, providing explainability context. |
| **Behaviour** | While generating, the Dialog remains open and visually indicates AI activity (e.g., animated border, subtle glow). |
| **Explainability** | The AILabel's popover explains what the AI is doing and how the user can edit or reject the generated content. |
| **Example** | Generating a project brief, creating multiple task descriptions, or drafting structured form data. |
