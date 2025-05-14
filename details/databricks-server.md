# databricks-server

A Model Context Protocol (MCP) server for executing SQL queries against Databricks via the Statement Execution API. It enables AI assistants and MCP clients to directly query Databricks data warehouses, analyze schemas, and retrieve structured results.

**Source:** [GitHub - RafaelCartenet/mcp-databricks-server](https://github.com/RafaelCartenet/mcp-databricks-server)

## Features
- Executes SQL queries against Databricks data warehouses using the Statement Execution API
- Provides tools for:
  - `execute_sql_query`: Execute a SQL query and return results
  - `list_schemas`: List all available schemas in a specific catalog
  - `list_tables`: List all tables in a specific schema
  - `describe_table`: Describe a table's schema
- Supports Agent mode for iterating over multiple requests to perform complex tasks
- Can be integrated with Unity Catalog Metadata for enhanced schema and data exploration
- Handles long-running queries by polling the Databricks API, with configurable timeout (default 10 minutes)
- Can be run in standalone mode or integrated with tools like Cursor's AI assistant
- Flexible setup via environment variables or .env file
- Enforces SQL warehouse, token, and data access permissions for secure operation

## Category
**data-access-integration-mcp-servers**

## Tags
`mcp`, `databricks`, `sql`, `data-exploration`, `ai-assistant`

## Pricing
No pricing information provided; appears to be open source.