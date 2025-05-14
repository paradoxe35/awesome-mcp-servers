# Clickzetta Server

A Model Context Protocol (MCP) server for interacting with ClickZetta Lakehouse databases, enabling SQL query execution, schema exploration, and documentation of data insights via natural language interfaces.

## Features
- **MCP Server Implementation**: Acts as a bridge between MCP clients and ClickZetta Lakehouse databases.
- **SQL Query Execution**:
  - `read_query`: Execute read-only SQL queries.
  - `write_query`: Execute write SQL queries when enabled with `--allow-write`.
  - `create_table`: Create tables in the database (requires `--allow-write`).
- **Schema Exploration**:
  - `list_tables`: List all available tables in the database.
  - `describe-table`: Get schema details for a specific table.
- **Data Insights Memo**: Interact with a memo resource that documents and presents insights from the database.
- **Natural Language Interaction**: Designed for use with tools like Claude Desktop, allowing users to ask questions in natural language and receive insights or query results.
- **Stdio Communication**: Runs as a local server and communicates with MCP clients over standard input/output.
- **Credential Management**: Requires configuration of ClickZetta Lakehouse credentials via a `.env` file.
- **Integration**: Can be integrated with Claude Desktop and potentially other MCP-compatible clients.
- **Installation Methods**:
  - Via direct package installation (tested on MacOS).
  - Planned/experimental support for installation via Smithery and UVX.

## Pricing
No pricing information is provided; the source code is available as an open source project.

## Source
[Clickzetta Server on GitHub](https://github.com/MCP-Mirror/yunqiqiliang_mcp-clickzetta-server)