# Dbutils

[Source Code](https://github.com/donghao1393/mcp-dbutils)

## Description
Dbutils is an all-in-one MCP (Model Context Protocol) service that enables AI-powered data analysis by securely connecting to multiple types of databases (such as SQLite, MySQL, PostgreSQL, and more) through a unified configuration. It acts as a secure bridge between AI systems and databases, allowing safe, read-only data analysis without exposing or modifying the underlying data.

## Features
- **Multi-Database Support:** Connects to SQLite, MySQL, PostgreSQL, and potentially more through a single unified configuration.
- **MCP Protocol Compatible:** Works with any AI system or client supporting the MCP protocol, including Claude Desktop, Cursor, and others.
- **Strict Read-Only Operations:** Only allows SELECT queries; no data modification is possible.
- **Secure Architecture:**
  - No direct database access for AI; all access is brokered through Dbutils.
  - Each connection is isolated and managed separately.
  - Connections are established only as needed and closed immediately after use.
  - Automatic timeouts for long-running operations.
  - All data processing happens locally; no data is sent to external servers.
  - Minimum data exposure; only requested data is returned.
  - Connection credentials are never exposed to AI models.
  - Sensitive data (like passwords) are masked in logs.
  - Supports SSL/TLS for encrypted remote database connections.
  - Configuration via YAML files for security and clarity.
  - User-controlled database access.
  - Secure defaults with no extra configuration needed.
- **AI Tooling:**
  - List database tables.
  - View table schemas.
  - Run SELECT queries.
  - Analyze table statistics.
  - List table constraints.
  - Explain query execution plans.
  - Retrieve database performance metrics.
  - Analyze queries for optimization.
- **Simple Configuration:** All database connections are managed via a single YAML file.
- **Multiple Installation Methods:**
  - Via `uvx` (Python environment).
  - Via Docker container.
  - Via Smithery (for Claude integration).
- **Local Processing:** All operations are performed on the user's machine.
- **Open Source:** Licensed under the MIT License.

## System Requirements
- Python 3.10+
- Or Docker Desktop
- Or Node.js 14+ (for Smithery)
- Supported databases: SQLite 3.x, PostgreSQL 12+, MySQL 8+
- Supported AI clients: Any MCP-compatible client (Claude Desktop, Cursor, etc.)

## Pricing
Dbutils is open-source software released under the MIT License. There are no paid plans or commercial pricing.

## Tags
`mcp` `database` `data-analysis` `multi-database`