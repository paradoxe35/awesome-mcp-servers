# mcp-server-trino

[Source Code](https://github.com/Dataring-engineering/mcp-server-trino)

## Description
mcp-server-trino is an MCP (Model-Control-Protocol) server implementation that enables data querying and access from Trino clusters using the MCP protocol. It provides a bridge between Trino's distributed SQL query engine and MCP-compatible tools and workflows.

## Features
- **List Trino Tables as MCP Resources**: Exposes Trino tables as resources over the MCP protocol.
- **Read Table Contents**: Allows reading the contents of Trino tables through MCP.
- **Execute Arbitrary SQL Queries**: Provides a tool for executing arbitrary SQL queries against Trino clusters.
- **Python-based Implementation**: Written in Python, utilizing the `trino.dbapi` and `mcp` libraries.
- **Environment-Based Configuration**: Reads Trino connection details (host, port, user, password, catalog, schema) from environment variables for flexible deployment.
- **Compatible with Trino's Python Client**: Integrates with Trino’s official Python driver for connectivity.
- **Supports Modern Python**: Requires Python 3.9+ (or a compatible version with dependencies).
- **Open Source**: Licensed under the MIT license.

## Configuration
The server is configured via environment variables:
- `TRINO_HOST`: Trino server hostname or IP (default: `localhost`)
- `TRINO_PORT`: Trino server port (default: `8080`)
- `TRINO_USER`: Trino user name (required)
- `TRINO_PASSWORD`: Trino password (optional)
- `TRINO_CATALOG`: Default Trino catalog (required)
- `TRINO_SCHEMA`: Default Trino schema (required)

## Category
- database-messaging-mcp-servers

## Tags
`mcp`, `trino`, `database`, `data-access`

## Pricing
No pricing information is provided; the project is open source under the MIT license.