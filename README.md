# cold-mail-automation
AI-powered cold email automation built with n8n to streamline internship outreach, personalize emails, manage leads, and automate the sending workflow using spreadsheets and AI.

# 🚀 SmartIntern – AI Cold Email Automation

SmartIntern is an **AI-powered internship outreach automation system** built with **n8n**. It helps students find and contact potential companies, recruiters, professors, and organizations through personalized cold emails.

## ✨ Features

* 🤖 **AI-Powered Email Generation** – Creates personalized cold emails automatically.
* ⚡ **n8n Automation** – Connects the complete workflow without manual effort.
* 📊 **Google Sheets Integration** – Store and manage company, recruiter, and email data.
* 📧 **Automated Email Sending** – Sends personalized emails directly through the workflow.
* 🎯 **Personalized Outreach** – Generates emails based on company and recipient information.
* 🔄 **Workflow Automation** – Automates repetitive internship outreach tasks.
* 📝 **Easy Lead Management** – Add and manage new prospects through a spreadsheet.

## 🛠️ Tech Stack

* **n8n** – Workflow automation
* **AI / LLM** – Personalized email generation
* **Google Sheets** – Lead & data management
* **Gmail / Email API** – Email delivery
* **HTML/CSS/JavaScript** – Web interface *(if applicable)*

## 🔄 How It Works

```text
Google Sheets
      ↓
   n8n Workflow
      ↓
   Read Lead Data
      ↓
   AI Email Generation
      ↓
Personalized Cold Email
      ↓
   Gmail / Email
      ↓
      Sent
```

## 📋 Example Data

| Name  | Company      | Email                                         |
| ----- | ------------ | --------------------------------------------- |
| John  | Example Tech | [john@example.com](mailto:john@example.com)   |
| Sarah | AI Startup   | [sarah@example.com](mailto:sarah@example.com) |

The workflow reads the lead information and generates a personalized email based on the available details.

## ⚙️ Setup

### 1. Install / Set Up n8n

Create an n8n workspace and prepare a new workflow.

### 2. Connect Google Sheets

Create a spreadsheet containing your leads and connect it to n8n.

### 3. Configure AI

Connect your preferred AI model/API and add the prompt responsible for generating personalized internship emails.

### 4. Configure Email

Connect Gmail or another supported email service to send the generated emails.

### 5. Run the Workflow

Add your leads to the spreadsheet and execute the n8n workflow.

## 🔐 Environment Variables & Credentials

Do **not** upload API keys, passwords, OAuth credentials, or private email credentials to GitHub.

Use n8n's credential management system or environment variables to securely store sensitive information.

## 🎯 Use Cases

* Internship outreach
* Cold emailing companies
* Contacting professors and researchers
* Startup outreach
* Freelance outreach
* Business networking
* Automated lead generation

## 📌 Project Goal

The goal of SmartIntern is to reduce the repetitive work involved in internship outreach and make the process **faster, more personalized, and easier to manage**.

## 🚧 Future Improvements

*  AI-based company/recruiter discovery
*  Automated follow-up emails
*  Email response tracking
*  Outreach analytics dashboard
*  LinkedIn lead integration
*  Better email personalization
*  Web-based campaign management

## 👨‍💻 Author

**Manan Jain**

B.Tech CSE | AI • Automation • Web Development

---

⭐ If you find this project useful, consider giving it a **star**!
