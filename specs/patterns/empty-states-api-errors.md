# Empty States (API Errors)

## 1. Description

API error empty state patterns are used when communication between the client and server fails, preventing data from being loaded or actions from completing. They inform users of issues such as downtime, unauthorised access, or gateway errors, helping clarify that the problem is system-related rather than user-driven.

## 2. Usage

Use API error empty states when a request fails and content cannot be displayed, such as during network issues, server errors, or permission failures. They should reassure users, explain the issue at an appropriate level, and provide a clear recovery path where possible, such as retrying or checking access.

### Do

- Clearly communicate that something went wrong with the system
- Use simple, human-readable language to describe the problem
- Provide a clear recovery action, such as retrying the request
- Indicate whether the issue is temporary or may require action
- Use consistent patterns via the EmptyState component
- Log or handle technical details behind the scenes

### Don't

- Blame the user or imply they caused the issue
- Expose raw technical error messages (e.g. stack traces)
- Leave users without a way to proceed
- Give no indication of what users should expect
- Create inconsistent or ad hoc error states
- Rely on users to interpret technical error codes like "502 Bad Gateway"

## 3. Types

Each variant below defines a specific technical error, tone, and recommended action.

### 3.1 Bad Gateway

| Element | Specification |
|---------|---------------|
| **Purpose** | Indicates that the server received an invalid response from an upstream service. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/cloud_connection.svg |
| **Title** | "Bad gateway" |
| **Subtitle** | "Something went wrong while connecting to the server. Please try again later." |
| **Button** | "Back" (Outline) |
| **Tone** | Neutral and factual. Avoid technical jargon. |
| **Use case** | HTTP 502 gateway failure or temporary routing issue. |

### 3.2 Service Unavailable

| Element | Specification |
|---------|---------------|
| **Purpose** | The service is temporarily unavailable due to overload or maintenance. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/unavailable.svg |
| **Title** | "Service unavailable" |
| **Subtitle** | "The service is currently unavailable. Please try again in a few minutes." |
| **Button** | "Back" (Outline) |
| **Tone** | Calm and reassuring. |
| **Use case** | HTTP 503 service downtime or high-load response. |

### 3.3 Offline

| Element | Specification |
|---------|---------------|
| **Purpose** | The client device has lost internet connection. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/sad_cloud.svg |
| **Title** | "You're offline" |
| **Subtitle** | "Check your connection and try again once you're back online." |
| **Button** | "Back" (Outline) |
| **Tone** | Supportive and friendly. |
| **Use case** | Displayed when the browser or app detects no network connectivity. |

### 3.4 Gateway Timeout

| Element | Specification |
|---------|---------------|
| **Purpose** | The server took too long to respond to the request. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/sand_timer.svg |
| **Title** | "Connection timed out" |
| **Subtitle** | "The request took too long to complete. Please try again." |
| **Button** | "Back" (Outline) |
| **Tone** | Reassuring and patient. |
| **Use case** | HTTP 504 timeout errors or slow server responses. |

### 3.5 Server Error

| Element | Specification |
|---------|---------------|
| **Purpose** | Indicates a general internal server error. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/error_cloud.svg |
| **Title** | "Server error" |
| **Subtitle** | "An unexpected error occurred on our end. Please try again later." |
| **Button** | "Back" (Outline) |
| **Tone** | Honest but calm. Avoid blaming the user or exposing technical detail. |
| **Use case** | HTTP 500-level general errors or unknown exceptions. |

### 3.6 Unauthorised

| Element | Specification |
|---------|---------------|
| **Purpose** | The request was denied due to missing or invalid credentials. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/lock.svg |
| **Title** | "Unauthorised" |
| **Subtitle** | "Your session may have expired. Please sign in again to continue." |
| **Button** | "Back" (Outline) |
| **Tone** | Clear and procedural. |
| **Use case** | HTTP 401 unauthorised responses or expired tokens. |

### 3.7 General Error

| Element | Specification |
|---------|---------------|
| **Purpose** | Used as a fallback when the cause of the error is unknown. |
| **Icon** | https://cdn.svc.oneadvanced.com/mosaic-icons/svg/fluency-color/error.svg |
| **Title** | "Something went wrong" |
| **Subtitle** | "An unexpected error occurred. Please refresh or try again later." |
| **Button** | "Back" (Outline) |
| **Tone** | Neutral, simple, and apologetic without overexplaining. |
| **Use case** | Fallback for unhandled or ambiguous error responses. |
