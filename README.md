![Workflow thumbnail](assets/thumbnail.svg)

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# AI-Powered Ticket Triage with Multi-Model Classification & Knowledge Base

Advanced n8n automation for AI-Powered Ticket Triage with Multi-Model Classification & Knowledge Base.

## Overview
- Category: Ticket Management, AI RAG
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Automate enterprise ticket management with AI-powered triage, faster resolutions, and seamless integration. Boost support efficiencylearn more now!

## Included Files
- `workflow.json`
- `metadata.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `@n8n/n8n-nodes-langchain.agent`
- `@n8n/n8n-nodes-langchain.documentDefaultDataLoader`
- `@n8n/n8n-nodes-langchain.embeddingsOpenAi`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `@n8n/n8n-nodes-langchain.mcpClientTool`
- `@n8n/n8n-nodes-langchain.outputParserStructured`
- `@n8n/n8n-nodes-langchain.vectorStorePGVector`
- `n8n-nodes-base.code`
- `n8n-nodes-base.if`
- `n8n-nodes-base.postgres`
- `n8n-nodes-base.set`
- `n8n-nodes-base.slack`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.webhook`

## Author

Murtaza Baig

## License
MIT License. See `LICENSE`.