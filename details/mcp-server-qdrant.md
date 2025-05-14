# mcp-server-qdrant

An official Model Context Protocol (MCP) server implementation for Qdrant, enabling MCP protocol support for Qdrant vector databases. It acts as a semantic memory layer on top of the Qdrant database, facilitating integration between LLM applications and external data sources.

**Source:** [https://github.com/qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant)

## Features

- **Semantic Memory Layer:** Provides a standardized way to store and retrieve information in Qdrant as semantic memories, enabling LLM applications to connect with contextual data.
- **Tools:**
  - `qdrant-store`: Store information and optional metadata into a specified Qdrant collection.
  - `qdrant-find`: Retrieve relevant information from the Qdrant database using semantic queries.
- **Flexible Configuration:**
  - Environment variables for configuration (QDRANT_URL, QDRANT_API_KEY, COLLECTION_NAME, QDRANT_LOCAL_PATH, EMBEDDING_PROVIDER, EMBEDDING_MODEL, etc.).
  - Supports both remote Qdrant servers and local Qdrant database paths.
  - Automatic collection creation if it does not exist.
- **Embedding Models:**
  - Uses FastEmbed models (default: `sentence-transformers/all-MiniLM-L6-v2`) for encoding memories.
- **Transport Protocols:**
  - Supports `stdio` (default, for local clients) and `sse` (Server-Sent Events, recommended for remote clients and team sharing).
- **Containerization:**
  - Includes a Dockerfile for easy containerized deployment.
- **Integration:**
  - Compatible with MCP clients such as Claude Desktop, Cursor, Windsurf, and VS Code.
  - Provides example configurations for integration with these tools.
- **Development & Testing:**
  - Includes a development mode with MCP inspector for local testing and debugging.
- **Customizable Tool Descriptions:**
  - Tool descriptions can be customized for specialized use cases (e.g., semantic code search).
- **Open Source:**
  - Licensed under Apache 2.0.

## Installation

- **Directly with uvx:**
  - Run the server using environment variables (no special install required).
- **Docker:**
  - Build and run with provided Dockerfile.
- **Smithery:**
  - Install via Smithery CLI for Claude Desktop integration.
- **Manual Configuration:**
  - Example JSON configs provided for Claude Desktop and VS Code.

## Use Cases

- Semantic memory for LLM-powered applications.
- Code snippet storage and retrieval for development environments.
- Integration with IDEs (VS Code, Cursor, Windsurf) for enhanced AI-assisted workflows.

## License

- Apache License 2.0

## Pricing

- No pricing information provided; the project is open source under Apache 2.0 license.