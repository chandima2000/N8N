## Project Overview: 

A visual automation pipeline that integrates Azure OpenAI with Gmail to create a context-aware assistant. The system uses a memory buffer to maintain conversation state, allowing the agent to remember user details (like names) across multiple turns.

## Tech Stack:

Orchestration: n8n

LLM: Azure OpenAI (GPT-4o / GPT-4 Turbo)

Memory: Simple Window Buffer (Stateful conversation)

Integrations: Google Workspace (Gmail API)

## Key Features:

Stateful Interaction: Uses a Memory node to store and retrieve chat history.

Tool Calling: The agent can autonomously decide when to draft or send an email via the Gmail node.

Dynamic Prompting: Custom system messages to define the agent's persona as a professional assistant.