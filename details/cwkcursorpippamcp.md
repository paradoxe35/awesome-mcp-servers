# Cwkcursorpippamcp

A comprehensive memory management system MCP server for Cursor IDE, enabling AI assistants to remember, recall, and manage information across conversations. Designed as a reference implementation for advanced MCP (Model Context Protocol) server design.

## Features
- **Persistent Memory Across Conversations:** Allows AI assistants (such as Claude or any model supporting MCP) to store and recall information throughout sessions.
- **Model-Agnostic Design:** While initially built for Claude, works with any AI assistant compatible with MCP.
- **Streamlit Management UI:** Provides a user-friendly web interface for browsing, searching, editing, and deleting memories outside of Cursor IDE.
- **Explicit Tool Invocation:** Supports explicit MCP tool calls for memory operations (remember, recall, list, delete) via Cursor IDE.
- **Natural Language and Tool Calls:** Enables both natural language and explicit tool-based memory management, depending on context.
- **Reference Implementation:** Includes a simple "Hello World" MCP server example and advanced usage guides for building custom MCP servers.
- **Educational Resources:** Comprehensive documentation, learning guides, SDK instructions, and troubleshooting advice for MCP integration.
- **Three-tier Configuration System:** Supports flexible configuration through prioritized sources and `.env` files.
- **API Usage:** Memory system can be accessed programmatically for advanced integrations.
- **Troubleshooting Guides:** Addresses common issues with MCP server setup and Cursor integration.
- **Open Source:** Code licensed under MIT (with identity/personality content under separate terms).

## Installation & Usage
- Designed to be installed as a Python development module.
- Must use the same Python environment as Cursor IDE.
- Configurable via `mcp.json` and optional `.env` file.
- Runs as a subprocess when enabled in Cursor's MCP Servers settings.

## Project Structure
- `learning/`: Guides, SDK instructions, troubleshooting, and working examples.
- `mcp-pippa-memory/`: Main MCP memory server implementation.

## Pricing
- **Free and Open Source** (MIT License for code)

## Links
- [GitHub Repository](https://github.com/neobundy/cwkcursorpippamcp)
- [MCP Learning Guide](https://github.com/neobundy/cwkcursorpippamcp/tree/main/learning)

## Category
- AI Integration MCP Servers

## Tags
`mcp` `memory` `context-management` `cursor`