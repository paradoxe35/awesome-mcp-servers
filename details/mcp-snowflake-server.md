# mcp-snowflake-server

**Category:** database-messaging-mcp-servers  
**Tags:** snowflake, database, mcp, data-access  
**Source:** [GitHub Repository](https://github.com/isaacwasserman/mcp-snowflake-server)

## Overview
mcp-snowflake-server is an implementation of the Model Context Protocol (MCP) server that enables database interaction with Snowflake. It allows users to run SQL queries, perform schema operations, and track insights via a memo resource using the MCP protocol.

## Features
- **Dynamic Memo Resource**
  - `memo://insights`: Continuously updated data insights memo that aggregates discovered insights during analysis. Auto-updates as new insights are discovered via the `append_insight` tool.

- **Query Tools**
  - `read_query`: Execute SELECT queries to read data from the database. Returns query results as an array of objects.
  - `write_query` (requires `--allow-write` flag): Execute INSERT, UPDATE, or DELETE queries. Returns the number of affected rows.
  - `create_table` (requires `--allow-write` flag): Create new tables in the database. Returns confirmation of table creation.

- **Schema Tools**
  - `list_tables`: Retrieve a list of all tables in the database.
  - `describe_table`: View column information for a specific table, returning column definitions with names and types.

- **Analysis Tools**
  - `append_insight`: Add new data insights to the memo resource, triggering an update of the `memo://insights` resource.

- **Configurable Connection**
  - Allows specifying Snowflake connection parameters (account, warehouse, user, password, role, database, schema).
  - Optional parameters for logging (`--log_dir`, `--log_level`) and tool exclusion (`--exclude_tools`).
  - `--allow_write` flag enables write operations (not recommended by default).

- **Integration**
  - Can be installed and integrated with Claude Desktop via Smithery, UVX, or local setup.

## Pricing
No pricing information provided; the project is open-source under the GPL-3.0 license.
