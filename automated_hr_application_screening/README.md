# 🤖 HR Automation System (n8n Workflow)
- This workflow provides an AI-powered human resources automation system running on the n8n platform.
- It automatically evaluates CVs, sends feedback to candidates, and manages interview processes.

## 🌟 Key Features
### 📧 Automatic CV Evaluation
- Processes incoming CVs automatically (PDF and text formats)

- Evaluates technical qualifications using AI-based filtering

- Classifies candidates as "Approved" or "Rejected" using Mistral AI model

### 🔍 Candidate Management
- Stores all candidate information centrally in Google Sheets

- Tracks every stage of the interview process

- Automated reminder and feedback system

### 🤖 Smart Decision Mechanism
- Automatic screening based on predefined technical criteria

- Ability to manually override AI decisions

- Automatic feedback emails to rejected candidates

### ⏰ Scheduled Operations
- Periodically scans Google Sheets to check pending candidates

- Automatically sends interview invitations

- Updates database after processing

## 🛠 Technical Details
### 🔗 Integrations
- Google Sheets - Candidate tracking system

- PDF.co - CV to text conversion

- Mistral AI - CV evaluation

- SMTP - Email sending

- IMAP - Incoming email reading

### ⚙️ Workflow Logic
- Detects incoming CVs via IMAP

- Converts PDFs to text

- Performs technical evaluation with AI

- Saves results to Google Sheets

- Sends automatic responses to candidates

- Periodically checks eligible candidates for interviews

- Sends interview invitations and updates database

### 🚀 Installation
- Set up n8n (official documentation)

- Add required credentials:

- IMAP/SMTP

- Google Sheets API

- PDF.co API

- Mistral AI

- Import the .json file to n8n

- Adjust triggers and scheduling according to your needs

## 📌 Important Notes
- ❗ This workflow provides a fully automated solution, but manual review of AI decisions is recommended for critical positions.

- ❗ Ensure you have set up proper permissions for Google Sheets integration.

- ❗ Remember to update AI prompts according to your company's technical requirements.

## 💡 Contribution
- This project is open source. You can fork it to add new features or make improvements, and submit pull requests.