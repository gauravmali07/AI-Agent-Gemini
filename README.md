# 🤖 AI Agent Workflow Automation using n8n & Google Gemini

![GitHub](https://img.shields.io/badge/GitHub-Portfolio_Project-black)
![n8n](https://img.shields.io/badge/n8n-Workflow_Automation-ff6d5a)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-blue)
![AI Agent](https://img.shields.io/badge/AI-Agent-success)
![LLM](https://img.shields.io/badge/LLM-Google_Gemini-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 🚀 Project Overview

This project demonstrates the implementation of an **AI-powered workflow automation agent** using **n8n** and **Google Gemini**.

The AI Agent is capable of understanding user queries, maintaining conversational context through memory, performing calculations, and utilizing external search tools to provide intelligent responses.

The workflow combines Large Language Models (LLMs), memory management, and tool calling to simulate real-world AI agent behavior.

---

## 🎯 Key Features

### 🧠 Conversational Memory

Maintains context across conversations using memory nodes.

### 🤖 Google Gemini Integration

Uses Google's Gemini model for intelligent response generation.

### 🧮 Calculator Tool

Performs mathematical calculations dynamically.

### 🔍 Google Search Tool

Retrieves real-time information using SerpAPI.

### ⚡ Workflow Automation

Built using n8n's low-code workflow automation platform.

### 🔗 Tool Calling

Allows the AI Agent to decide when to use external tools.

---

## 🏗️ Architecture

```text
User Query
     │
     ▼
Chat Trigger
     │
     ▼
AI Agent
 ├── Google Gemini Chat Model
 ├── Simple Memory
 ├── Calculator Tool
 └── Google Search (SerpAPI)
     │
     ▼
Generated Response
```

---

## 🛠️ Technology Stack

| Category            | Technology      |
| ------------------- | --------------- |
| Workflow Automation | n8n             |
| AI Model            | Google Gemini   |
| Memory              | Simple Memory   |
| Search Tool         | SerpAPI         |
| Tool Calling        | Calculator Tool |
| Agent Framework     | n8n AI Agent    |

---

## 📸 Screenshots

### Workflow Architecture

<img width="1917" height="885" alt="Screenshot 2026-06-22 135504" src="https://github.com/user-attachments/assets/c6a99591-ffe6-4aeb-93a5-bf551664a72d" />

<img width="1917" height="880" alt="Screenshot 2026-06-22 135414" src="https://github.com/user-attachments/assets/30b76aa8-d6c1-4ae3-a279-c0d370267426" />

## ⚙️ Workflow Components

### AI Agent

Acts as the central decision-making component that processes user requests and determines when to invoke tools.

### Google Gemini Chat Model

Provides natural language understanding and response generation.

### Simple Memory

Stores conversation history to enable context-aware interactions.

### Calculator Tool

Handles arithmetic and mathematical operations.

### Google Search (SerpAPI)

Retrieves external information from search engines when required.

---

## 📂 Repository Structure

```text
n8n-ai-agent-gemini/
│
├── README.md
├── workflow.json
│
├── screenshots/
│   ├── workflow.png
│   └── ai-response.png
│
└── docs/
    └── setup-guide.md
```

---

## 🚀 Getting Started

### Prerequisites

* n8n Installed
* Google Gemini API Key
* SerpAPI Key

### Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/n8n-ai-agent-gemini.git
```

Navigate to the project directory:

```bash
cd n8n-ai-agent-gemini
```

### Import Workflow

1. Open n8n.
2. Click **Import Workflow**.
3. Select `workflow.json`.
4. Configure your credentials.
5. Activate the workflow.

---

## 💡 Example Use Cases

### Information Retrieval

Ask questions that require online search.

### Mathematical Calculations

Perform arithmetic operations using the Calculator Tool.

### Conversational Assistant

Maintain context across multiple interactions.

### AI Automation Learning

Understand AI agent architecture and workflow orchestration.

---

## 📈 Skills Demonstrated

* AI Agent Development
* Prompt Engineering
* Workflow Automation
* LLM Integration
* Tool Calling
* API Integration
* Conversational Memory
* Problem Solving & Debugging

---

## 🔮 Future Enhancements

* PDF Document Chat
* RAG (Retrieval-Augmented Generation)
* WhatsApp Integration
* Telegram Bot Integration
* Google Sheets Logging
* Email Automation
* Vector Database Integration
* Multi-Agent Architecture

---

## 👨‍💻 Author

**Gaurav Mali**

🎓 Master of Computer Applications (MCA)

💡 Passionate about Artificial Intelligence, Data Analytics, Workflow Automation, and Full-Stack Development.

### Connect with Me

* LinkedIn: https://linkedin.com/in/YOUR-LINKEDIN
* GitHub: https://github.com/YOUR-GITHUB

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It helps support my learning journey and future open-source projects.
