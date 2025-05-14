# mysql-mcp-server

A Model Context Protocol (MCP) server providing read-only access to MySQL databases for model-based systems and automation workflows.

- **Source:** [GitHub Repository](https://github.com/dave-wind/mysql-mcp-server)
- **Category:** database-messaging-mcp-servers
- **Tags:** mcp, mysql, database, read-only
- **License:** MIT

## Features

- **Read-Only Database Access:** Enforces read-only operations via SQL validation and READ ONLY transactions.
- **Schema Discovery:** Automatically discovers and exposes database table structures, including column names and data types, as JSON schema.
- **SQL Query Execution:** Provides a tool for executing SELECT statements against the connected MySQL database.
- **Model Context Protocol Compliance:** Implements MCP specification for integration with compatible LLMs (Large Language Models).
- **Simple Configuration:** Minimal setup required, configurable via JSON file.
- **Integration with Automation:** Designed to support automation workflows, including n8n integration.
- **Security Model:**
  - Only allows SELECT queries (no INSERT/UPDATE/DELETE/DDL).
  - All queries are executed within READ ONLY transactions.
  - No schema modification operations are supported (CREATE, ALTER, DROP, etc.).
- **Communication:** Uses JSON-RPC over stdio following the MCP specification.
- **Node.js Support:** Requires Node.js v18 or newer.
- **Installation:**
  - Install globally via npm: `npm install @davewind/mysql-mcp-server -g`
  - Configuration via JSON file to specify connection details and MCP server commands.

## Pricing

- **Open Source:** Free under the MIT license.