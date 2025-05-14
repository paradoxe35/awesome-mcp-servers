# MCPHost

A CLI host application that enables Large Language Models (LLMs) to interact with external tools via the Model Context Protocol (MCP).

[Source & Documentation](https://mcphub.tools/detail/mark3labs/mcphost)

## Features
- **CLI Host Application:** Provides a command-line interface for hosting LLM interactions.
- **Supports Multiple LLMs:** Currently supports Claude 3.5 Sonnet and various Ollama models.
- **MCP Client-Server Architecture:** Facilitates connections to external tools and data sources through the Model Context Protocol.
- **Interactive Conversations:** Allows dynamic, interactive engagement with supported LLMs.
- **Multiple Concurrent MCP Servers:** Connect to and interact with multiple MCP servers simultaneously.
- **Dynamic Tool Discovery:** Automatically identifies and integrates available tools during LLM interactions.
- **Tool Calling Capabilities:** Enables LLMs to call functions from both Claude and Ollama models for enriched responses.
- **Configurable MCP Settings:** Users can adjust server locations, command arguments, and message history.
- **Configurable via CLI Flags:** Supports specifying models, configuration files, and other settings through command-line flags.
- **Customizable Configuration:** Creates and manages a configuration file (`~/.mcp.json` by default), with support for custom paths.
- **MCP Server Compatibility:** Works with any MCP-compliant server; reference implementations are available.
- **Environment Variable Support:** Integrates with environment variables (e.g., `OLLAMA_HOST` for Ollama base URL).
- **Open Source:** Licensed under the MIT License.

## Pricing
No pricing information provided. MCPHost is open source and available under the MIT License.

## Tags
`cli` `llm-integration` `host` `open-source`