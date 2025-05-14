# chroma-mcp

**Source:** [https://github.com/chroma-core/chroma-mcp](https://github.com/chroma-core/chroma-mcp)

## Description
chroma-mcp is a Model Context Protocol (MCP) server implementation that provides database capabilities for Chroma, an open-source embedding database. It enables integration between LLM applications and external data sources, allowing AI models to create collections over generated data and user inputs, and retrieve that data using vector search, full text search, and metadata filtering.

## Features
- **Flexible Client Types:**
  - Ephemeral (in-memory) client for testing and development
  - Persistent file-based storage client
  - HTTP client for self-hosted Chroma instances
  - Cloud client for Chroma Cloud integration (connects to api.trychroma.com)

- **Collection Management:**
  - Create, modify, and delete collections
  - List all collections with pagination
  - Retrieve collection information and statistics
  - Configure HNSW parameters for optimized vector search

- **Document Operations:**
  - Add documents with optional metadata and custom IDs
  - Query documents using semantic search
  - Advanced filtering using metadata and document content
  - Retrieve documents by IDs or filters
  - Full text search capabilities

- **Supported Tools (API Endpoints):**
  - create_collection
  - peek_collection
  - list_collections
  - get_collection_info
  - get_collection_count
  - modify_collection
  - delete_collection
  - add_documents
  - query_documents
  - get_documents

- **Configuration Options:**
  - Supports configuration via command-line arguments or environment variables
  - Integration with Claude Desktop supported

## Pricing
No pricing information is provided. chroma-mcp is an open-source project.

## Tags
mcp, vector-database, semantic-search, data-access, chroma

## Category
data-access-integration-mcp-servers