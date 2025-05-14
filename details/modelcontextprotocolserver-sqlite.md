# modelcontextprotocol/server-sqlite

**Category:** database-messaging-mcp-servers  
**Tags:** mcp, database, sqlite, open-source  
**Source:** [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)

## Overview
modelcontextprotocol/server-sqlite is a Model Context Protocol (MCP) server that provides database interaction and business intelligence capabilities using SQLite. It enables running SQL queries, business data analysis, and automatic generation of business insight memos, supporting MCP-based automation workflows.

## Features
- **Business Insights Memo Resource**
  - `memo://insights`: A continuously updated resource aggregating business insights discovered during analysis.
  - Auto-updated as new insights are added via the append-insight tool.

- **Demonstration Prompt**
  - `mcp-demo`: Interactive prompt guiding users through database operations.
    - Requires a `topic` argument (business domain to analyze).
    - Generates appropriate database schemas and sample data.
    - Guides users through analysis and insight generation.
    - Integrates with the business insights memo.

- **Core Tools**
  - **Query Tools**
    - `read_query`: Execute SELECT queries and return results as array of objects.
    - `write_query`: Execute INSERT, UPDATE, or DELETE queries; returns number of affected rows.
    - `create_table`: Create new tables with a given SQL statement; returns confirmation.
  - **Schema Tools**
    - `list_tables`: Retrieve a list of all tables in the database.
    - `describe_table`: View schema information (column names and types) for a specific table.
  - **Analysis Tools**
    - `append_insight`: Add new business insights to the memo resource; triggers memo update.

- **Deployment and Usage**
  - Can be integrated with Claude Desktop via configuration for both `uv` and `docker` commands.
  - Docker support for containerized deployment.
  - Configurable database path.

- **Open Source**
  - Licensed under the MIT License (free to use, modify, and distribute).

## Pricing
No pricing or paid plans are specified. The project is open-source under the MIT License.