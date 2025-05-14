# mcp-server-milvus

**Category:** Database Messaging MCP Servers  
**Source:** [GitHub Repository](https://github.com/zilliztech/mcp-server-milvus)

MCP server for Milvus/Zilliz vector databases, enabling direct interaction with your database through the Model Context Protocol (MCP). Provides a standardized way to connect LLM (Large Language Model) applications with Milvus vector database features.

## Features

### General
- Implements the Model Context Protocol (MCP) to enable integration between LLM applications and Milvus vector databases.
- Can be used with various LLM-enabled applications such as Claude Desktop, Cursor, and any custom MCP client.
- Runs with Python 3.10+ and requires a running Milvus instance.
- Can be run directly via `uv` without separate installation.
- Supports configuration via environment variables (`MILVUS_URI`, `MILVUS_TOKEN`, `MILVUS_DB`).

### Available Tools

#### Search and Query Operations
- **milvus-text-search**: Full-text document search in collections.
- **milvus-vector-search**: Vector similarity search using different distance metrics (COSINE, L2, IP).
- **milvus-hybrid-search**: Combines vector similarity and attribute-based filtering.
- **milvus-multi-vector-search**: Similarity search with multiple query vectors.
- **milvus-query**: Query collections using filter expressions.
- **milvus-count**: Count entities in a collection, with optional filtering.

#### Collection Management
- **milvus-list-collections**: Lists all collections in the database.
- **milvus-collection-info**: Retrieves detailed information about a collection.
- **milvus-get-collection-stats**: Provides statistics about a collection.
- **milvus-create-collection**: Creates a new collection with a specified schema and optional index parameters.
- **milvus-load-collection**: Loads collections into memory.
- **milvus-release-collection**: Releases collections from memory.
- **milvus-get-query-segment-info**: Retrieves information about query segments.
- **milvus-get-collection-loading-progress**: Shows loading progress of a collection.

#### Data Operations
- **milvus-insert-data**: Inserts data into a collection.
- **milvus-bulk-insert**: Batch data insertion for better performance.
- **milvus-upsert-data**: Upserts (insert or update) data in a collection.
- **milvus-delete-entities**: Deletes entities from a collection using a filter expression.
- **milvus-create-dynamic-field**: Adds a dynamic field to an existing collection.

#### Index Management
- **milvus-create-index**: Creates indexes on vector fields.
- **milvus-get-index-info**: Retrieves index information for a collection.

### Integration Examples
- **Claude Desktop**: Integrate by updating the configuration file and running the server with the appropriate Milvus URI.
- **Cursor**: Add the MCP server via the settings UI or project-specific configuration for Composer's Agent feature.

### Development & Deployment
- Can be run locally or remotely.
- Provides troubleshooting steps for connection and authentication issues.

## Pricing
No pricing information is provided; the project is open source and available on GitHub.

## Tags
`mcp`, `milvus`, `vector-database`, `database`, `ai-integration`