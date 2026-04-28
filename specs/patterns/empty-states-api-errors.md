# UI Pattern Spec (LLM-Friendly Template)

## 1. Pattern Name
Empty States (API Errors)

---

## 2. Intent (Why this exists)
API error empty state patterns are used when communication between the client and server fails, preventing data from being loaded or actions from completing. They inform users of issues such as downtime, unauthorised access, or gateway errors, helping clarify that the problem is system-related rather than user-driven.

---

## 3. Context of Use
- Use when:
  - A request fails and content cannot be displayed
  - Network issues occur
  - Server errors occur
  - Permission failures occur
- Avoid when:
  - Not specified in source

---

## 4. Core Behaviour (How it works)
- Trigger:
  - A request fails due to API or network-related issues
- System Response:
  - Display an API error empty state
  - Inform the user that the issue is system-related
  - Explain the issue at an appropriate level
- Ongoing Behavior:
  - Reassure users
  - Provide guidance on what to do next
- Exit Condition:
  - User retries the action
  - User checks access or connection
  - Issue is resolved and content can load

---

## 5. Rules & Constraints
- MUST:
  - Clearly communicate that something went wrong with the system
  - Use simple, human-readable language to describe the problem
  - Provide a clear recovery action, such as retrying the request
  - Indicate whether the issue is temporary or may require action
  - Use consistent patterns via the EmptyState component
  - Log or handle technical details behind the scenes
- SHOULD:
  - Not specified in source
- MUST NOT:
  - Blame the user or imply they caused the issue
  - Expose raw technical error messages (e.g. stack traces)
  - Leave users without a way to proceed
  - Give no indication of what users should expect
  - Create inconsistent or ad hoc error states
  - Rely on users to interpret technical error codes like "502 Bad Gateway"

---

## 6. Variants
- Bad Gateway:
  - Purpose: Indicates that the server received an invalid response from an upstream service.
  - Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/cloud_connection.svg
  - Title: "Bad gateway"
  - Subtitle: "Something went wrong while connecting to the server. Please try again later."
  - Button: "Back" (Outline)
  - Tone: Neutral and factual. Avoid technical jargon.
  - Use case: HTTP 502 gateway failure or temporary routing issue.

- Service Unavailable:
  - Purpose: The service is temporarily unavailable due to overload or maintenance.
  - Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/unavailable.svg
  - Title: "Service unavailable"
  - Subtitle: "The service is currently unavailable. Please try again in a few minutes."
  - Button: "Back" (Outline)
  - Tone: Calm and reassuring.
  - Use case: HTTP 503 service downtime or high-load response.

- Offline:
  - Purpose: The client device has lost internet connection.
  - Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/sad_cloud.svg
  - Title: "You're offline"
  - Subtitle: "Check your connection and try again once you're back online."
  - Button: "Back" (Outline)
  - Tone: Supportive and friendly.
  - Use case: Displayed when the browser or app detects no network connectivity.

- Gateway Timeout:
  - Purpose: The server took too long to respond to the request.
  - Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/sand_timer.svg
  - Title: "Connection timed out"
  - Subtitle: "The request took too long to complete. Please try again."
  - Button: "Back" (Outline)
  - Tone: Reassuring and patient.
  - Use case: HTTP 504 timeout errors or slow server responses.

- Server Error:
  - Purpose: Indicates a general internal server error.
  - Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/error_cloud.svg
  - Title: "Server error"
  - Subtitle: "An unexpected error occurred on our end. Please try again later."
  - Button: "Back" (Outline)
  - Tone: Honest but calm. Avoid blaming the user or exposing technical detail.
  - Use case: HTTP 500-level general errors or unknown exceptions.

- Unauthorised:
  - Purpose: The request was denied due to missing or invalid credentials.
  - Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/lock.svg
  - Title: "Unauthorised"
  - Subtitle: "Your session may have expired. Please sign in again to continue."
  - Button: "Back" (Outline)
  - Tone: Clear and procedural.
  - Use case: HTTP 401 unauthorised responses or expired tokens.

- General Error:
  - Purpose: Used as a fallback when the cause of the error is unknown.
  - Icon: https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/error.svg
  - Title: "Something went wrong"
  - Subtitle: "An unexpected error occurred. Please refresh or try again later."
  - Button: "Back" (Outline)
  - Tone: Neutral, simple, and apologetic without overexplaining.
  - Use case: Fallback for unhandled or ambiguous error responses.

---

## 7. Examples (Abstract, not visual)
- A network request fails
- System shows an API error empty state
- User sees explanation of the issue
- User is given a recovery action such as retrying or checking access

---

## 8. Rationale (Why it works)
- Helps clarify that the problem is system-related rather than user-driven
- Reassures users during failure states
- Provides clear recovery paths such as retrying or checking access

---

## 9. Trade-offs
- Pros:
  - Provides clarity during system failures
  - Helps users recover from errors
- Cons:
  - Not specified in source

---

## 10. Related Components
- EmptyState component

---

## 11. Related Patterns
- Not specified in source
