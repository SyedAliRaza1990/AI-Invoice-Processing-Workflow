# 🤖 AI Invoice Processing Workflow using n8n & Groq AI

![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-FF6D00?style=for-the-badge&logo=n8n&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-AI-4B0082?style=for-the-badge)
![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![MIT License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

## 📌 Overview

This project demonstrates an **AI-powered Invoice Processing Automation** built using **n8n**, **Google Drive**, **Groq AI**, and **Google Sheets**.

Whenever a new PDF invoice is uploaded to Google Drive, the workflow automatically:

- 📂 Detects the uploaded invoice
- 📥 Downloads the PDF
- 📄 Extracts text from the invoice
- 🤖 Sends the extracted content to Groq AI
- 📊 Extracts structured invoice information
- 📈 Stores the output in Google Sheets

This automation eliminates repetitive manual work, improves processing speed, and enhances the accuracy of finance operations.

---

# 📸 Workflow Screenshot

![Workflow](workflow.png)

---

# 🚀 Workflow Architecture

```text
Google Drive Trigger
        │
        ▼
Download PDF
        │
        ▼
Extract Text From PDF
        │
        ▼
Groq AI Analysis
        │
        ▼
Append Data to Google Sheets
```

---

# ✨ Features

- ✅ Automatic Invoice Detection
- ✅ PDF Download from Google Drive
- ✅ PDF Text Extraction
- ✅ AI-powered Invoice Analysis
- ✅ Structured Data Extraction
- ✅ Google Sheets Integration
- ✅ Low-Code Automation with n8n
- ✅ Finance Process Automation

---

# 🛠 Technology Stack

| Tool | Purpose |
|------|---------|
| n8n | Workflow Automation |
| Google Drive | File Storage |
| PDF Extractor | Text Extraction |
| Groq AI | Invoice Analysis |
| HTTP Request | API Integration |
| Google Sheets | Data Storage |

---

# ⚙️ How It Works

1. Upload a PDF invoice to Google Drive.
2. Google Drive Trigger detects the new file.
3. The workflow downloads the invoice.
4. Text is extracted from the PDF.
5. Extracted text is sent to Groq AI.
6. Groq AI identifies important invoice details.
7. Structured data is appended to Google Sheets.

---

# 💼 Business Use Cases

- Accounts Payable Automation
- Invoice Processing
- Vendor Invoice Management
- Expense Tracking
- Accounting Automation
- AI Document Processing
- Financial Operations

---

# 📈 Benefits

- ⏱ Saves processing time
- 🎯 Improves accuracy
- 📉 Reduces manual errors
- 🚀 Scalable workflow
- 💰 Increases operational efficiency
- 🤖 Demonstrates AI-powered finance automation

---

# 📂 Repository Structure

```text
AI-Invoice-Processing-Workflow/
│
├── AI-Invoice-Processing-Workflow.json
├── workflow.png
├── README.md
└── LICENSE
```

---

# ⚙️ Installation

1. Clone this repository.

2. Import the workflow JSON into n8n.

3. Configure Google Drive credentials.

4. Replace

```text
Bearer YOUR_GROQ_API_KEY
```

with your own Groq API Key.

5. Execute the workflow.

---

# 🔒 Security

For security reasons:

- API Keys are **NOT included**
- Credentials are removed before publishing
- Use your own Google credentials
- Use your own Groq API Key

---

# 🚀 Future Improvements

- 📧 Gmail Integration
- 🔍 OCR Enhancement
- 📑 Multi-language Invoice Support
- 🚨 Duplicate Invoice Detection
- 💬 Slack Notifications
- 👥 Microsoft Teams Integration
- 💼 QuickBooks Integration
- 📊 Power BI Dashboard
- 📈 Xero Integration
- ✅ Approval Workflow

---

# 👨‍💻 Author

## **Syed Ali Raza**

**Senior Finance & Accounts Professional**

### Expertise

- Financial Reporting
- US GAAP & IFRS
- FP&A
- Budgeting & Forecasting
- Data Analytics
- AI Automation
- n8n
- Power BI
- SQL
- Python

---

## ⭐ Support

If you found this project useful,

**please consider giving this repository a ⭐ on GitHub.**

Your support is greatly appreciated.

---

## 📬 Connect With Me

- 💼 LinkedIn
- 💻 GitHub
