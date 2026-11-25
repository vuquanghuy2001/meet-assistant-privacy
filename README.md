# Privacy Policy for Meet Transcript & Translator and Report Automated

**Last Updated:** November 25, 2026

This Privacy Policy describes how **Meet Transcript & Translator and Report Automated** ("the Extension") handles user data.

## 1. Data Collection & Storage
- **Local Storage Only:** All meeting transcripts, translations, report drafts, and your personal Groq API Key are stored **locally on your device** using Chrome's `chrome.storage.local` API. We do not operate any backend server to collect, store, or sell your meeting data or API keys.
- **No Personal Data Tracking:** The Extension does not collect browsing history, personal identifiers, or analytics.

## 2. How Data Is Processed (Third-Party APIs)
To provide its core features, the Extension transmits caption text directly from your browser to the following services only when you actively use those features:
- **Google Meet (`meet.google.com`):** Reads live caption text from the meeting page DOM solely to display, translate, and summarize it for you.
- **Google Translate (`translate.googleapis.com`):** Sends caption text and user-entered text for real-time English ↔ Korean translation.
- **Groq API (`api.groq.com`):** Sends selected conversation context, keywords, or meeting transcripts directly to Groq using **your own API key** to generate AI reply suggestions and meeting minutes.
- **Feedback Form (Optional):** If you voluntarily submit feedback via the in-app Feedback modal, only your selected feedback category and message are sent to our Google Sheets feedback log to help improve the Extension.

## 3. Data Control & Deletion
You have full control over your data. You can delete all stored transcripts, translations, and report drafts at any time by clicking the **"Clear History"** button inside the Extension, or by uninstalling the Extension.

## 4. Contact
If you have any questions about this Privacy Policy, please contact the developer at: vqh.huy210601@gmail.com
