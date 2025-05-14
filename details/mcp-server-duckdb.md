# mcp-server-duckdb

A Model Context Protocol (MCP) server implementation for DuckDB, providing database interaction capabilities through MCP tools.

- **Source:** [GitHub Repository](https://github.com/ktanaka101/mcp-server-duckdb)
- **License:** MIT
- **Category:** database-messaging-mcp-servers
- **Tags:** mcp, database, duckdb, open-source

## Features

- **DuckDB Integration:** Interact with DuckDB databases via the Model Context Protocol.
- **Database Operations:**
  - `read-query`: Execute SELECT queries to read data from the database.
  - `write-query`: Execute INSERT, UPDATE, or DELETE queries to modify data.
  - `create-table`: Create new tables in the database.
  - `list-tables`: List all tables in the database.
  - `describe-table`: Get schema information for specific tables.
- **Read-Only Mode:**
  - Option to run the server in read-only mode, disabling all write operations (`write-query`, `create-table`).
  - Enhances security by preventing any database modifications when enabled.
- **Automatic Database Creation:**
  - The server creates the DuckDB database file and parent directories if they do not exist (unless in read-only mode).
- **Configuration Options:**
  - `db-path`: Required parameter specifying the path to the DuckDB database file.
  - `--readonly`: Optional flag to run the server in read-only mode.
- **Installation:**
  - Installable via Smithery CLI for integration with tools like Claude Desktop.
- **Development and Debugging:**
  - Written in Python, uses the uv package manager.
  - Supports debugging with the MCP Inspector, providing visibility into request/response communication, tool execution, server state, and errors.

## Pricing

No pricing information is provided; the project is open-source under the MIT license.

## Contributors

- Kentaro Tanaka (@ktanaka101)
- Henry Mao (@calclavia)
- Frank Fiegel (@punkpeye)
