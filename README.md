# AI Workflow Automations with n8n


Welcome to my collection of n8n workflow automations. This repository documents my journey in mastering low-code AI orchestration, transitioning complex agentic logic into scalable, visual pipelines.


## 🚀 Current Project: Stateful AI Email Assistant
This workflow is a context-aware chatbot and email assistant built during the initial phase of my n8n "Zero to Hero" specialization. It demonstrates the ability to manage conversation state and interact with external workspace tools autonomously.

## 🧠 Core Architecture
The workflow consists of four primary components:

Trigger: An n8n Chat Trigger for real-time interaction.

Brain: Azure OpenAI (GPT-5) integrated via a dedicated Chat Model node.

Memory: A Simple Memory node that allows the agent to maintain state (e.g., remembering a user's name or previous requests) across multiple turns.

Tooling: Gmail API integration, enabling the agent to draft and send emails based on natural language instructions.

## 🛠️ Technical Stack
Orchestration: n8n

LLM Provider: Azure OpenAI Service

Infrastructure: KodeKloud Lab Environment / Local Docker

APIs: Google Workspace (Gmail), Google Auth (OAuth 2.0)

## 📸 Workflow Preview
Captured from my active n8n editor session.

## 📥 How to Use
Clone the Repo: 
```bash
git clone https://github.com/chandima2000/n8n-workflows.git
```
Import to n8n:

Open your n8n instance.

Create a new workflow.

Go to Import from File and select workflows/email-ai-agent.json.

Configure Credentials:

Set up your Azure OpenAI API keys.

Configure your OAuth2 credentials for Gmail via the Google Cloud Console.
