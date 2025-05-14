# tuannvm/mcp-trino

**Source:** [https://github.com/tuannvm/mcp-trino](https://github.com/tuannvm/mcp-trino)

**Category:** database-messaging-mcp-servers

**Tags:** mcp, trino, database, golang

## Description
A high-performance Model Context Protocol (MCP) server for Trino implemented in Go. It enables AI assistants and applications to interact with Trino's distributed SQL query engine via standardized MCP tools.

## Features
- **High-Performance MCP Server:** Written in Go for efficiency and reliability.
- **Trino Integration:** Connects to Trino (formerly PrestoSQL), a distributed SQL query engine for analytics on large datasets.
- **MCP Tools Provided:**
  - `execute_query`: Execute SQL queries with full support for complex analytics.
  - `list_catalogs`: List all catalogs in the Trino server.
  - `list_schemas`: List all schemas within a given catalog.
  - `list_tables`: List all tables within a given schema.
  - `get_table_schema`: Retrieve detailed schema information (columns, data types, nullability) for a specific table.
- **Multiple Installation Methods:**
  - Homebrew (macOS, Linux)
  - Manual download of pre-built binaries (macOS, Linux, Windows, ARM/x86_64)
  - Docker image
  - Build from source
- **Integration with AI Applications:**
  - Cursor
  - Claude Desktop
  - Windsurf
  - ChatWise
- **Transport Modes:**
  - `stdio` (default)
  - `http` (with optional Server-Sent Events for live updates)
- **Configurable via Environment Variables:**
  - Trino host, port, user, password, catalog, schema, SSL options, and more.
  - Control allowed query types (read-only by default, can enable write queries).
- **Security:**
  - By default, only read-only SQL queries are allowed to prevent SQL injection.
  - Option to enable write queries if needed.
- **End-to-End AI Workflow Support:**
  - Designed for conversational data exploration and querying via AI assistants.
- **CI/CD:**
  - Uses GitHub Actions for automated code quality, security, and testing checks.
  - Automated releases with GoReleaser.
- **Open Source (MIT License):**
  - Contributions are welcome.

## Configuration Options
- Environment variables can control all aspects of server operation, including connection settings, transport mode, security, and more.
- Supports both HTTPS (default) and HTTP connections to Trino.

## Pricing
- **Free and Open Source** (MIT License). No pricing plans.
