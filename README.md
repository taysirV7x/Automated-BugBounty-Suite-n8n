# 🛡️ Automated Bug Bounty Ecosystem
> A powerful suite of **n8n workflows** for automated recon, monitoring, and AI-assisted analysis.

![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)
![n8n Version](https://img.shields.io/badge/n8n-compatible-orange.svg)
![AI-Powered](https://img.shields.io/badge/AI-Gemini%20Integrated-red.svg)

---

## 📖 Overview
This project is an all-in-one automation "arsenal" built on **n8n**. It eliminates repetitive tasks for security researchers by leveraging AI to analyze threats and monitoring targets in real-time.

---

## 🛠️ The Arsenal (Workflows)

| Tool Name | Core Function | Tech Stack |
| :--- | :--- | :--- |
| **🔍 The Warden: Scope Monitor** | 24/7 HackerOne asset tracking | n8n, GraphQL, Discord |
| **⚔️ The Sword: Template Gen** | AI-driven Nuclei template creation | Gemini AI, n8n Forms |
| **📜 The Herald: Summarizer** | Intelligent H1 report analysis | Gemini AI, H1 API |
| **⚡ CVE Shoten** | Smart monitoring for new CVEs | NIST API, AI Filtering |
| **📊 Tip Harvestor** | Automated knowledge base builder | X API, Google Sheets |

---

## 🚀 Deep Dive

### 1. **The Warden: Scope Monitor** 📡
*Detect changes before the crowd.*
- **Features:** Checks H1 programs every 20 minutes.
- **Output:** Discord alerts with direct links and version diffs.

### 2. **The Sword: Nuclei Generator** 🛠️
*From POC to Scanner in seconds.*
- **Features:** Takes raw POC scripts and descriptions.
- **AI Logic:** Automatically extracts paths, headers, and matchers.

### 3. **The Herald: Report Summarizer** 🧠
*Learn faster, hunt better.*
- **Features:** Fetches JSON reports from HackerOne.
- **Insight:** Provides "Key Takeaway" and "Reproduction Logic" summaries.

---

## ⚙️ Requirements & Setup

### **Prerequisites**
- [x] **n8n Instance** (Self-hosted or Cloud)
- [x] **Google Gemini API Key** (For AI Nodes)
- [x] **Discord Webhook URL** (For Notifications)
- [x] **HackerOne API Credentials**

### **Installation**
1. **Download** the `.json` files from the `workflows/` folder.
2. **Import** them into your n8n dashboard.
3. **Configure** your credentials in the global settings.
4. **Activate** and start hunting!

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page].

## ⚖️ Disclaimer
This project is for **educational and ethical security research** purposes only. Using these tools against targets without explicit permission is illegal.

---
*Created with ❤️ by [Taysir Zeituni]*

<img width="1727" height="951" alt="Screenshot 2026-01-16 002733" src="https://github.com/user-attachments/assets/ebf854f2-feb2-4121-ae68-bf2cbcaaf81b" />
<img width="1737" height="943" alt="Screenshot 2026-01-16 002547" src="https://github.com/user-attachments/assets/227811d8-e4c2-4331-85fb-bff3b68cf33a" />
<img width="1720" height="942" alt="Screenshot 2026-01-16 002439" src="https://github.com/user-attachments/assets/4a7964fa-98c2-4008-91c0-af473b691502" />
<img width="1696" height="946" alt="Screenshot 2026-01-16 002333" src="https://github.com/user-attachments/assets/6d13ea87-65d7-42d6-adf3-8cbc867e549f" />
<img width="1698" height="941" alt="Screenshot 2026-01-16 002144" src="https://github.com/user-attachments/assets/a50c983d-e064-453c-b5bc-bd9e4837f7a6" />
<img width="1732" height="948" alt="Screenshot 2026-01-16 001709" src="https://github.com/user-attachments/assets/e8ac93aa-7d0d-4462-9cae-8ef9d01d1a33" />

