# apple-notes-mcp

[GitHub Repository](https://github.com/sirmews/apple-notes-mcp)

## Category
- Data Access Integration MCP Servers

## Description
apple-notes-mcp is a Model Context Protocol (MCP) server that enables access to and search functionality over local Apple Notes databases. It integrates with the MCP server ecosystem to allow tools like Claude Desktop to interact with your Apple Notes. The server supports semantic search and AI-assisted Retrieval Augmented Generation (RAG) over your notes, offering secure, local interaction.

## Features
- **Read and Search Apple Notes:** Access your local Apple Notes database and provide note content to compatible clients (e.g., Claude Desktop).
- **Semantic Search:** Supports advanced, semantic search over your notes for improved retrieval.
- **Retrieval Augmented Generation (RAG):** Enables AI-assisted workflows and knowledge extraction from your notes.
- **MCP Server Integration:** Fits into the broader Model Context Protocol server ecosystem, making your notes available to MCP-compatible tools.
- **Prompt Support:** Provides several commands/prompts:
  - `get-all-notes`: Retrieve all notes.
  - `read-note`: Get the full content of a specific note.
  - `search-notes`: Search through notes using various criteria.
- **Local and Secure:** All operations are performed locally, ensuring your notes remain private.
- **Cross-Platform:** Designed for use on macOS and Windows (with appropriate configuration).
- **MIT Licensed:** Open source under the MIT license.

### Limitations / Missing Features
- No support for encrypted notes.
- No filtering for pinned notes.
- No handling of cloud sync status.
- Attachments in notes are not retrieved.
- No support for checklist status in notes.
- Cannot create or edit notes; only reading and searching is supported.

## Pricing
- **Free and Open Source:** Licensed under MIT. No paid plans.

## Tags
mcp, apple-notes, semantic-search, rag
