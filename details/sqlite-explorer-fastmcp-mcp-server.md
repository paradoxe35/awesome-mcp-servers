# sqlite-explorer-fastmcp-mcp-server

A read-only MCP server for SQLite databases, built with the FastMCP framework. It provides safe exploration and query validation for LLMs (Large Language Models), enabling them to interact with SQLite databases securely and efficiently.

## Features
- **Read-only Access:** Provides safe, read-only access to SQLite databases via the Model Context Protocol (MCP).
- **Built with FastMCP:** Utilizes the FastMCP framework for secure and efficient operations.
- **LLM Integration:** Enables LLMs to explore and query SQLite databases.
- **Query Validation:** Includes built-in safety features and validation to ensure that only safe queries are executed.
- **Exposed Tools:**
  - `read_query`: Execute SELECT queries with safety checks.
  - `list_tables`: List all available tables in the database.
  - `describe_table`: Retrieve detailed schema information for a specific table.
- **Development Documentation:** Includes documentation files to assist with development and LLM integration.
- **Installation Options:** Can be installed for use with Claude Desktop or the Cline VSCode plugin.
- **Environment Variables:** Requires certain environment variables to be set for operation.
- **Requirements:** All dependencies are listed in the `requirements.txt` file for easy installation.

## Category
- database-messaging-mcp-servers

## Tags
- mcp
- sqlite
- database
- read-only

## Source
[https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server)

## Pricing
No pricing information provided; the project appears to be open source.