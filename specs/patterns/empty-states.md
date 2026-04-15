# Empty States

## 1. Description

Empty state patterns communicate that no content, data, or configuration is currently available within a given context. They help users understand why nothing is shown and provide clarity on the current state, whether it's due to no results, missing setup, or restricted access.

## 2. Usage

Use empty state patterns whenever a view has no content to display, such as first-time use, empty lists, filtered results, or error or permission states. They should guide users toward the next step, whether that's creating content, adjusting filters, or resolving an issue, while maintaining clarity and reducing uncertainty.

### Do

- Clearly explain why the state is empty
- Provide a clear next step or call to action
- Tailor the message to the specific scenario (e.g. no data, no results, error)
- Use supportive visuals or illustrations where appropriate
- Keep messaging concise and easy to understand
- Maintain consistency with the EmptyState component

### Don't

- Leave users wondering why no content is shown
- Present an empty state with no guidance
- Use generic messaging for all empty states
- Overload the state with unnecessary graphics
- Use long or overly complex explanations
- Create inconsistent or one-off empty state designs

## 3. Types

Each variant below defines a specific context, tone, and recommended action.

### 3.1 No Records

| Element | Specification |
|---------|---------------|
| **Purpose** | Shown when a dataset (e.g. table or list) has no items yet. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/empty_folder.svg |
| **Title** | "No records found" |
| **Subtitle** | "There are no records to display. Create a new record to get started." |
| **Button** | "Add record" (Outline) |
| **Tone** | Encouraging and neutral. |
| **Use case** | Data table or module that's been initialized but is empty. |

### 3.2 No Tasks

| Element | Specification |
|---------|---------------|
| **Purpose** | Displayed when a task list or queue is empty. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/empty_folder.svg |
| **Title** | "No tasks yet" |
| **Subtitle** | "You haven't created any tasks. Start by adding one below." |
| **Button** | "Add task" (Outline) |
| **Tone** | Supportive and productive. |
| **Use case** | To-do, workflow, or task dashboards with no entries. |

### 3.3 No Results

| Element | Specification |
|---------|---------------|
| **Purpose** | Used when search or filters return zero matches. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/empty_folder.svg |
| **Title** | "No results" |
| **Subtitle** | "Try adjusting your filters or search terms." |
| **Button** | "Clear filters" (Outline) |
| **Tone** | Reassuring; helps users recover easily. |
| **Use case** | Search views or filtered datasets. |

### 3.4 System Maintenance

| Element | Specification |
|---------|---------------|
| **Purpose** | Indicates that the system is undergoing planned updates. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/maintenance.svg |
| **Title** | "System under maintenance" |
| **Subtitle** | "We're performing scheduled maintenance to improve your experience. Please check back soon." |
| **Button** | "Retry" (Outline) |
| **Tone** | Calm, transparent, and professional. |
| **Use case** | Displayed globally during maintenance windows. |

### 3.5 Loading

| Element | Specification |
|---------|---------------|
| **Purpose** | Temporarily displayed while content is loading. |
| **Icon** | Animated spinner https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-outline/spinner.svg |
| **Title** | "Loading…" |
| **Subtitle** | "Please wait while we prepare your data." |
| **Button** | None |
| **Tone** | Neutral and patient. |
| **Use case** | While waiting for content or network responses. |
| **Behaviour** | Automatically replaced by content once loaded. |

### 3.6 Connection Error

| Element | Specification |
|---------|---------------|
| **Purpose** | Indicates network or service connection failure. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/error.svg |
| **Title** | "Connection error" |
| **Subtitle** | "We're having trouble connecting right now. Check your network and try again." |
| **Button** | "Retry" (Outline) |
| **Tone** | Reassuring; avoid implying user fault. |
| **Use case** | Offline or failed API calls. |

### 3.7 Unverified Account

| Element | Specification |
|---------|---------------|
| **Purpose** | Shown when a user's account needs email or identity verification. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/unverified_account.svg |
| **Title** | "Account not verified" |
| **Subtitle** | "Please verify your account to access this feature." |
| **Button** | "Check permissions" (Outline) |
| **Tone** | Supportive and instructional. |
| **Use case** | User registration or onboarding flows. |

### 3.8 Access Denied

| Element | Specification |
|---------|---------------|
| **Purpose** | The user lacks permission to view or edit this content. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/access_denied.svg |
| **Title** | "Access denied" |
| **Subtitle** | "You don't have permission to view this page. Contact your administrator." |
| **Button** | "Request permission" (Outline) |
| **Tone** | Neutral and polite — never accusatory. |
| **Use case** | Permission or role-based access restrictions. |

### 3.9 Config Expired

| Element | Specification |
|---------|---------------|
| **Purpose** | Indicates a system or integration configuration is outdated. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/settings.svg |
| **Title** | "Configuration expired" |
| **Subtitle** | "Your configuration settings have expired. Please refresh or update them." |
| **Button** | "Edit properties" (Outline) |
| **Tone** | Informative and actionable. |
| **Use case** | Timed credentials or integration tokens. |

### 3.10 No Config

| Element | Specification |
|---------|---------------|
| **Purpose** | Displayed when required configuration has not been set up. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/settings.svg |
| **Title** | "No configuration found" |
| **Subtitle** | "It looks like this feature hasn't been set up yet." |
| **Button** | "Configure" (Outline) |
| **Tone** | Encouraging and helpful. |
| **Use case** | Empty integrations or initial setup states. |

### 3.11 No Authorisation

| Element | Specification |
|---------|---------------|
| **Purpose** | Appears when authentication is missing or invalid. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/disconnected.svg |
| **Title** | "Not authorised" |
| **Subtitle** | "You need to sign in or reauthenticate to continue." |
| **Button** | "Log in" (Outline) |
| **Tone** | Clear and procedural. |
| **Use case** | Session timeout or invalid credentials. |

### 3.12 Admin Config Required

| Element | Specification |
|---------|---------------|
| **Purpose** | Indicates that an administrator must configure a system before users can proceed. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/cloud_cross.svg |
| **Title** | "Configuration required" |
| **Subtitle** | "This area can't be used until an administrator completes setup." |
| **Button** | "Send email" (Outline) |
| **Tone** | Directive and neutral. |
| **Use case** | Access dependent on admin-defined system setup. |
