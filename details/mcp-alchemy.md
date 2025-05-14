# mcp-alchemy

A universal, SQLAlchemy-based MCP (Model Context Protocol) server that enables LLMs (e.g., Claude Desktop) to connect to and interact with a variety of relational databases, providing schema insight, relationship exploration, and advanced query execution.

**Source:** [GitHub - runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy)

## Features

- **Multi-Database Support:**
  - Works with PostgreSQL, MySQL, MariaDB, SQLite, Oracle, MS SQL Server, and any SQLAlchemy-compatible database.
  - Default drivers for SQLite, MySQL/MariaDB (via pymysql), PostgreSQL (via psycopg2-binary). Additional drivers can be installed as needed.

- **Database Exploration & Insight:**
  - Provides tools to list all tables (`all_table_names`).
  - Search/filter tables by substring (`filter_table_names`).
  - Retrieve detailed table schemas, including column names/types, primary keys, foreign key relationships, and nullable flags (`schema_definitions`).
  - Displays relationships between tables.

- **Query Execution:**
  - Execute arbitrary SQL queries (`execute_query`) with vertical output format.
  - Smart truncation for large results.
  - Clean display of NULL values and ISO formatted dates.
  - Full result set access via `claude-local-files` integration.
  - Clear, separated row output for easy reading.

- **Large Dataset Handling:**
  - Integration with `claude-local-files` enables analysis and artifact creation for very large datasets.
  - Export and further process large result sets when `CLAUDE_LOCAL_FILES_PATH` is set.

- **Configuration:**
  - Easily integrated with Claude Desktop via `claude_desktop_config.json`.
  - Supports environment variables:
    - `DB_URL` (required): SQLAlchemy database URL.
    - `CLAUDE_LOCAL_FILES_PATH`: Directory for full result sets (optional).
    - `EXECUTE_QUERY_MAX_CHARS`: Maximum query output length (optional, default 4000).

- **API Tools:**
  - `all_table_names`, `filter_table_names`, `schema_definitions`, `execute_query`.

- **Installation & Usage:**
  - Simple install via git clone and `uv` (Python environment tool).
  - Example configuration snippets provided for quick setup.

- **Open Source & Contributions:**
  - Licensed under Mozilla Public License 2.0 (MPL-2.0).
  - Actively welcomes contributions: bug reports, feature requests, documentation, and code.

## Pricing

- **Open Source:**
  - No pricing; distributed under the MPL-2.0 license. Free to use, modify, and contribute.

## Tags

`mcp` `sqlalchemy` `database` `multi-database` `schema-inspection`

## Category

database-messaging-mcp-servers