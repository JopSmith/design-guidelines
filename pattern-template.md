# Pattern Name
Short, unique, descriptive
- Example: Empty State, Inline Validation, Progressive Disclosure

## 1. Intent (Why this exists)
1–3 sentences max
- What problem this pattern solves
- When it should be used

Focus on user need + system goal

## 2. Context of Use
When to apply vs not apply
- Use when:
  - Condition A
  - Condition B
- Avoid when:
  - Condition X

This helps an LLM decide applicability instead of guessing.

## 3. Core Behaviour (How it works)
Describe the logic step-by-step.
- Trigger: What starts the pattern?
- System Response: What happens immediately?
- Ongoing Behavior: What updates over time?
- Exit Condition: When does it stop?

Keep this procedural, almost like pseudocode.

## 4. Rules & Constraints
Clear, testable rules.
- MUST:
  - Rule 1
  - Rule 2
- SHOULD:
  - Guideline 1
- MUST NOT:
  - Anti-patterns

Avoid vague terms like “nice,” “intuitive,” etc.

## 5. Variants
Only include if behaviour meaningfully changes.
- Variant A: When X → Behaviour changes to Y
- Variant B: When Z → Behaviour changes to W

## 6. Examples (Abstract, not visual)
Use simple text scenarios, not design mockups.
Can show references to images, e.g. state specific icons or illustrations.

Example:
- User submits empty form
- System shows inline error immediately
- Error disappears once corrected

This is critical for LLMs—they learn from interaction flows, not visuals.

## 7. Rationale (Why it works)
Explain underlying principles:
- Reduces cognitive load
- Prevents user error early
- Aligns with feedback loops

This helps LLMs generalise beyond the exact pattern.

## 8. Trade-offs
Be explicit.
- Pros:
  - Faster feedback
- Cons:
  - Can feel intrusive if overused

## 9. Related Components
Link conceptually, not visually, e.g:
- Button
- Dialog
- Input

## 10. Related Patterns
Link conceptually, not visually, e.g:
- Form Validation
- Error Messaging
- Progressive Disclosure

## Key Principles for LLM Readability
- Use consistent headings across all specs (critical)
- Prefer bullets over paragraphs
- Avoid synonyms (pick one term and stick to it)
- Make cause → effect explicit
- Separate rules from explanation
- Keep each section short and atomic

## What to Avoid
- Visual descriptions (“blue button on the right”)
- Brand/style language
- Long narrative explanations
- Mixed concerns (don’t combine behavior + rationale in one section)
- Implicit assumptions

## One-line summary
A good LLM-friendly UI pattern spec is:

A structured, rule-based description of when and how a pattern works, plus why it exists—without relying on visuals.