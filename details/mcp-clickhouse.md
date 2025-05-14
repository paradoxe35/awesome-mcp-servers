# mcp-clickhouse

**MCP server for ClickHouse database**

[Source on GitHub](https://github.com/ClickHouse/mcp-clickhouse)

## Description
mcp-clickhouse is an open-source MCP protocol server for integrating with ClickHouse databases. It enables schema inspection and query execution capabilities via the MCP protocol, making it possible to interact with ClickHouse clusters in a controlled and secure manner.

## Features
- **Execute SQL queries**: Run SELECT queries against your ClickHouse cluster (queries are executed with `readonly = 1` for safety).
- **List databases**: Retrieve a list of all databases available in your ClickHouse cluster.
- **List tables**: List all tables in a specified database, with support for parameterized views.
- **Optimized row counts**: Improved performance for retrieving table row counts.
- **Environment-based configuration**: Configure ClickHouse connection details (host, port, user, password, database, SSL settings, timeouts) via environment variables or config files.
- **Secure connections**: Supports HTTPS (secure) connections and SSL certificate verification options.
- **Customizable timeouts**: Configure connection and query timeouts for handling long-running queries.
- **Integration with Claude Desktop**: Can be configured as an MCP server within Claude Desktop with JSON-based settings.
- **Docker support for development**: Includes Docker Compose setup for local development and testing environments.
- **Test and development tools**: Includes scripts and instructions for running tests, linting, and development server.

## Configuration Options
- `CLICKHOUSE_HOST` (required): Hostname of your ClickHouse server.
- `CLICKHOUSE_USER` (required): Username for authentication.
- `CLICKHOUSE_PASSWORD` (required): Password for authentication.
- `CLICKHOUSE_PORT`: Port number (default 8443 for HTTPS, 8123 for HTTP).
- `CLICKHOUSE_SECURE`: Enable/disable HTTPS (default: true).
- `CLICKHOUSE_VERIFY`: Enable/disable SSL certificate verification (default: true).
- `CLICKHOUSE_CONNECT_TIMEOUT`: Connection timeout (default: 30 seconds).
- `CLICKHOUSE_SEND_RECEIVE_TIMEOUT`: Query timeout (default: 300 seconds).
- `CLICKHOUSE_DATABASE`: Default database to connect to (optional).

## License
Apache-2.0

## Pricing
No pricing information provided; mcp-clickhouse is open-source software.

## Tags
mcp, clickhouse, database, integration
