# YCloud-Developers/ycloud-whatsapp-mcp-server

A Model Context Protocol (MCP) server for the WhatsApp Business Platform by YCloud, enabling business-grade messaging integration via MCP servers.

**Source:** [https://github.com/YCloud-Developers/ycloud-whatsapp-mcp-server](https://github.com/YCloud-Developers/ycloud-whatsapp-mcp-server)

## Features
- **Automatic MCP Tool Generation:** Automatically generates MCP tools from the YCloud WhatsApp OpenAPI specification.
- **Full API Support:** Supports all YCloud WhatsApp API endpoints.
- **API Authentication:** Handles API authentication via API keys in request headers.
- **Parameter Handling:** Automatically processes parameter types and validation for API requests.
- **HTTP Request/Response Handling:** Supports full HTTP request and response lifecycle handling.
- **Environment Variable Configuration:** Allows configuration of API base URL, OpenAPI spec path, and API headers via environment variables.
- **Integration with Claude Desktop:** Can be integrated with the Claude desktop application for direct AI model interaction with the YCloud WhatsApp API.
- **Debugging Tools:** Supports debugging through server logs and MCP Inspector, as well as viewing status/logs within Claude desktop.
- **TypeScript Implementation:** Main codebase is written in TypeScript.
- **Open Source:** Licensed under MIT, open to contributions via pull requests or issues.

## System Requirements
- Node.js v16.0.0 or higher
- npm v7.0.0 or higher
- Claude desktop application (optional, for Claude integration)

## Installation & Usage
- Clone the repository and install dependencies with `npm install`.
- Build the project with `npm run build`.
- Configure required environment variables (API base URL, API key, etc.).
- Start the server with `npm start`.
- For Claude integration, configure the Claude desktop config file as described in the documentation.

## Pricing
No pricing information is provided; this is an open source project available under the MIT license.