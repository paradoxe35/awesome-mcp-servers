# modelcontextprotocol/server-sentry

**Category:** Monitoring  
**Tags:** mcp, sentry, monitoring, error-tracking

## Description
modelcontextprotocol/server-sentry is a Model Context Protocol (MCP) server that integrates with Sentry.io to retrieve and analyze issues. It provides tools to inspect error reports, stack traces, and other debugging information from your Sentry account.

## Features
- Integrates with Sentry.io for error tracking and performance monitoring.
- Retrieves and analyzes issues reported to Sentry.
- Tools for inspecting error reports and stack traces.
- Supports configuration for various environments:
  - Claude Desktop
  - Visual Studio Code (VS Code)
  - Zed
- Can be installed via `uvx` (no specific installation needed) or via `pip`.
- Includes debugging support with the MCP inspector.
- Configuration can be shared via workspace files for collaborative environments.
- Licensed under the MIT License.

## Installation
- **Using uv (recommended):**
  - No specific installation required; use `uvx` to run directly.
- **Using pip:**
  - Install via pip and run as a script.

## Configuration
- Supports configuration via JSON files for different environments (Claude Desktop, VS Code, Zed).
- Allows sharing configuration in collaborative development setups.

## Debugging
- Use the MCP inspector to debug the server.
- Supports development and debugging in custom directories.

## Pricing
- Open source under the MIT License (free to use, modify, and distribute).

## Source
[GitHub Repository](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry)