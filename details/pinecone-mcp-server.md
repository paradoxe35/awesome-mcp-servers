# Pinecone MCP Server

**Category:** database-messaging-mcp-servers  
**Tags:** pinecone, vector-database, semantic-search, privacy

## Description
Pinecone MCP Server is an implementation of the Model Context Protocol (MCP) server that enables reading and writing operations to a Pinecone vector database index. It is designed to be used with clients like Claude Desktop and supports multi-tenant vector search and privacy-safe personalization within the MCP ecosystem. The server provides basic Retrieval-Augmented Generation (RAG) capabilities over Pinecone.

Source code: [https://github.com/sirmews/mcp-pinecone](https://github.com/sirmews/mcp-pinecone)

## Features
- **Read and Write to Pinecone Index:** Supports both reading from and writing to a Pinecone vector database.
- **Semantic Search:** Allows searching for records in the Pinecone index using semantic queries.
- **Document Operations:**
  - **Read Document:** Retrieve a specific document from the Pinecone index.
  - **List Documents:** List all documents stored in the Pinecone index.
  - **Process Document:** Chunk a document, generate embeddings, and upsert the chunks into the Pinecone index. Chunking is token-based, and embeddings are generated via Pinecone's inference API.
- **Index Statistics:** Retrieve stats about the Pinecone index, such as number of records, dimensions, and namespaces.
- **Multi-Tenancy Support:** Designed to work in environments where multiple tenants need isolated vector search and personalization.
- **Privacy-Safe Personalization:** Built with privacy considerations for user data and operations.
- **Rudimentary RAG:** Provides basic Retrieval-Augmented Generation functionality by integrating with Pinecone.
- **Integration with Claude Desktop:** Can be installed and configured for use with Claude Desktop on MacOS and Windows.
- **Configuration Options:** Supports both development (unpublished) and published server configurations.
- **Docker Support:** Includes a Dockerfile for containerized deployments.
- **MIT Licensed:** Open source under the MIT license.

## Installation
- Can be installed via Smithery CLI or using Python package managers (`uvx`, `uv pip`).
- Requires a Pinecone account and API key for operation.

## Pricing
No pricing information is provided. The software is open source under the MIT license; however, use of Pinecone as a backend may incur costs as per Pinecone's pricing.

## License
MIT License.
