# go-mcp-mysql

A zero-dependency Model Context Protocol (MCP) server for interacting with MySQL, built in Go.

- **Source:** [https://github.com/Zhwt/go-mcp-mysql](https://github.com/Zhwt/go-mcp-mysql)
- **Category:** database-messaging-mcp-servers
- **Tags:** mcp, mysql, golang, database, schema-inspection

## Features
- Zero external dependencies; does not require Node.js or Python.
- Ready-to-use MCP server for MySQL automation and interaction.
- Supports CRUD operations on MySQL databases and tables.
- Configurable read-only mode to prevent unintended write operations.
- Option to check query plans using the `--with-explain-check` flag (runs EXPLAIN before executing queries).
- Command-line interface with support for various flags and options.
- Schema tools:
  - List databases
  - List tables
  - Create tables
  - Alter tables
  - Describe tables
- Data tools:
  - Read queries
  - Write queries
  - Update queries
  - Delete queries
- Can be installed via pre-built binary or built from source using Go.
- MIT License.

## Pricing
No pricing information provided. The project is open source under the MIT license.

## Notes
- This is a work in progress and may not yet be ready for production use.