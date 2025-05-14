# legion-mcp

**Universal database MCP server supporting multiple database types (PostgreSQL, MySQL, Oracle, etc.), ideal for heterogeneous MCP environments.**

- **Source:** [https://github.com/TheRaLabs/legion-mcp](https://github.com/TheRaLabs/legion-mcp)
- **Category:** database-messaging-mcp-servers
- **Tags:** mcp, database, multi-database, universal, integration

## Features
- **Multi-Database Support:**
  - Supports PostgreSQL, Redshift, CockroachDB, MySQL, RDS MySQL, Microsoft SQL Server, BigQuery, Oracle DB, and SQLite.
  - Connect to and manage multiple databases simultaneously, each with a unique ID.
  - Database schemas are represented programmatically for easy access to tables and columns.
- **MCP Integration:**
  - Uses the Model Context Protocol (MCP) Python SDK for maintaining context in AI applications.
  - Integrates with Legion Query Runner for database connectivity.
- **Flexible Configuration & Deployment:**
  - Can be configured for single or multiple databases via environment variables or command-line arguments.
  - Installation via UV (recommended) or pip.
  - Automatic or custom database ID assignment.
- **Schema Representation:**
  - Schemas are exposed as resources, allowing retrieval of schema info for one or all databases.
  - Easy programmatic access to table and column metadata.
- **Tools and Endpoints:**
  - `execute_query`: Run SQL queries and return results as markdown tables.
  - `execute_query_json`: Run SQL queries and return results as JSON.
  - `get_table_columns`: Retrieve column names for tables.
  - `get_table_types`: Retrieve column types for tables.
  - `get_query_history`: View recent query history.
  - `list_databases`: List all connected databases.
  - `get_database_info`: Get detailed database and schema info.
  - `find_table`: Find which database contains a given table.
  - `describe_table`: Get detailed table descriptions.
  - `get_table_sample`: Retrieve sample data from a table.
- **Prompts for Query Assistance:**
  - `sql_query`: Generate SQL queries.
  - `explain_query`: Explain SQL queries.
  - `optimize_query`: Optimize SQL queries.
  - `select_database`: Assist in choosing a database for queries.
- **Development & Testing:**
  - Includes tooling for development, testing, and running an MCP Inspector.
- **Open Source:**
  - Licensed under GPL.

## Pricing
No pricing information is provided; legion-mcp is open source under the GPL license.