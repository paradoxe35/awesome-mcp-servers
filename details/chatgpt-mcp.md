# chatgpt-mcp

**Category:** AI Integration MCP Servers  
**Tags:** mcp, openai, summarization, nlp  
**Source:** [GitHub Repository](https://github.com/automateyournetwork/chatGPT_MCP)

## Description
chatgpt-mcp is a Model Context Protocol (MCP) server that integrates with OpenAI's GPT-4o model. It provides advanced text analysis, summarization, and generation capabilities by forwarding prompts to an external LLM (ChatGPT). The server is designed to run within LangGraph-based assistants.

## Features
- **MCP stdio server:** Exposes a single tool (`ask_chatgpt`) for sending text to ChatGPT (GPT-4o) for advanced reasoning, summarization, and analysis.
- **Text processing capabilities:**
  - Summarizes long documents
  - Analyzes configuration files
  - Compares options
  - Performs advanced natural language reasoning
- **Integration:**
  - Designed for use with LangGraph pipelines
  - Can be configured via JSON for MCP server orchestration
- **Deployment:**
  - Docker support for containerized deployment
  - Manual testing via local command-line interface
- **Environment configuration:**
  - Uses environment variable (`OPENAI_API_KEY`) for secure API access
  - Supports `.env` file or manual export for key management
- **Dependencies:**
  - Installs `openai`, `requests`, and `python-dotenv` during Docker build
- **Security:**
  - Recommends never committing secrets or API keys; use environment variables or a secret manager
- **MIT License**

## Project Structure
- `Dockerfile` – Docker build instructions
- `server.py` – Main server implementation
- `README.md` – Documentation

## Pricing
No pricing information is provided; the project is open source under the MIT license.
