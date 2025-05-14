# supabase-mcp-server

Supabase MCP Server enables tools like Cursor and Windsurf to manage Supabase databases and execute SQL queries via the MCP (Model Context Protocol) protocol. It provides a feature-rich server for database management, SQL execution, and programmatic access to the Supabase Management API with built-in safety controls.

- **Source:** [https://github.com/alexander-zuev/supabase-mcp-server](https://github.com/alexander-zuev/supabase-mcp-server)

## Features

### Compatibility
- Supports Cursor, Windsurf, Cline, and any MCP client supporting the stdio protocol.

### SQL Query Execution
- Control over read-only and read-write modes for SQL queries.
- Robust transaction handling for both direct and pooled database connections.
- Supports:
  - Read operations (SELECT)
  - Data Manipulation Language (INSERT, UPDATE, DELETE)
  - Data Definition Language (CREATE, ALTER, DROP) (DDL requires read-write mode and sufficient permissions).
- Safety features:
  - Starts in read-only mode by default.
  - Requires explicit mode switch for write operations.
  - Automatically resets to read-only after write operations.
  - Intelligent transaction state detection.

### Database Exploration Tools
- `get_db_schemas`: List all database schemas with sizes and table counts.
- `get_tables`: List tables in a schema with sizes, row counts, and metadata.
- `get_table_schema`: Detailed table structure, columns, keys, relationships.
- `execute_sql_query`: Execute raw SQL queries with support for all PostgreSQL operations. Supports transaction control (BEGIN, COMMIT, ROLLBACK).

### Supabase Management API Access
- Manage Supabase projects via the Management API.
- Tools:
  - `send_management_api_request`: Send arbitrary requests with auto-injection of project ref and safety mode.
  - `get_management_api_spec`: Retrieve enriched API specification with safety information.
  - `get_management_api_safety_rules`: Retrieve all safety rules including blocked and unsafe operations.
  - `live_dangerously`: Switch between safe and unsafe modes.
- Safety features:
  - API methods categorized as safe, unsafe, or blocked.
  - Blocked operations (e.g., deleting projects/databases) are never allowed.
- Management API tools only work with remote Supabase projects.

### Supabase Auth Admin Tools
- Direct access to Supabase Auth Admin methods via Python SDK:
  - `get_user_by_id`, `list_users`, `create_user`, `delete_user`, `invite_user_by_email`, `generate_link`, `update_user_by_id`, and more.
  - Supports retrieving documentation for all Auth Admin methods.
  - Returns structured Python objects.
  - Handles UUID validation and error reporting.

### Installation & Configuration
- Installable via pipx, uv, or manually from source.
- Compatible with Python 3.12+ and PostgreSQL 16+.
- Supports both local and remote Supabase instances.
- Configuration via environment variables, local `.env` file, or global config file.

### Logging & Debugging
- Writes detailed logs to a local log file for troubleshooting.
- Includes an MCP Inspector tool for debugging MCP server issues.

### Other Features
- Pre-built tools for seamless integration with Cursor & Windsurf.
- Dead-simple install & setup via package manager.
- Supports multiple Supabase regions.

### Roadmap Highlights
- Stronger SQL query validation.
- Improved access to API specs and logs.
- CLI integration and better local database management support in future releases.

## Pricing
No pricing information is provided; the project is open source under the Apache-2.0 license.
