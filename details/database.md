# Database (DBHub)

**Source:** [GitHub - bytebase/dbhub](https://github.com/bytebase/dbhub)

## Description
DBHub is a universal database gateway implementing the Model Context Protocol (MCP) server interface. It allows MCP-compatible clients to connect to and explore multiple database types, including PostgreSQL, MySQL, Microsoft SQL Server, SQLite, and more.

## Features
- **Universal MCP Server:** Acts as a gateway for MCP-compatible clients (e.g., Claude Desktop, Cursor) to connect to various databases.
- **Supported Database Types:**
  - PostgreSQL
  - MySQL
  - Microsoft SQL Server
  - SQLite
  - (Mentions support for Redshift, CockroachDB, RDS MySQL, BigQuery, Oracle DB, though primary support for first four is detailed)
- **Demo Mode:** Includes a bundled SQLite "employee" sample database for testing, with tables for employees, departments, salaries, etc.
- **Resource Exploration:**
  - List schemas, tables, table structures, indexes, and procedures (procedure support varies by DB type).
- **Database Tools:**
  - Execute queries (`run_query`)
  - List available connectors (`list_connectors`)
- **Prompt Capabilities:**
  - Generate SQL statements (`generate_sql`)
  - Explain database elements (`explain_db`)
- **Flexible Connection:**
  - Connect to databases using DSN via command line, environment variable, or environment file.
  - Supports connection to local and remote databases.
- **Transport Modes:**
  - `stdio` (default): For direct integration with tools like Claude Desktop.
  - `sse`: For browser and network clients.
- **Docker and NPM Installation:**
  - Run as a Docker container or via NPM.
- **Open Source:**
  - Licensed under the MIT License.
  - Written primarily in TypeScript.
- **Integration Guides:**
  - Examples for integration with Claude Desktop and Cursor.
- **Customizable Command Line Options:**
  - `--demo`, `--dsn`, `--transport`, `--port`.
- **Development Ready:**
  - Setup scripts for development and production environments.
- **Sample Endpoints:**
  - Demo SSE endpoint available for testing with sample data.

## Pricing
No pricing information is provided. DBHub is open source and available under the MIT License.

## Tags
`mcp`, `database`, `postgresql`, `mysql`, `cloud`

## Category
`database-messaging-mcp-servers`