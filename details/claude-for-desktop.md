# Claude for Desktop

A desktop application that acts as an MCP (Model Context Protocol) host, allowing users to connect and interact with various MCP servers. This tool is essential for testing, developing, and using MCP servers, especially in the context of integrating AI models with external data and tools.

**Source:** [Tutorial: Build a Simple MCP Server With Claude Desktop (The New Stack)](https://thenewstack.io/tutorial-build-a-simple-mcp-server-with-claude-desktop/)

## Features
- **MCP Host:** Serves as a local host for MCP servers, enabling desktop-based interaction with AI models and external tools via MCP.
- **Integration with Custom MCP Servers:** Allows users to register and connect their own MCP servers (e.g., built in Python using FastMCP), facilitating testing and local development workflows.
- **Configuration Management:** Supports editing MCP server configuration via a JSON file (`claude_desktop_config.json`), where users can specify command paths and arguments for server processes.
- **Real-Time Data Access:** Enables AI models running in Claude for Desktop to invoke MCP servers and retrieve real-time or contextual data from external APIs (e.g., FlightAware for flight information) as part of the AI workflow.
- **STDIO Transport:** Uses STDIO as the default communication protocol between Claude for Desktop and MCP servers for data exchange.
- **Permission Handling:** When an AI model needs to access a third-party service via MCP, the application prompts the user for permission before making the request.
- **Developer-Focused:** Features a Developer tab in settings for managing and debugging MCP server integrations.
- **Open Source:** Part of the open ecosystem around MCP and AI agent development.

## Pricing
- No pricing information was provided in the available content.

## Tags
`mcp`, `desktop`, `ai-integration`, `open-source`

## Category
Development Tools – MCP Servers
