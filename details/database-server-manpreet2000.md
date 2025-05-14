# database-server-manpreet2000

A Model Context Protocol (MCP) server implementation that allows Large Language Models (LLMs) to interact with databases through natural language queries. Currently supports MongoDB, with planned support for PostgreSQL, CockroachDB, and Redis.

**Source:** [GitHub Repository](https://github.com/manpreet2000/mcp-database-server)

## Features
- Provides an MCP server interface for database operations.
- Enables LLMs to query, insert, delete, and aggregate documents in MongoDB using natural language.
- Supported Tools:
  - `getCollections`: List all collections in the connected database.
  - `getCollection`: Retrieve documents from a collection with optional query parameters.
  - `insertOne`: Insert a single document into a collection.
  - `deleteOne`: Delete a single document from a collection.
  - `aggregate`: Execute an aggregation pipeline.
- Designed to be configurable through the Claude Desktop configuration file.
- Future planned support for PostgreSQL, CockroachDB, and Redis.
- Open source under the MIT License.

## Pricing
- No pricing information provided. The project is open source and licensed under the MIT License.

## Tags
mcp, database, mongodb, natural-language