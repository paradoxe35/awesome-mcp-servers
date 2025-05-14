# nile-mcp-server

**Category:** database-messaging-mcp-servers  
**Tags:** mcp, postgresql, database, ai-integration  
**Source:** [GitHub Repository](https://github.com/niledatabase/nile-mcp-server)

## Description
nile-mcp-server is a Model Context Protocol (MCP) server for the Nile database platform. It enables management and querying of Postgres databases, tenants, users, and authentication, and is designed for integration with LLM (Large Language Model) applications. The server provides a standardized interface for interacting with Nile's Postgres-based platform.

## Features
- **Database Management:**
  - Create, list, get details, and delete databases.
- **Credential Management:**
  - Create and list database credentials.
- **Region Management:**
  - List available regions for database creation.
- **SQL Query Execution:**
  - Execute SQL queries directly on Nile databases.
  - Results are formatted as markdown tables.
  - Supports automatic credential management and secure SSL connections.
- **MCP Protocol Support:**
  - Full implementation of the Model Context Protocol for LLM integration.
- **Type Safety:**
  - Written in TypeScript with comprehensive type checking.
- **Error Handling:**
  - User-friendly and detailed error messages for various scenarios.
- **Test Coverage:**
  - Comprehensive test suite using Jest for all major functionalities.
- **Environment Management:**
  - Automatic loading of environment variables from a `.env` file.
- **Input Validation:**
  - Schema-based input validation using Zod.
- **Resource Management:**
  - Read schema information for tables/views, list all resources in a database.
- **Tenant Management:**
  - Create, list, and delete tenants in a database.
- **Server Modes:**
  - STDIO mode (default, for integration with tools like Claude Desktop and Cursor).
  - SSE (Server-Sent Events) mode for real-time event-driven communication over HTTP.
- **Logging:**
  - Structured logging with daily rotation, separate debug logs, and JSON formatted logs.
- **Development Tools:**
  - Includes scripts for building, testing, linting, and cleaning the project.
- **Integration:**
  - Designed for easy integration with Claude Desktop and Cursor.

## Example Usage
- Create a new database in a specific region.
- List all databases.
- Get details or delete a database.
- Manage credentials for a database.
- List available regions for database creation.
- Execute SQL queries and get results as markdown tables.
- Read schema information for tables/views.
- Manage tenants (create, list, delete).

## Installation
- Via npm: `npm install @niledatabase/nile-mcp-server`
- Alpha/preview version: `npm install @niledatabase/nile-mcp-server@alpha`
- Can also be installed manually by cloning the repository and building with npm.

## License
MIT License

## Pricing
No pricing information is provided; the project is open source under the MIT License.
