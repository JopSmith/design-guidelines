# UI Pattern Spec (LLM-Friendly Template)

## 1. Pattern Name
Empty States

---

## 2. Intent (Why this exists)
Empty state patterns communicate that no content, data, or configuration is currently available within a given context. They help users understand why nothing is shown and provide clarity on the current state, whether it's due to no results, missing setup, or restricted access.

---

## 3. Context of Use
- Use when:
  - A view has no content to display
  - First-time use
  - Empty lists
  - Filtered results
  - Error states
  - Permission states
- Avoid when:
  - The view contains content

---

## 4. Core Behaviour (How it works)
- Trigger:
  - A view has no content, data, or configuration available

- System Response:
  - Display an empty state pattern
  - Explain why the state is empty
  - Provide a next step or call to action

- Ongoing Behavior:
  - Maintain clarity on the current state
  - Guide users toward next steps (e.g. creating content, adjusting filters, resolving issues)

- Exit Condition:
  - Content becomes available
  - User completes the suggested action (e.g. adds data, adjusts filters, resolves issue)

---

## 5. Rules & Constraints

- MUST:
  - Clearly explain why the state is empty
  - Provide a clear next step or call to action
  - Tailor the message to the specific scenario (e.g. no data, no results, error)
  - Maintain consistency with the EmptyState component

- SHOULD:
  - Use supportive visuals or illustrations where appropriate
  - Keep messaging concise and easy to understand

- MUST NOT:
  - Leave users wondering why no content is shown
  - Present an empty state with no guidance
  - Use generic messaging for all empty states
  - Overload the state with unnecessary graphics
  - Use long or overly complex explanations
  - Create inconsistent or one-off empty state designs

---

## 6. Variants

### Variant: No Records
- Purpose: Shown when a dataset (e.g. table or list) has no items yet.
- Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/empty_folder.svg
- Title: "No records found"
- Subtitle: "There are no records to display. Create a new record to get started."
- Button: "Add record" (Outline)
- Tone: Encouraging and neutral.
- Use case: Data table or module that's been initialized but is empty.

### Variant: No Tasks
- Purpose: Displayed when a task list or queue is empty.
- Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/empty_folder.svg
- Title: "No tasks yet"
- Subtitle: "You haven't created any tasks. Start by adding one below."
- Button: "Add task" (Outline)
- Tone: Supportive and productive.
- Use case: To-do, workflow, or task dashboards with no entries.

### Variant: No Results
- Purpose: Used when search or filters return zero matches.
- Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/empty_folder.svg
- Title: "No results"
- Subtitle: "Try adjusting your filters or search terms."
- Button: "Clear filters" (Outline)
- Tone: Reassuring; helps users recover easily.
- Use case: Search views or filtered datasets.

### Variant: System Maintenance
- Purpose: Indicates that the system is undergoing planned updates.
- Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/maintenance.svg
- Title: "System under maintenance"
- Subtitle: "We're performing scheduled maintenance to improve your experience. Please check back soon."
- Button: "Retry" (Outline)
- Tone: Calm, transparent, and professional.
- Use case: Displayed globally during maintenance windows.

### Variant: Loading
- Purpose: Temporarily displayed while content is loading.
- Icon: Animated spinner https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-outline/spinner.svg
- Title: "Loading…"
- Subtitle: "Please wait while we prepare your data."
- Button: None
- Tone: Neutral and patient.
- Use case: While waiting for content or network responses.
- Behaviour: Automatically replaced by content once loaded.

### Variant: Connection Error
- Purpose: Indicates network or service connection failure.
- Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/error.svg
- Title: "Connection error"
- Subtitle: "We're having trouble connecting right now. Check your network and try again."
- Button: "Retry" (Outline)
- Tone: Reassuring; avoid implying user fault.
- Use case: Offline or failed API calls.

### Variant: Unverified Account
- Purpose: Shown when a user's account needs email or identity verification.
- Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/unverified_account.svg
- Title: "Account not verified"
- Subtitle: "Please verify your account to access this feature."
- Button: "Check permissions" (Outline)
- Tone: Supportive and instructional.
- Use case: User registration or onboarding flows.

### Variant: Access Denied
- Purpose: The user lacks permission to view or edit this content.
- Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/access_denied.svg
- Title: "Access denied"
- Subtitle: "You don't have permission to view this page. Contact your administrator."
- Button: "Request permission" (Outline)
- Tone: Neutral and polite — never accusatory.
- Use case: Permission or role-based access restrictions.

### Variant: Config Expired
- Purpose: Indicates a system or integration configuration is outdated.
- Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/settings.svg
- Title: "Configuration expired"
- Subtitle: "Your configuration settings have expired. Please refresh or update them."
- Button: "Edit properties" (Outline)
- Tone: Informative and actionable.
- Use case: Timed credentials or integration tokens.

### Variant: No Config
- Purpose: Displayed when required configuration has not been set up.
- Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/settings.svg
- Title: "No configuration found"
- Subtitle: "It looks like this feature hasn't been set up yet."
- Button: "Configure" (Outline)
- Tone: Encouraging and helpful.
- Use case: Empty integrations or initial setup states.

### Variant: No Authorisation
- Purpose: Appears when authentication is missing or invalid.
- Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/disconnected.svg
- Title: "Not authorised"
- Subtitle: "You need to sign in or reauthenticate to continue."
- Button: "Log in" (Outline)
- Tone: Clear and procedural.
- Use case: Session timeout or invalid credentials.

### Variant: Admin Config Required
- Purpose: Indicates that an administrator must configure a system before users can proceed.
- Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/cloud_cross.svg
- Title: "Configuration required"
- Subtitle: "This area can't be used until an administrator completes setup."
- Button: "Send email" (Outline)
- Tone: Directive and neutral.
- Use case: Access dependent on admin-defined system setup.

---

## 7. Examples (Abstract, not visual)

- First-time use:
  - User opens a module with no data
  - System shows "No records found"
  - User clicks "Add record"

- Filtered results:
  - User applies filters
  - No matching data exists
  - System shows "No results"
  - User clicks "Clear filters"

- Connection issue:
  - System fails to load data
  - System shows "Connection error"
  - User clicks "Retry"

- Loading:
  - User opens a page
  - System shows "Loading…"
  - Content replaces state once ready

---

## 8. Rationale (Why it works)

- Reduces uncertainty by explaining why nothing is shown  
- Guides users toward next steps  
- Maintains clarity in different system states  
- Provides feedback during loading, errors, and empty data conditions  

---

## 9. Trade-offs

- Pros:
  - Improves clarity when no data is present
  - Helps users take action
  - Reduces confusion

- Cons:
  - Can become repetitive if not tailored to context
  - Overuse of visuals can clutter the interface

---

## 10. Related Components

- Button  
- EmptyState component  

---

## 11. Related Patterns

- Error states  
- Loading states  
- Permission states  
