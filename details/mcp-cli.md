# mcp-cli

A CLI inspector for the Model Context Protocol (MCP), designed to facilitate development and debugging of MCP-based integrations.

- **Source:** [https://github.com/wong2/mcp-cli](https://github.com/wong2/mcp-cli)
- **Category:** Testing & Debugging Tools
- **Tags:** cli, testing, debugging, mcp, open-source
- **License:** GPL-3.0

## Features
- Run and test MCP servers from various sources:
  - Use default config (Claude Desktop config file)
  - Specify a custom config file (same format as Claude Desktop)
  - Run servers from NPM packages
  - Run locally developed servers via Node.js
  - Connect to running servers over Streamable HTTP (`--url`)
  - Connect to running servers over Server-Sent Events (SSE) (`--sse`)
- List available tools, resources, and prompts exposed by MCP servers
- Call tools, read resources, and read prompts directly from the CLI

## Pricing
mcp-cli is open-source software released under the GPL-3.0 license. There is no cost to use it.
