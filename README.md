# 🚀 Automate Emails Using AI Agents (n8n + Gmail + Google Sheets)

This project demonstrates how to **automatically send personalized emails using an AI Agent in n8n**, connected with **Google Sheets** and **Gmail**.  
It uses **Google Gemini Chat Model** inside n8n to generate dynamic email content.

---

## 📌 Features
- ✅ Read contact details (email, name, region) from **Google Sheets**  
- ✅ Use an **AI Agent (Google Gemini Chat Model)** to create personalized email messages  
- ✅ Automatically send emails via **Gmail**  
- ✅ Update Google Sheets with the **status** ("Email Sent") after sending  

---

## 🛠️ Workflow Overview

The n8n workflow includes the following steps:

1. **Trigger** → Start the workflow manually (`Execute Workflow`).  
2. **Google Sheets Node** → Fetch recipient details.  
3. **Edit Fields Node** → Clean/prepare data.  
4. **AI Agent Node** → Generate personalized email text.  
5. **Gmail Node** → Send email to recipients.  
6. **Google Sheets Update Node** → Mark status as "Email Sent".  

---

## 🔗 Workflow Diagram

![Workflow]

---

## 📊 Sample Google Sheet

Here’s how the Google Sheet looks:

| Email                  | Name   | Region        | Status     |
|-------------------------|--------|--------------|------------|
| 23b01a1272@svecw.edu.in | Ravi   | Eluru        | Email Sent |
| kandula.jayati@gmail.com | Vishal | Machilipatnam | Email Sent |
| kandula.marvel@gmail.com | Zara  | Vizag        | Email Sent |

![Google Sheet

---

## ⚡ Tech Stack
- [n8n](https://n8n.io/) – Workflow automation  
- **Google Sheets** – Contact storage  
- **Google Gemini Chat Model** – AI for personalized messages  
- **Gmail** – Sending emails  

---

## ▶️ How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/Jayatikandula/Automate-Emails-Using-AI-Agents.git
