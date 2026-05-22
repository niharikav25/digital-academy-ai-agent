# Digital Academy AI Support Agent

An AI-powered educational support assistant built using n8n, Google Gemini, and Google Sheets.  
This project simulates a real-world AI customer support workflow for an online learning platform.

The assistant can answer student queries, provide career guidance, recommend learning paths, and retrieve course information from a structured knowledge base.

---

## Features

- AI-powered student support chatbot
- FAQ retrieval using Google Sheets
- Career guidance and course recommendations
- Conversation memory for contextual responses
- Structured prompt engineering
- Knowledge-base grounded responses
- Professional support workflow automation
- Dynamic AI-generated learning roadmaps

---

## Tech Stack

- n8n
- Google Gemini API
- Google Sheets API
- AI Agent Workflows
- Prompt Engineering
- Conversational AI

---

## Workflow Architecture

```text
User
 ↓
Chat Trigger
 ↓
AI Support Agent
 ├── Gemini Support Model
 ├── Conversation Memory
 └── Google Sheets Knowledge Base
 ↓
AI Response
```

---

## Example Queries

- What courses do you offer?
- Do you provide placement assistance?
- How do I become an AI engineer?
- What tools are taught in the DevOps course?
- Which course is best for beginners?
- Do you provide certificates?

---

## Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/niharikav25/digital-academy-ai-agent.git
```

### 2. Import Workflow into n8n

- Open n8n
- Import the workflow JSON file from `/workflows`

### 3. Configure Credentials

Add:
- Google Gemini API credentials
- Google Sheets credentials

### 4. Connect Google Sheets

Use your own spreadsheet as the knowledge base.

### 5. Run Workflow

Start the chat workflow and begin interacting with the AI assistant.

---

## Project Structure

```text
digital-academy-ai-agent/
│
├── workflows/
│   └── digital-academy-ai-agent.json
│
├── screenshots/
│   ├── workflow.png
│   ├── career-guidance.png
│   ├── faq-response.png
│   └── knowledge-base.png
│
├── docs/
│   └── architecture.png
│
└── README.md
```

---

## Future Improvements

- Vector database integration
- Retrieval-Augmented Generation (RAG)
- WhatsApp integration
- Voice-enabled assistant
- Multi-agent routing architecture
- Student analytics dashboard
- Human support escalation workflow

---

## Learning Outcomes

This project helped in understanding:

- AI agent workflows
- Prompt engineering
- Tool calling
- Knowledge grounding
- Conversational AI systems
- Workflow automation using n8n
- AI-powered recommendation systems

---
