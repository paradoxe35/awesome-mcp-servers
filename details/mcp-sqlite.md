# mcp-sqlite

A Model Context Protocol (MCP) server providing comprehensive SQLite database interaction capabilities, designed for MCP workloads.

- **Source:** [GitHub Repository](https://github.com/jparkerweb/mcp-sqlite)
- **Category:** database-messaging-mcp-servers
- **Tags:** mcp, sqlite, database, integration

## Features
- **Database Information:**
  - `db_info`: Retrieve detailed information about the connected SQLite database.
  - `list_tables`: List all tables present in the database.
  - `get_table_schema`: Get detailed schema information for a specific table.
- **CRUD Operations:**
  - `create_record`: Insert new records into a table.
  - `read_records`: Query records from a table with optional filters.
  - `update_records`: Update records in a table that match specified conditions.
  - `delete_records`: Delete records from a table that match specified conditions.
- **Custom Queries:**
  - `query`: Execute custom SQL queries against the connected SQLite database.
- **Integration:**
  - Designed to be used as an MCP server, with configuration via IDE MCP Server settings.
  - Supports specifying the database path as a command-line argument.

## Pricing
No pricing information is provided; the project appears to be open source.