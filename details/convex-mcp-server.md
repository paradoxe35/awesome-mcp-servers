# convex-mcp-server

Convex MCP Server is a beta implementation of a Model Context Protocol (MCP) server for Convex deployments. It enables AI agents and tools to interact with Convex databases via a standardized protocol, providing facilities for introspection, table exploration, function execution, and more.

## Features

- **Database Introspection**: Agents can inspect Convex deployments, including available tables and functions.
- **Table Exploration**:
  - List all tables within a deployment.
  - Retrieve declared and inferred schemas for tables.
  - Paginate through table documents using the `data` tool.
- **Query Execution**:
  - Agents can write and execute one-off, sandboxed JavaScript queries against the data (read-only; cannot modify the database).
- **Function Management**:
  - List all deployed functions, including their types and visibility, via the `functionSpec` tool.
  - Execute functions using the `run` tool, with automatic handling of required parameters.
- **Deployment Management**:
  - List and select among multiple deployments (production, development, previews) within a project.
  - Use a "deployment selector" for subsequent tool calls.
- **Environment Variable Management**:
  - List, get, set, and remove environment variables for a deployment (`envList`, `envGet`, `envSet`, `envRemove`).
- **Standardized MCP Tools Interface**:
  - Exposes all functionality via MCP "tools" for compatibility with agents like Cursor and Claude Desktop.
  - Utilizes simple string arguments for tool calls.
- **Global Server Operation**:
  - Runs as a global MCP server, accessible to all Convex projects on a machine.
  - Uses stdio as the transport protocol on a locally running server.
- **Agent Compatibility**:
  - Tested primarily with Cursor (macOS Sequoia), but designed for compatibility with other agents (e.g., Windsurf, Claude Desktop) via `npx -y convex@latest mcp start`.
- **Secure Execution**:
  - All custom query code is sandboxed to prevent database modifications.

## Installation

- Add the MCP server in supported agents (e.g., Cursor) by configuring the appropriate command (`npx -y convex@latest mcp start`).

## Pricing

- No pricing information is provided in the available content.

## Source

[convex-mcp-server on stack.convex.dev](https://stack.convex.dev/convex-mcp-server)

## Tags

mcp, convex, database, query