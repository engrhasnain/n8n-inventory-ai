# 🤖 n8n AI Agent with Groq + Google Sheets

This project is my **first n8n automation**, integrating the **LLaMA 3** model (via Groq API) with **Google Sheets** to create a smart AI agent that can **read, update, and append** data directly into a Google Sheet.

---

## 🚀 Features

- 🧠 **AI-Powered Responses** using **Groq's LLaMA 3 model**
- 📄 **Google Sheets Integration**:
  - Read row data from a target sheet
  - Append new rows dynamically
  - Update existing rows with AI-generated results
- 🔄 **Automated Workflow** built entirely in **n8n**
- ⚡ No manual work — everything is automated once triggered

---

## 📂 Workflow Overview

1. **Trigger** → Start workflow with the when chat recieved the message.
2. **Read Sheet Data** → Pulls rows from the connected Google Sheet.
3. **AI Processing** → Sends the data to Groq's LLaMA 3 model for analysis/processing.
4. **Write Back to Sheet** → Updates existing rows or appends new ones automatically.

---

## 🛠️ Tech Stack

- **[n8n](https://n8n.io/)** – No-code/low-code workflow automation
- **[Groq API](https://groq.com/)** – High-speed LLaMA 3 inference
- **[Google Sheets API](https://developers.google.com/sheets/api)** – Data storage and retrieval
- **JavaScript Functions (inside n8n)** – For data formatting and handling

---

## 📸 Demo Post

Check out my **LinkedIn post** where I walk through this project:  
🔗 *[https://www.linkedin.com/posts/muhammad-hasnain-pirzada-335816201_n8n-ai-groq-activity-7359664754950291456-Ue0G?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAADOOa1kBsWsaZdMrTcUn5Kj-uDoHsXL2WX8](#)*

---

## 🗂️ Project Structure

```plaintext
.
├── README.md        # Documentation
├── 1_n8n_inventory_management.json    # Exported n8n workflow file
```
## Using it
To use clone the Repo, and pase the .json file in the desire n8n workflow in the n8n.io workflow project.
