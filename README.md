# 🤖 AI Invoice Processing Workflow using n8n & Groq AI

![Workflow](workflow.png)

## 📌 Overview

This project demonstrates an end-to-end AI-powered invoice processing automation built using **n8n**, **Google Drive**, **Groq AI**, and **Google Sheets**.

When a new PDF invoice is uploaded to Google Drive, the workflow automatically downloads the file, extracts the invoice text, processes it using Groq AI to identify key invoice details, and stores the structured output in Google Sheets.

This automation reduces manual effort, improves data accuracy, and accelerates finance operations by eliminating repetitive data entry tasks.

---

## 🚀 Workflow Architecture

```text
Google Drive Trigger
        │
        ▼
Download PDF File
        │
        ▼
Extract Text from PDF
        │
        ▼
Groq AI (Invoice Analysis)
        │
        ▼
Append Structured Data to Google Sheets
```

---

## ✨ Key Features

- 📂 Automatically detects newly uploaded invoice PDFs
- 📥 Downloads files directly from Google Drive
- 📄 Extracts text from PDF invoices
- 🤖 Uses Groq AI for intelligent invoice analysis
- 📊 Stores structured invoice information in Google Sheets
- ⚡ Fully automated, low-code workflow built with n8n
- 💼 Suitable for finance and accounting automation

---

## 🛠 Technology Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| Google Drive | Invoice Storage |
| PDF Extractor | Text Extraction |
| Groq AI | Invoice Data Analysis |
| HTTP Request | API Communication |
| Google Sheets | Structured Data Storage |

---

## 📂 Repository Structure

```
AI-Invoice-Processing-Workflow/
│
├── AI-Invoice-Processing-Workflow.json
├── workflow.png
├── README.md
└── LICENSE
```

---

## ⚙️ How It Works

1. A new invoice PDF is uploaded to Google Drive.
2. n8n detects the new file automatically.
3. The workflow downloads the PDF.
4. Text is extracted from the invoice.
5. The extracted content is sent to Groq AI.
6. Groq AI identifies key invoice details.
7. Structured invoice data is appended to Google Sheets.

---

## 💼 Business Use Cases

- Accounts Payable Automation
- Invoice Processing
- Finance Operations
- Vendor Invoice Management
- Expense Tracking
- Accounting Automation
- AI-powered Document Processing

---

## 📈 Benefits

- Saves manual processing time
- Improves data accuracy
- Reduces human errors
- Standardizes invoice processing
- Easily scalable for large volumes
- Demonstrates practical AI automation in finance

---

## 🔒 Security

For security reasons, API keys and credentials are **not included** in this repository.

Before running the workflow, replace the placeholder below with your own Groq API Key:

```text
Bearer YOUR_GROQ_API_KEY
```

---

## 🚀 Future Improvements

- Gmail Integration
- OCR Enhancement
- Multi-language Invoice Support
- Duplicate Invoice Detection
- Slack Notifications
- Microsoft Teams Notifications
- QuickBooks Integration
- Xero Integration
- Approval Workflow
- Dashboard & Reporting

---

## 📸 Workflow Screenshot

The workflow below shows the complete automation process.

![Workflow](workflow.png)

---

## ⚙️ Installation

1. Clone this repository.
2. Import the JSON workflow into n8n.
3. Configure your Google credentials.
4. Add your Groq API Key.
5. Execute the workflow.

---

## 👨‍💻 Author

**Syed Ali Raza**

Senior Finance & Accounts Professional

AI & Finance Automation

**Skills**

- Financial Reporting
- IFRS & US GAAP
- FP&A
- Data Analytics
- AI Automation
- n8n
- Power BI
- SQL
- Python

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

Feedback and contributions are always welcome.
