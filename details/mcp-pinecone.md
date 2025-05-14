# mcp-pinecone

A Model Context Protocol (MCP) server for interacting with Pinecone, enabling vector search and document management capabilities over Pinecone indexes.

- **Source Code:** [GitHub - sirmews/mcp-pinecone](https://github.com/sirmews/mcp-pinecone)
- **Category:** database-messaging-mcp-servers
- **Tags:** mcp, pinecone, vector-database, semantic-search, ai-integration

---

## Features

- **Read and Write to Pinecone Index:** Provides an MCP server interface to interact with Pinecone indexes for both reading and writing data.
- **Rudimentary RAG (Retrieval-Augmented Generation):** Supports basic RAG workflows.
- **Semantic Search:** Allows searching for records in a Pinecone index using semantic embeddings.
- **Read Document:** Fetches a document from a Pinecone index.
- **List Documents:** Lists all documents available in the Pinecone index.
- **Pinecone Stats:** Retrieves index statistics, such as the number of records, dimensions, and namespaces.
- **Process Document:** Processes a document into token-based chunks, generates embeddings, and upserts them into the Pinecone index. Embeddings are generated via Pinecone's inference API.
- **Request Handlers:** Implements MCP handlers such as `list_resources`, `read_resource`, `list_tools`, `call_tool`, `get_prompt`, and `list_prompts`.
- **Development Tools:** Includes a Dockerfile, Makefile, and supports installation via PyPI or Smithery CLI.
- **Debugging Support:** Compatible with MCP Inspector for debugging MCP servers.

## Installation

- **PyPI:** `uv pip install mcp-pinecone`
- **Smithery CLI:** `npx -y @smithery/cli install mcp-pinecone --client claude`
- **Docker:** Dockerfile included in the repository for containerized setup.

## Configuration

- Requires a Pinecone account, API key, and index name for operation.
- Supports configuration for both development (unpublished) and published server setups.

## License

MIT License

## Pricing

No pricing information is provided. The project is open source under MIT License.
