# MCP Python SDK

- **Category:** Development Tools / MCP Servers
- **Source:** [GitHub - henrypugh/mcp-python-sdk](https://github.com/henrypugh/mcp-python-sdk)
- **Tags:** python, sdk, development, mcp

## Overview
The MCP Python SDK is the official Python implementation of the Model Context Protocol (MCP), enabling developers to build MCP servers and clients in Python. MCP standardizes the way applications provide context to large language models (LLMs), separating context provision from LLM interaction. This SDK implements the full MCP specification.

## Features
- **Full MCP Protocol Support:** Implements all MCP protocol messages, lifecycle events, and core primitives (resources, tools, prompts).
- **Server and Client APIs:**
  - Build MCP servers that expose resources, prompts, and tools.
  - Build MCP clients that connect to any MCP server.
- **Core Concepts:**
  - **Resources:** Expose data to LLMs (analogous to GET endpoints).
  - **Tools:** Provide functionality for LLMs to take actions (analogous to POST endpoints).
  - **Prompts:** Define reusable templates for LLM interactions.
  - **Images:** Automatic handling of image data with an Image class.
  - **Context:** Access to MCP capabilities (progress reporting, resource reading, etc.) in server handlers.
- **Server Implementation:**
  - `FastMCP` high-level server for quick development.
  - Low-level server API for full protocol control and advanced customization.
  - Lifespan API for managing startup/shutdown and resource initialization.
- **Transport Support:**
  - Standard transports including stdio and SSE.
- **Development Tools:**
  - Quickstart templates and examples (Echo Server, SQLite Explorer).
  - Development mode with hot-reloading and dependency management.
  - Integration with Claude Desktop for easy server installation and testing.
- **Client Utilities:**
  - High-level client session for interacting with MCP servers.
  - List and interact with prompts, resources, and tools.
  - Support for sampling callbacks and advanced client features.
- **Server Capabilities Declaration:**
  - Servers declare features such as prompts, resources, tools, logging, and completion suggestions during initialization.
- **Type-Safe Context Passing:**
  - Use of Python typing and async context managers for robust server lifecycle and handler context.
- **Extensive Documentation and Examples:**
  - Code snippets and example servers provided in the repository.
- **Open Source:** Licensed under the MIT License.

## Installation
- Recommended: `uv add "mcp[cli]"`
- Alternative: `pip install mcp`

## Pricing
- **Open Source / Free** (MIT License)

## Documentation
- [Model Context Protocol documentation](https://modelcontextprotocol.io/)

---
**Repository:** [https://github.com/henrypugh/mcp-python-sdk](https://github.com/henrypugh/mcp-python-sdk)