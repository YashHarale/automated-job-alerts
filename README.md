# Automated Job Alerts (n8n)

An end-to-end automation that fetches, filters, and delivers **Product Management job alerts** from multiple sources using **n8n**, and sends a **daily email digest** automatically.

This project demonstrates real-world automation, API integration, data normalization, filtering logic, and scheduled execution.

---

## 🚀 What This Project Does

- Fetches remote jobs from **RemoteOK** and **Remotive**
- Filters roles relevant to **Product Management**
- Merges jobs from multiple sources
- Generates a clean, structured email digest
- Sends the email automatically every day at **9:00 AM**
- Avoids manual job searching entirely

---

## 🧠 Key Features

- 🔄 Multi-source job aggregation  
- 🎯 Role-based filtering (PM, APM, TPM, Product Analyst)  
- 🧹 Data normalization across APIs  
- 📬 Automated email delivery  
- ⏰ Daily scheduled execution  
- 🧩 Low-code but production-style workflow design  

---

## 🛠 Tech Stack

- **n8n** – Workflow automation
- **RemoteOK API** – Remote job listings
- **Remotive API** – Remote job listings
- **(Send Email) SMTP** – Email delivery
- **JavaScript** – Custom logic inside n8n Code nodes

---

## 🖼 Workflow Overview

Below is the complete n8n workflow used in this project:

![n8n Workflow](screenshots/n8nFlowDiagram.png)

### Flow Explanation:
1. **Schedule Trigger** runs daily at 9 AM  
2. Jobs are fetched from **RemoteOK** and **Remotive**  
3. Job data is normalized into a common structure  
4. Product Management roles are filtered  
5. Results from both sources are merged  
6. A structured email body is generated  
7. Email is sent to the user automatically  




