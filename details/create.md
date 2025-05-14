# Create

**Category:** MCP Middleware Orchestration  
**Tags:** typescript, server-management, automation, controller

## Description
Create enables dynamic creation and management of Model Context Protocol (MCP) servers on-demand. It provides a TypeScript-based controller that facilitates secure and flexible server lifecycle control. The service runs in Docker for isolation and security, and can itself function as an MCP server, managing other servers as child processes.

## Features
- **Dynamic MCP Server Management**: Create, run, and manage MCP servers as needed, on-demand.
- **TypeScript-Based Controller**: Built with TypeScript, ensuring type safety and flexibility.
- **Docker Support**: Runs in Docker for optimal security and isolation.
- **MCP Server Orchestration**: The server can create and manage multiple MCP servers, enabling a flexible ecosystem.
- **Tool Execution**: Execute tools on managed servers.
- **Server Lifecycle Control**: Start, stop, and delete MCP servers.
- **Server Listing**: List all currently running servers.
- **Tool Discovery**: Get the list of available tools for any managed server.
- **Integration with Claude Desktop and Cursor**: Can be integrated into Claude Desktop and Cursor for workflow automation.
- **Installation Options**: Supports both Docker-based and manual installation via npm.
- **System Requirements**: Requires Node.js 18 or higher.
- **Language Support**: TypeScript currently supported; JavaScript and Python support planned for the future.

### Exposed Tools
- **create-server-from-template**: Create an MCP server from a template (input: language; output: serverId, message)
- **execute-tool**: Execute a tool on a specified server (input: serverId, toolName, args; output: tool execution result)
- **get-server-tools**: Retrieve the list of tools available on a server (input: serverId; output: tools)
- **delete-server**: Delete a specific server (input: serverId; output: success, message)
- **list-servers**: List all currently running servers (no input; output: servers list)

## Installation
- **Docker (Recommended):**
  - Build: `docker build -t mcp-create .`
  - Run: `docker run -it --rm mcp-create`
- **Manual:**
  - Clone: `git clone https://github.com/tesla0225/mcp-create.git`
  - Install dependencies: `npm install`
  - Build: `npm run build`
  - Run: `npm start`

## Integration
- **Claude Desktop**: Add to configuration via `claude_desktop_config.json`.
- **Cursor**: Add globally or per-project in `~/.cursor/mcp.json` or `.cursor/mcp.json`.

## System Requirements
- Node.js 18 or higher

## Pricing
No pricing information provided.

## Source
[View Create on playbooks.com](https://playbooks.com/mcp/tesla0225-create)