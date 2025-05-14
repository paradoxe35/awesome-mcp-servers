# mcp-server-odbc

**Category:** Database Messaging MCP Servers  
**Tags:** mcp, database, odbc, integration  
**Source:** [GitHub Repository](https://github.com/OpenLinkSoftware/mcp-odbc-server)

## Description
mcp-server-odbc is a TypeScript-based Model Context Protocol (MCP) server that provides generic Database Management System (DBMS) connectivity through the ODBC protocol. It enables integration of Large Language Models (LLMs) and client applications with ODBC-accessible data sources, supporting a wide range of use cases for database integration.

## Features
- **ODBC Connectivity**: Abstracts access to any ODBC-compatible database via a configured Data Source Name (DSN).
- **TypeScript Implementation**: Built as a lightweight layer on top of node-odbc, leveraging Node.js for cross-platform compatibility.
- **Command-Line Tools**: Provides tools for schema discovery, table listing, table description, and SQL/SPARQL query execution.
- **Supported Operations:**
  - `get_schemas`: List all database schemas.
  - `get_tables`: List tables within a schema.
  - `describe_table`: Get column metadata (names, types, nullability, keys).
  - `filter_table_names`: List tables by substring/pattern match.
  - `query_database`: Execute SQL queries and return results in JSON.
  - `execute_query`, `query_database_jsonl`: Execute SQL queries and return results in JSON Lines (JSONL) format.
  - `execute_query_md`, `query_database_md`: Execute SQL queries and return results as Markdown tables.
  - `spasql_query`: Execute Virtuoso-specific SPASQL (SQL/SPARQL hybrid) queries.
  - `sparql_query`: Execute Virtuoso-specific SPARQL queries.
  - `virtuoso_support_ai`: Interact with Virtuoso Support Assistant/Agent for LLM-based assistance.
- **Environment Configuration**: Uses `.env` file for secure configuration of ODBC DSN, user, password, ODBC INI path, and optional AI API key.
- **MCP Inspector Tool Compatibility**: Includes tools and detailed instructions for testing and troubleshooting the server via the MCP Inspector Tool.
- **Apple Silicon (ARM64) Compatibility**: Provides detailed steps for resolving architecture compatibility issues on Apple Silicon devices.
- **Integration with LLM Clients**: Provides example configuration and usage guides for integrating with Claude Desktop, Cline (VSCode Extension), and Cursor editor.
- **Open Source**: Licensed under MIT, open to contributions and usage demos for more DBMS connectors.

## Installation & Setup
- Requires Node.js v21.1.0 or higher and unixODBC runtime.
- Install dependencies with npm.
- Clone the repository and set up environment variables as per your ODBC environment.
- Detailed setup steps for Apple Silicon and platform-specific issues are provided.

## Usage Examples
- Command-line usage or integration with LLM-powered applications to run SQL/SPARQL queries, get schema information, and interact with Virtuoso-specific AI features.
- Sample configuration provided for Claude Desktop, Cline (VSCode), and Cursor editor.

## License
MIT License

## Pricing
No pricing information is provided; the project is open source under the MIT License.