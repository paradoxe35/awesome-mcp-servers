# postgres-mcp

**Source:** [https://github.com/crystaldba/postgres-mcp](https://github.com/crystaldba/postgres-mcp)

**Category:** database-messaging-mcp-servers

**Tags:** mcp, postgresql, database, performance

---

## Description

Postgres MCP (Model Context Protocol) Pro is an open source MCP server for PostgreSQL, designed to assist in development, performance analysis, tuning, and health checks. It provides deterministic tools and classical optimization algorithms to complement generative AI and streamline the management and optimization of Postgres databases.

---

## Features

### Database Health Monitoring
- Detects unused and duplicate indexes
- Monitors cache hit rates
- Checks connection utilization
- Identifies vacuum needs before problems occur
- Performs comprehensive health checks including buffer cache hit rates, connection health, constraint validation, index health (duplicate/unused/invalid), sequence limits, and vacuum health

### Index Tuning
- Generates optimal indexes using proven algorithms (inspired by Microsoft's Anytime Algorithm)
- Validates AI-suggested indexes
- Simulates performance impacts with hypothetical indexes using the `hypopg` extension
- Balances performance gain vs storage costs using cost-benefit analysis
- Supports workload compression and query normalization for better tuning recommendations

### Schema Intelligence
- Provides detailed schema information for tables, views, and more
- Context-aware SQL generation
- Recommends optimal column selection
- Lists all database schemas and objects
- Provides object details (columns, constraints, indexes)

### Protected Execution
- Unrestricted mode: full read/write for development
- Restricted mode: read-only with resource limits for production
- Safe SQL parsing to prevent security issues (e.g., blocks COMMIT/ROLLBACK in restricted mode)

### API and Tooling
- Implements MCP tools for:
    - Listing schemas and objects
    - Fetching object details
    - Executing SQL (with read-only limitations in restricted mode)
    - Explaining queries with hypothetical indexes
    - Reporting slowest queries (using `pg_stat_statements`)
    - Analyzing workload and query indexes
    - Performing comprehensive health checks
- Supports both stdio and Server-Sent Events (SSE) transports for integration with various clients

### Integration and Extensibility
- Designed to work with AI assistants (e.g., Claude Desktop, Cursor, etc.)
- Installation via Docker or Python (pipx/uv)
- Optional use of `pg_stat_statements` and `hypopg` extensions for advanced analysis
- Uses psycopg3 for asynchronous Postgres connections

### Security and Reliability
- Read-only transaction enforcement in restricted mode
- SQL parsing to block unsafe statements
- Query execution time limits in restricted mode

### Version Support
- Tested with PostgreSQL 15, 16, and 17 (aims to support 13 through 17)

---

## Pricing

No pricing information was provided. The project is open source.

---

## Installation Options
- Docker image (recommended for most users)
- Python package (via pipx or uv)

---

## Requirements
- PostgreSQL database (with optional `pg_stat_statements` and `hypopg` extensions for advanced features)
- Docker or Python environment

---

## Maintainer
- Created and maintained by Crystal DBA.