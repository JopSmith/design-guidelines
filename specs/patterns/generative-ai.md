# UI Pattern Spec (LLM-Friendly Template)

## 1. Pattern Name
Generative AI

---

## 2. Intent (Why this exists)
Generative AI patterns define how AI-driven features are presented and interacted with across an interface. They focus on ensuring transparency, clarity, and consistency, helping users understand when content is AI-generated, how it was produced, and what role the user plays in the interaction.

Use generative AI patterns in any experience where AI creates, modifies, or suggests content. These patterns should make AI involvement explicit, provide appropriate context, and support user control and understanding. They are essential in building trust, especially in scenarios where outputs may influence decisions, workflows, or user-generated content.

---

## 3. Context of Use
- Use when:
  - AI creates content
  - AI modifies content
  - AI suggests content
  - AI involvement needs to be explicit
  - Outputs may influence decisions, workflows, or user-generated content
- Avoid when:
  - AI usage is hidden
  - AI behaviour is unclear or lacks context

---

## 4. Core Behaviour (How it works)
- Trigger:
  - AIButton component triggers AI action
- System Response:
  - AI generation begins
  - Relevant component transitions into AI Aura styling
  - AILabel identifies AI-generated content or action
- Ongoing Behavior:
  - AI Aura styling indicates active AI generation
  - AILabel provides explainability via popover
  - Users can review, edit, or refine AI outputs
- Exit Condition:
  - AI generation completes
  - Content becomes editable
  - User may modify or accept output

---

## 5. Rules & Constraints
- MUST:
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
- SHOULD:
  - Provide context for how AI generates content
  - Support user understanding of AI role
- MUST NOT:
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

---

## 6. Variants
- Input-Level: When AI generation occurs within a single input → behaviour applies inside Textarea or InputText
- Form-Level: When AI generation occurs across a structured form → behaviour applies within a Dialog

---

## 7. Examples (Abstract, not visual)
- User clicks AIButton under a Textarea
- System applies AI Aura styling to Textarea
- AI generates draft content inside Textarea
- AILabel appears near form label with explainability popover
- User edits generated content

- User clicks AIButton to open Dialog
- Dialog opens with AI Aura styling
- AI generates structured content inside Dialog
- AILabel appears near Dialog title with explainability popover
- User reviews and edits generated content

---

## 8. Rationale (Why it works)
- Ensures transparency by clearly labelling AI-generated content
- Builds trust by explaining how AI works
- Supports user control by allowing editing and refinement
- Maintains consistency through standardised components and visual cues
- Reduces confusion by keeping AI context within the interaction

---

## 9. Trade-offs
- Pros:
  - Builds trust through transparency
  - Improves user understanding of AI behaviour
  - Supports user control over outputs
- Cons:
  - Additional UI elements may increase interface complexity
  - Overuse of AI indicators may create visual noise

---

## 10. Related Components
- AILabel
- AIButton
- Textarea
- InputText
- Dialog

---

## 11. Related Patterns
- Explainability
- Content Editing
- Feedback Patterns