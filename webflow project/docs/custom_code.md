## Custom Code: AG Automation Webflow Site

This document serves as a record for any custom HTML, CSS, or JavaScript code embedded within the AG Automation Webflow site. Custom code is utilized to extend Webflow's native capabilities, implement dynamic features, and integrate with external services at the Application Layer (L7).

**Current Custom Code:**

*   No custom scripts are currently registered on the site.

**Guidelines for Adding Custom Code:**

1.  **Purpose:** Clearly define the objective and functionality of the custom code.
2.  **Location:** Specify where the code is embedded (e.g., page header, page footer, site-wide header, site-wide footer, HTML Embed element).
3.  **Language:** Indicate the language used (HTML, CSS, JavaScript).
4.  **Dependencies:** List any external libraries, APIs, or services that the custom code relies on.
5.  **Functionality:** Describe what the code does in detail, including any event listeners, data manipulations, or API calls.
6.  **Maintainability:** Ensure the code is well-commented, readable, and follows best practices for the respective language.
7.  **Performance:** Optimize custom code for performance to avoid negatively impacting page load times and user experience.
8.  **Security:** Adhere to security best practices, especially when handling sensitive data or interacting with external APIs.
9.  **Testing:** Thoroughly test custom code across different browsers and devices to ensure functionality and prevent conflicts.

**Example Structure for Documenting Custom Code:**

```markdown
### [Descriptive Name of Custom Code]

**Purpose:** [Brief explanation of what the code achieves]

**Location:** [e.g., Site-wide footer, Home page header, specific HTML Embed element on 'Contact Us' page]

**Language:** JavaScript

**Dependencies:** [e.g., jQuery, external API endpoint: https://api.example.com/data]

**Code Snippet:**
```javascript
// Your custom JavaScript code here
console.log('Custom code executed!');
```

**Functionality Details:**
*   [Explain step-by-step what the code does]
*   [Describe any triggers or events that activate the code]
*   [Mention any data manipulation or UI changes]

**Notes/Considerations:**
*   [Any important notes, potential conflicts, or future improvements]
```
