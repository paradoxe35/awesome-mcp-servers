# Bos (Basic Orchestration System)

**Category:** MCP Middleware Orchestration  
**Source:** [playbooks.com/mcp/gooboot-bos](https://playbooks.com/mcp/gooboot-bos)

## Description
Bos (MCP-BOS) is a modular, extensible Model Context Protocol (MCP) server framework designed for Claude Desktop. It provides a configuration-based approach for building and managing extensible MCP services, simplifying module loading and registration for MCP server development.

## Features
- **Modular Architecture:** Easily build and manage extensible MCP services using a modular server framework.
- **Configuration-Based Setup:** Configure servers and modules through a `config.json` file, allowing for global and module-specific configurations (e.g., server name, debug mode, log levels, dependencies, module-specific parameters).
- **Automatic Module Discovery:** Supports automatic detection and loading of modules.
- **Declarative Configuration:** Modules can be enabled/disabled and configured declaratively.
- **Extensibility:** Create and add custom modules without modifying the core codebase. Modules follow a defined interface for easy integration.
- **FastMCP Standard Support:** Compatible with the FastMCP standard for improved interoperability.
- **Multiple Execution Methods:** Run the server via direct Python execution or using UV.
- **Integration:** Designed for integration with Claude Desktop and Cursor, supporting global and per-project MCP server configurations.
- **Development Tools:** Includes tools for development and testing (e.g., MCP Inspector for testing/debugging, log output for troubleshooting).
- **Troubleshooting Guidance:** Provides solutions for common issues such as module loading, character encoding, and connection problems.
- **Language:** Python

## Installation & Setup
- Clone the repository from GitHub.
- Install dependencies (`uv pip install mcp[cli]`).
- Configure the server and modules via `config.json`.
- Run the server with `python main.py` or `uv run main.py`.
- Integrate with Claude Desktop or Cursor as needed.

## Pricing
No pricing information is provided; the product appears to be open-source.

## Tags
`mcp`, `framework`, `extensible`, `server-management`