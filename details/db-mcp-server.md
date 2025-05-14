# db-mcp-server

A high-performance multi-database MCP (Model Context Protocol) server built with Golang, designed to provide AI assistants with structured, unified access to multiple databases.

- **Source:** [https://github.com/FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server)
- **Category:** database-messaging-mcp-servers
- **Tags:** mcp, database, golang, mysql, postgresql

## Features

- **Multi-Database Support:**
  - Connects to and interacts with multiple databases concurrently
  - Supported databases:
    - **MySQL:** Full support for queries, transactions, schema analysis, and performance insights
    - **PostgreSQL (v9.6-17):** Full support for queries, transactions, schema analysis, and performance insights
    - **TimescaleDB:** Full support including hypertables, time-series queries, continuous aggregates, compression, and retention policies

- **Dynamic Tool Generation:**
  - Automatically generates specialized tools for each connected database

- **Query Tools:**
  - `query_<db_id>`: Execute SELECT queries and get results as tabular datasets
  - `execute_<db_id>`: Run data manipulation statements (INSERT, UPDATE, DELETE)
  - `transaction_<db_id>`: Begin, commit, and rollback transactions

- **Schema Tools:**
  - `schema_<db_id>`: Get information about tables, columns, indexes, and foreign keys
  - `generate_schema_<db_id>`: Generate SQL or code from database schema

- **Performance Tools:**
  - `performance_<db_id>`: Analyze query performance and get optimization suggestions

- **TimescaleDB Specialized Tools:**
  - `timescaledb_<db_id>`: General TimescaleDB operations
  - `create_hypertable_<db_id>`: Convert standard tables to hypertables
  - `list_hypertables_<db_id>`: List all hypertables
  - `time_series_query_<db_id>`: Execute optimized time-series queries with bucketing
  - `time_series_analyze_<db_id>`: Analyze time-series data patterns
  - `continuous_aggregate_<db_id>`: Create materialized views that auto-update
  - `refresh_continuous_aggregate_<db_id>`: Manually refresh continuous aggregates

- **Deployment Options:**
  - Docker deployment
  - STDIO mode (for IDE integration)
  - SSE mode (Server-Sent Events)
  - Source code installation

- **Configuration:**
  - Supports configuration via JSON files and command-line options

- **Clean Architecture:**
  - Follows clean architecture principles for maintainability

- **Logging:**
  - Verbose logging available for troubleshooting

## Pricing

- The project is open source and licensed under the MIT License. No pricing plans are specified.
