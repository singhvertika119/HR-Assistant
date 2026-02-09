# AI-Powered Resume Shortlister (n8n + Gemini)

This project automates the recruitment screening process using an n8n workflow and Google Gemini AI.

## 🚀 Features
- **Automated Webhook Entry:** Receives resume data via POST requests.
- **AI Analysis:** Uses Gemini 1.5 Flash to score resumes based on specific technical skills (Python, ML, SQL).
- **Conditional Logic:** Automatically filters candidates with a score >= 70.
- **Email Automation:** Sends professional HTML-formatted 'Shortlist' or 'Rejection' emails via Gmail API.
- **Database Logging:** Appends candidate details and AI feedback to a Google Sheet.

## 🛠️ Tech Stack
- n8n (Workflow Automation)
- Google Gemini AI (LLM)
- Google Sheets & Gmail APIs

## 📂 How to Use
1. Download the `HR Assistant.json` file from this repo.
2. Open your n8n instance.
3. Click on the menu (⋮) and select **Import from File**.
4. Upload the JSON file and connect your own credentials for Gemini, Gmail, and Google Sheets.
