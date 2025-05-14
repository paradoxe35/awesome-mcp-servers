# dealx/mcp-server

MCP Server for the DealX platform, enabling integration and data retrieval in accordance with the MCP protocol.

- **Source:** [GitHub - DealExpress/mcp-server](https://github.com/DealExpress/mcp-server)
- **Category:** Business & Commerce / MCP Servers
- **Tags:** integration, business, platform, open-source

---

## Overview
The `@dealx/mcp-server` is a Model Context Protocol (MCP) server for the DealX platform. It allows large language models (LLMs) to interact with the DealX platform, currently supporting searching for ads, with planned extensions for further functionalities.

---

## Features
- **Implements the Model Context Protocol (MCP):** Provides a standardized way for LLMs to interact with the DealX platform.
- **Search Ads Tool:**
  - Allows searching for ads on DealX via structured queries.
  - Parameters:
    - `query` (string, optional): Search query string.
    - `sort` (string, optional): Sort order (e.g., "-created" for newest first).
    - `offset` (number, optional): Pagination offset (starts at 1, default: 1).
    - `limit` (number, optional): Number of results per page (max 100, default: 30).
- **Extensible Tooling:**
  - Easily add new tools by defining them in the source and implementing logic.
  - Planned tools include create/edit/delete ads, and managing discussion threads for ads.
- **Environment Configuration:**
  - Supports configuration via `.env` file for API URL, server port, and log level.
- **Supports Multiple Installation Methods:**
  - Install via npm globally or use via npx without installation.
  - Designed for both production use and development/contribution.
- **Integration with LLMs:**
  - Can be added to LLM MCP configurations (e.g., Claude, Cline for VS Code) for natural language interaction with DealX.
- **Development Scripts:**
  - Build, start, lint, format, and test scripts via npm.
- **Written in TypeScript/JavaScript.**
- **Open-source under the MIT License.**

---

## Usage
- Install globally: `npm install -g @dealx/mcp-server`
- Run with npx: `npx -y @dealx/mcp-server`
- Configure environment variables as needed (API URL, port, log level).
- Add to your LLM's MCP configuration for integration.

---

## Planned Features
- Creating, editing, and deleting ads on DealX.
- Managing discussion threads for ads.

---

## Pricing
- **Open Source:** Free to use under the MIT License.

---

## License
MIT License