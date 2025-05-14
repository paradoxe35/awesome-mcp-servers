# higress-ops-mcp-server

**Category:** cloud-devops-mcp-servers  
**Source:** [GitHub Repository](https://github.com/higress-group/higress-ops-mcp-server)

## Description
higress-ops-mcp-server is an implementation of a Model Context Protocol (MCP) server that provides comprehensive configuration and management capabilities for the Higress gateway. It includes both a server and a client, facilitating interaction with Higress through an agent-based architecture leveraging LangGraph and LangChain MCP Adapters.

## Features
- **MCP Server Implementation:** Provides a server that manages and configures Higress gateways via the MCP protocol.
- **Integrated MCP Client:** Includes a client for interacting with the MCP server, built using LangGraph and LangChain MCP Adapters.
- **Agent Flow Architecture:** Supports agent-based workflows for streamlined configuration and management tasks.
- **Extensible Tooling:**
  - Easily add new tools by creating or extending tool classes.
  - Tools can encapsulate custom logic and API calls to the Higress Console.
  - Tools can be registered and managed through a unified mechanism.
- **Environment Configuration:** Uses environment variables for configuration, supporting flexible deployment.
- **Sensitive Tool Handling:** Supports marking certain tools (e.g., write operations) as requiring human confirmation before execution.
- **API Interaction:** Built-in utilities for making HTTP API calls (GET, PUT, POST) to the Higress Console API.
- **Python Implementation:** The server and client are implemented in Python, facilitating customization and integration.

## Usage
- Start the MCP server and client in stdio mode using `uv run client.py`.
- Add and register custom tools to extend management capabilities.
- Configure environment variables via `.env` file.

## Pricing
No pricing information is provided; the project is open source.

## Tags
mcp, higress, gateway, cloud, configuration