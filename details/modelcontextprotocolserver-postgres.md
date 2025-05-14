# modelcontextprotocol/server-postgres

A PostgreSQL Model Context Protocol (MCP) server providing database integration with schema inspection and query capabilities for MCP workflows.

- **Source:** [GitHub Repository](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)
- **Category:** database-messaging-mcp-servers
- **Tags:** postgresql, database, integration, mcp

## Features

- **Read-only PostgreSQL Access:**
  - Provides read-only access to PostgreSQL databases for secure data inspection.
- **Database Schema Inspection:**
  - Enables retrieval of JSON schema information for each table (column names and data types), automatically discovered from database metadata.
- **Read-only SQL Query Execution:**
  - Allows execution of read-only SQL queries against the connected database, with all queries executed within a READ ONLY transaction.
- **Integration with LLMs:**
  - Designed to enable Large Language Models (LLMs) to inspect database schemas and execute queries as part of MCP workflows.
- **Deployment Options:**
  - Can be run via Docker or with NPX, supporting flexible development and deployment environments.
- **Configuration Examples:**
  - Provides example configurations for integration with Claude Desktop and other MCP clients.
- **Open Source (MIT License):**
  - Licensed under the MIT License, allowing free use, modification, and distribution.

## Pricing

No pricing information is provided. The server is open source and available under the MIT License.
