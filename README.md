# Sheychael Enterprises – AI Market Intelligence Agent

> **Proof-of-Concept AI Agent** built for Sheychael Enterprises to automate wholesale price comparisons, vendor query routing, and order dispatch logic.

---

## 📌 Executive Summary
Sheychael Enterprises addresses price opacity and logistical friction in commercial wholesale markets. While the broader platform concept focuses on empowering small business vendors and buyers, this repository houses the **working AI Agent prototype** that executes its core market intelligence functions.

---

## 🤖 The AI Agent in Action

### 1. Backend & Workflow Automation
Below is the execution pipeline handling query parsing, database lookups, and dispatch routing:

![Backend Workflow](./figure%202)
*Figure 1: Automated logic and routing pipeline.*

### 2. User & Operational Interface (Frontend Workflows)
Vendor input screens, dashboard interface, and client-facing workflow layout:

![Frontend Interface 1](./figure%201)
![Frontend Interface 2](./FIGURE%203)
*Figures 2 & 3: Vendor input screens and operational interface.*

### 3. Live Chatbot & Prompt Execution
The agent operates under custom system prompt constraints to enforce Sheychael's brand tone, operational rules, and accurate price matching:

![Chatbot Interaction 1](./FIGURE%204)
![Chatbot Interaction 2](./FIGURE%205)
![Chatbot Interaction 3](./FIGURE%206)
*Figures 4–6: Live interactions displaying wholesale price comparisons and query handling.*

---

## 🛠️ Repository Architecture
* `prompts/`: Contains the complete system prompt instructions and decision-tree logic.
* `workflows/`: Exported automation files for backend routing and webhook integration.
* `data/`: Sample SQL schema and non-sensitive inventory lookup tables.

---

## 🔒 Security & Data Hygiene
* All API credentials and tokens have been abstracted into environment variables.
* Sample datasets contain zero live or proprietary client information.
