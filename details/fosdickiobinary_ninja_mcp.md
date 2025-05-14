# fosdickio/binary_ninja_mcp

A Binary Ninja plugin and MCP server for integrating Binary Ninja with MCP/LLM clients to enable automated binary analysis and reverse engineering workflows.

- **Source:** [GitHub Repository](https://github.com/fosdickio/binary_ninja_mcp)
- **Category:** Security Attestation / MCP Servers
- **License:** GPL-3.0

---

## Features

- **MCP Server for Binary Ninja:** Exposes Binary Ninja's capabilities via HTTP endpoints, enabling integration with any MCP client.
- **Real-time Integration:** Seamlessly connects Binary Ninja with LLM/MCP clients for AI-assisted reverse engineering.
- **Primary Support for Claude Desktop:** Out-of-the-box integration with Claude Desktop, but extensible to other MCP clients.
- **MCP Bridge Component:** Allows connection between different MCP clients and the Binary Ninja MCP server.
- **Automated Binary Analysis:** Supports automated generation of analysis reports, renaming functions, and more via LLM prompts.
- **Supported Integration Functions:**
  - Get binary status
  - List classes, data items, exports, imports, methods, namespaces, segments
  - Rename data and functions
  - Search functions by name
  - Decompile functions to C code
  - Set, get, and delete comments (for addresses and functions)
  - Retrieve assembly for functions
- **Installation via Plugin Manager:** Install directly from Binary Ninja's Plugin Manager or manually.
- **Python 3.12+ Support:** Requires Python 3.12 or newer.
- **Extensible:** Can be used with other MCP clients by implementing the required integration layer.

## Components

- **Binary Ninja Plugin:** Implements the MCP server functionality.
- **MCP Bridge:** Facilitates communication between MCP clients and the Binary Ninja MCP server (especially for Claude Desktop).

## Prerequisites

- Binary Ninja
- Python 3.12+
- (Optional) Claude Desktop, or other MCP client

## Installation & Setup

- Install the plugin via Binary Ninja's Plugin Manager or copy the repository to the plugins folder.
- For Claude Desktop integration, use the provided setup script or configure manually as described in the documentation.

## Usage

- Start Binary Ninja and the MCP server plugin.
- Launch your MCP client (e.g., Claude Desktop) to enable integration.
- Use natural language prompts in the MCP client to perform binary analysis and reverse engineering tasks.

## Pricing

- No pricing information provided; the project is open source under GPL-3.0.

## Tags

`mcp` `binary-analysis` `reverse-engineering` `automation`