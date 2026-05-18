# ✉️ AI-Powered Cold Email Outreach & Conditional Follow-Up System

An intelligent, production-grade outbound engine that leverages LLMs and multi-stage conditional n8n logic to generate hyper-personalized cold email campaigns and track prospect engagement automatically.

---

## 📊 Workflow Architecture
![n8n Workflow Canvas Layout](<img width="1859" height="657" alt="Screenshot 2026-05-19 004744" src="https://github.com/user-attachments/assets/b585c04f-3a50-40bf-b599-a07b0f8a7342" />

---

## 🛠️ Core Tech Stack
* **Workflow Orchestration:** n8n (Advanced Conditional Logic, Wait Nodes, Webhook triggers)
* **AI & Core Execution:** OpenAI API (GPT-4o / GPT-3.5-Turbo), Prompt Engineering
* **Languages:** Python
* **Integrations:** Gmail API, Google Sheets API

---

## 💡 Key Core Functionalities
* **Dynamic Hyper-Personalization:** Instead of using rigid templates, the system processes raw multi-source lead data through the OpenAI API to write context-aware, highly tailored cold emails dynamically.
* **Multi-Stage Conditional Follow-Ups:** Built with advanced n8n routing logic. The system automatically tracks if a lead has replied; if no response is detected within a designated timeline, it routes them into custom, conditional follow-up sequences.
* **Hands-Free Analytics Tracking:** Integrated seamlessly with Google Sheets and Gmail to monitor delivery performance, sequence states, and scale outreach cleanly to ~20 targeted leads daily.

---

## 🚀 Deployment Instructions

### 1. Import the Workflow to n8n
1. Download the `Cold-Email-Follow-Up-Automation.json` file from this repository.
2. Open your n8n instance, create a new workflow, click the three dots in the top-right corner, and select **Import from File**.
3. Upload the `.json` file to instantly populate the entire node canvas.

### 2. Configure Credentials & Environment Variables
Ensure you have active API connections established in your n8n instance for:
* **OpenAI API** (For generating personalized email copies)
* **Google Sheets** (For reading lead lists and updating sequence statuses)
* **Gmail** (For sending the outbound outreach and checking for replies)

---

## 📂 Repository Contents
* `Cold-Email-Follow-Up-Automation.json` — Full n8n canvas export file.
* `README.md` — Technical documentation and architecture breakdown.
