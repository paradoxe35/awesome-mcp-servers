# xiyan-mcp-server

**Description:**
A Model Context Protocol (MCP) server powered by XiyanSQL, enabling natural language queries over databases through the MCP interface. It converts natural language into SQL using a built-in or remote model and executes the queries on supported databases.

**Source:** [GitHub Repository](https://github.com/XGenerationLab/xiyan_mcp_server)

**Category:** database-messaging-mcp-servers

**Tags:** mcp, xiyansql, natural-language, database, ai-integration

---

## Features
- **Natural Language to SQL:** Converts natural language input into SQL queries using a state-of-the-art (SOTA) text-to-SQL model (XiYanSQL-QwenCoder-32B).
- **MCP Protocol Support:** Implements the Model Context Protocol for interfacing with various client applications.
- **Multiple Integration Modes:**
  - **Remote Mode:** Connects to remote model APIs (requires API key), suitable for cloud-based deployments.
  - **Local Mode:** Allows running the text-to-SQL model locally for enhanced security, no API key required.
- **Multiple Transport Protocols:** Supports both `stdio` and `sse` (Server-Sent Events) for flexible communication.
- **Database Support:** Compatible with MySQL and PostgreSQL databases (with plans for more dialects).
- **Configurable LLM Backends:**
  - General LLMs (e.g., OpenAI GPT, Qwen-max)
  - SOTA Text-to-SQL models via Modelscope or Alibaba Cloud DashScope
  - Local deployment of XiYanSQL models
- **Sample Data Retrieval:**
  - Retrieve sample data from a specified table for model reference.
  - List available databases.
- **Customizable Server Settings:**
  - Configurable port, host, log level, debug mode, and protocol paths.
- **Flexible Client Integration:**
  - Works with various clients such as Claude Desktop, Cline, Goose, Cursor, and Witsy.
- **Performance:**
  - Demonstrated superior performance on MCPBench compared to MySQL and PostgreSQL MCP servers.
- **Installation:**
  - Available via pip or installation from source.
  - Compatible with Python 3.11+.
- **Configuration:**
  - YAML-based configuration for server, model, and database settings.

## Pricing
No pricing information is provided. The software is open source; however, usage of remote models (e.g., Modelscope or DashScope APIs) may require obtaining API keys and could be subject to their own pricing or usage restrictions.
