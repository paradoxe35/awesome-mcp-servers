# designcomputer/mysql_mcp_server

A Model Context Protocol (MCP) server that enables secure, structured communication between AI applications and MySQL databases. It is intended as a protocol implementation for use as a bridge between AI hosts and MySQL, not as a standalone server.

**Source:** [https://github.com/designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server)

## Features
- Lists available MySQL tables as resources
- Reads table contents
- Executes SQL queries with error handling
- Secure database access via environment variables
- Comprehensive logging of database operations
- Configurable via environment variables (MYSQL_HOST, MYSQL_PORT, MYSQL_USER, MYSQL_PASSWORD, MYSQL_DATABASE)
- Designed for integration with AI applications (e.g., Claude Desktop)
- Supports debugging and testing with MCP Inspector
- Can be installed via pip or Smithery CLI
- Security best practices recommended, including minimal privilege user and query whitelisting
- MIT licensed, open source

## Security Guidelines
- Never commit credentials or environment variables
- Use a dedicated MySQL user with minimal permissions
- Avoid using root or administrative accounts
- Restrict access to necessary operations only
- Enable logging for audit purposes
- Regularly review security of database access

## Installation
- Install via pip: `pip install mysql-mcp-server`
- Or via Smithery CLI for Claude Desktop: `npx -y @smithery/cli install mysql-mcp-server --client claude`

## Development
- Clone repository and set up Python virtual environment
- Install development dependencies (`pip install -r requirements-dev.txt`)
- Run tests with pytest

## License
MIT License

## Pricing
No pricing information is provided; this is an open source project under the MIT License.