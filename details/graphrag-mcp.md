# graphrag-mcp

**Repository:** [https://github.com/rileylemm/graphrag_mcp](https://github.com/rileylemm/graphrag_mcp)

**Category:** data-access-integration-mcp-servers

**Tags:** mcp, semantic-search, vector-database, neo4j, qdrant

---

## Description

graphrag-mcp is a Model Context Protocol (MCP) server designed to interact with a hybrid graph and vector database system, combining Neo4j (graph database) and Qdrant (vector database). It enables structured and semantic document search, making it suitable for applications needing both graph-based and semantic retrieval.

---

## Features

- **Hybrid Retrieval System:** Combines Neo4j for structured graph queries and Qdrant for semantic vector-based search.
- **MCP Server:** Implements the Model Context Protocol specification, allowing compatibility with any MCP-enabled client.
- **LLM Integration:** Seamlessly integrates with large language models by providing a hybrid retrieval backend.
- **Search Tools:**
  - `search_documentation`: Performs semantic search for information.
  - `hybrid_search`: Executes both semantic and graph-based search approaches.
- **Easy Setup:**
  - Configuration via `.env` file for database connections.
  - Quick start scripts and detailed setup instructions provided.
- **Extensible:** Can be added as a resource to MCP clients such as Cursor and Claude Desktop.
- **Document Indexing:** Supports indexing documents into both Neo4j and Qdrant databases.
- **Open Source:** Licensed under the MIT License.

---

## Pricing

No pricing information provided. The project is open source under the MIT License.

---

## License

MIT License.

---

## Attribution

If you use or adapt this MCP server, attribution to Riley Lemm and a link back to the repository is requested.