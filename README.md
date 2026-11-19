# n8n Masterclass: Automations & AI Agents

My hands-on learning repository for the **Complete n8n Masterclass [Updated for 2026]: Build Real-World Automations and AI Agents from Scratch** by [CampusX](https://www.youtube.com/@campusx-official).

This repo collects the workflows, notes, and mini-projects I build while going through the course, from basic triggers and nodes to full AI agent pipelines.

## About the Course

n8n is an open-source, low-code workflow automation platform. The course teaches how to connect apps, APIs, and AI models into automated workflows, and how to build AI agents that can reason, use tools, and take action.

## What's Inside

```
n8n-masterclass-automations-and-ai-agents/
├── 01-basics/              # Triggers, nodes, expressions, data flow
├── 02-apis-and-webhooks/   # HTTP requests, webhooks, authentication
├── 03-integrations/        # Google Sheets, Gmail, Slack, Telegram, etc.
├── 04-ai-workflows/        # LLM nodes, prompts, structured outputs
├── 05-ai-agents/           # Agents, tools, memory
├── 06-rag/                 # Vector stores, embeddings, chat with documents
├── 07-projects/            # End-to-end real-world automations
├── workflows/              # Exported workflow JSON files
└── notes/                  # Concepts and learnings
```

> Folder names will follow the course modules, so adjust as you progress.

## Topics Covered

- n8n fundamentals: workflows, nodes, triggers, executions
- Working with data: JSON, expressions, code node, merging and branching
- APIs, webhooks, and HTTP requests
- Connecting apps and services (Google Workspace, messaging platforms, databases)
- Error handling, scheduling, and workflow reliability
- LLM integration and prompt design inside workflows
- Building AI agents with tools and memory
- Retrieval-Augmented Generation (RAG) with vector databases
- Real-world automation projects

## How to Use These Workflows

1. Install and run n8n (self-hosted via Docker/npm, or use n8n Cloud).
2. Open a workflow JSON from the `workflows/` folder.
3. In n8n, go to **Workflows → Import from File** and select the JSON.
4. Add your own credentials (API keys, OAuth) to each node that requires them.
5. Run the workflow and tweak it for your own use case.

⚠️ **Never commit API keys or credentials.** Exported workflows should have credentials removed, and secrets should live in n8n's credential manager or a `.env` file (already in `.gitignore`).

## Progress Tracker

- [ ] Basics and core concepts
- [ ] APIs and webhooks
- [ ] App integrations
- [ ] AI workflows
- [ ] AI agents
- [ ] RAG
- [ ] Final projects

## Tech Stack

n8n · Docker · JavaScript (Code node) · REST APIs · LLM APIs (OpenAI / Gemini / Claude) · Vector databases

## Credits

All course content belongs to **CampusX**. This repository contains only my own practice work and notes for learning purposes.

## License

MIT License. Feel free to learn from and adapt the workflows.
