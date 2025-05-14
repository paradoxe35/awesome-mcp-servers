# Dbs

A Model Context Protocol (MCP) implementation for connecting to and working with various database systems, serving as a versatile MCP server.

- **Source:** [GitHub Repository](https://github.com/cuongtl1992/mcp-dbs)
- **Category:** database-messaging-mcp-servers
- **Tags:** mcp, database, multi-database, integration

## Features

- **Supports Multiple Databases:**
  - SQLite
  - PostgreSQL
  - SQL Server
  - MongoDB
- **Integration with LLMs:**
  - Can be integrated with Claude Desktop and similar LLM tools for database access.
- **Flexible Server Modes:**
  - Runs by default in SSE (Server-Sent Events) mode on port 3001
  - Custom port support via `--port` option
  - STDIO mode for tools that communicate over standard input/output via `--stdio` option
- **Environment Variable Configuration:**
  - Database connections configurable via environment variables (takes precedence over tool config)
- **MCP Tools Exposed:**
  - `connect-database`: Connect to a database (parameters for SQLite, PostgreSQL, SQL Server, MongoDB)
  - `disconnect-database`: Disconnect from a database
  - `execute-query`: Execute queries that return results (works with SQL and MongoDB)
  - `execute-update`: Execute queries that do not return results (e.g., INSERT, UPDATE, DELETE; works with SQL and MongoDB)
- **MCP Resources Exposed:**
  - `Database Schema`: Returns schema info for all tables and columns
  - `Table Schema`: Returns schema info for a specific table
  - `Tables List`: Returns a list of all tables in the database
- **Testing and Development:**
  - Includes a test suite for development
- **Open Source:**
  - Licensed under MIT

## Pricing

No pricing information provided; the project is open source under the MIT license.