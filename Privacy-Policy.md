### Privacy Policy for ApplyEdge

**Effective Date:** Nov 28th, 2024

---

### Introduction
ApplyEdge is a Chrome browser extension designed to simplify the process of crafting tailored job applications, empowering users with best-in-class AI tools to create resumes and cover letters. Your data security and privacy are our utmost priority. We have designed ApplyEdge to ensure that sensitive data stays securely in your control and is never shared with anyone unless absolutely necessary for the extension's core functions.

This privacy policy outlines what data ApplyEdge collects, how it is used, and how we ensure the security and privacy of your information.

---

### Data Collection and Usage
#### 1. **Data Stored Locally**
- **What We Store:**
  - **Your Input Data:** Resumes, cover letters, LinkedIn information, career-related documents, and other content you manually upload or enter into the extension.
  - **Configuration Data:** Custom prompts, API keys for Large Language Models (LLMs) like OpenAI, Anthropic, and Gemini.
  - **Generated Content:** Generated resumes, cover letters, and research outputs for your job applications.
  - **User Settings and Preferences:** Settings related to API configurations and customization of your workflow.

- **How It’s Stored:**
  - All your input, generated content, and settings are stored **locally on your device** in an encrypted format using **state-of-the-art AES-GCM encryption**. ApplyEdge generates and stores encryption keys locally; these keys are never transmitted or accessible to us.

- **What This Means:**
  - **We do not store or access your data.** Everything related to your job applications stays on your browser unless you choose to send data to an external service (e.g., an LLM API).

---

#### 2. **External Services**
ApplyEdge interacts only with the services and third-party APIs you configure. Specifically:

##### a) **Large Language Models (LLMs)**
- **What Data Leaves Your Computer:**
  - The content necessary to generate resumes and cover letters, such as job descriptions or your career-related data.

- **Where This Data Goes:**
  - The AI APIs you configure (e.g., OpenAI, Anthropic, Gemini). The extension only sends data to the API services you explicitly provide during setup, and it does so securely.

- **Our Commitment:**
  - We do not store unencrypted API keys. Your keys are encrypted locally for all interactions with LLM APIs.

##### b) **Analytics via PostHog**
- **What We Track:**
  - **Anonymized Usage Metrics:** For example, tracking how often features are accessed, performance metrics, and general event data to help us improve the extension.
  - **What We Don’t Track:** PostHog never receives your personally identifiable information (PII), such as resumes, cover letters, LinkedIn data, API keys, or job descriptions.

- **External Privacy Policy:**
  - PostHog’s Privacy Policy is available [here](https://posthog.com/privacy).

---

### What ApplyEdge **Does Not** Do
We take pride in our secure and privacy-focused design:
- **No PII Collection:** We do not collect or transmit your personally identifiable information. Your resumes, cover letters, LinkedIn data, and other inputs remain encrypted and local to your browser.
- **No Remote Storage of Data:** We do not host any servers or databases. All processing either occurs in your browser or is securely transmitted to external APIs exclusively within the scope of your API configuration.
- **No Unauthorized Sharing:** We do not sell, rent, or share your data with any third party beyond what is essential for functionality and your explicit usage. We couldn't even if we wanted too - your data is encrypted, and more so, encrypted by your browser using a key we do not see.

---

### Data Security
- **Encryption:** All sensitive data stored locally in the browser is encrypted using **AES-GCM encryption**, ensuring that even if someone accessed your browser storage, the data would remain inaccessible. Nobody has access to the key - not us, or even the user, it is generated in the background by your browser
- **Limited Access:** Data is only decrypted temporarily to perform user-initiated tasks, such as sending prompts to an AI API. At no point do we (the developers) have access to your unencrypted data.

---

### Your Control and Rights
- **Full Control:** All data resides in your browser. You can remove it at any time by clearing the browser’s local data for the extension.
- **Data Management:**
  - Delete specific applications, resumes, or inputs via the extension’s settings.
  - Remove your API keys or update your configuration as needed.
- **Transparency:** You can view, edit, or delete any data stored locally by the extension from within the settings interface.

---

### Third-Party Links and Policies
ApplyEdge interacts with third-party services that you configure within the extension. We encourage you to review their privacy policies:
- **PostHog Analytics:** [PostHog Privacy Policy](https://posthog.com/privacy)
- **OpenAI:** [OpenAI Privacy Policy](https://openai.com/privacy)
- **Anthropic:** [Anthropic Privacy Policy](https://www.anthropic.com/terms)
- **Gemini (Google AI):** [Google Privacy Policy](https://policies.google.com/privacy)

---

### Changes to This Privacy Policy
We may update this privacy policy from time to time. Changes will be reflected in the version posted on our publicly accessible URL (e.g., GitHub). We recommend periodically reviewing this policy to stay informed about our data practices.

---

### Contact
If you have any questions or concerns about this privacy policy, feel free to reach out to us:
- **Email:** Ndo18Development@gmail.com

---

### Summary
ApplyEdge is built with security and user privacy at its core. We ensure that:
1. **All sensitive data is stored locally and encrypted.**
2. **The only data leaving your device is explicitly sent (e.g., for LLM interactions or anonymized event tracking).**
3. **We never store or process your data remotely.**

Your trust is critical to us. ApplyEdge is committed to providing a secure, private, and efficient experience for all users.
