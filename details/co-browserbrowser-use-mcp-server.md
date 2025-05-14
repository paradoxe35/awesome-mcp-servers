# co-browser/browser-use-mcp-server

[GitHub Repository](https://github.com/co-browser/browser-use-mcp-server)

## Description
`co-browser/browser-use-mcp-server` is a server package that enables remote browser automation via an MCP (Multi-Client Protocol) server using SSE (Server-Sent Events) transport. It includes a Dockerized Chromium browser and a VNC server for visual remote browser access. It is designed for integration with AI tools and clients such as Cursor, Claude Desktop, and Claude Code.

## Features
- **MCP Server with SSE Transport:** Exposes a server supporting the MCP protocol using SSE for real-time communication with clients.
- **Remote Browser Automation:** Allows programmatic control of a Chromium browser through defined actions and tasks.
- **Async and Synchronous Modes:** Supports both asynchronous browser tasks and a "PATIENT" mode for fully synchronous operations.
- **Dockerized Environment:** Runs Chromium and VNC within a Docker container for easy deployment and isolation.
- **VNC Server:** Streams the browser UI over VNC, allowing visual access to the remote browser session. Default password is `browser-use`, with support for Docker secrets for production use.
- **Playwright Integration:** Uses Playwright for browser automation; requires Playwright to be installed and configured.
- **Configurable via Environment Variables:** Supports settings for API keys, custom Chrome builds, and operation modes via `.env` file.
- **Client Compatibility:** Works with Cursor, Claude Desktop, Claude Code, and other MCP-compatible clients.
- **Extensible LLM Provider Support:** Plans to add support for multiple LLM providers (Claude, Grok, Bedrock, etc.) to power browser-use automation.
- **Open Source:** Licensed under the MIT license.

## Usage
- Start the server and connect MCP clients using the provided SSE endpoint (e.g., `http://localhost:8000/sse`).
- VNC access is available on port 5900 by default.
- Configure environment variables as needed in a `.env` file (API keys, Chrome path, operation mode).
- Supports integration with various clients via JSON configuration files.

## Pricing
No pricing information is provided; the project is open source and available under the MIT license.

## Tags
mcp, browser, automation, docker, sse

## Category
code-execution-automation-mcp-servers