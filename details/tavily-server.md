# Tavily Server

A TypeScript-based Model Context Protocol (MCP) server implementing a simple notes system, serving as a practical example of custom MCP server implementations.

**Source:** [GitHub Repository](https://github.com/dkmaker/mcp-tavily-server)

## Features

### Resources
- List and access notes via `note://` URIs
- Each note includes a title, content, and metadata
- Notes are accessible as plain text (MIME type)

### Tools
- **create_note**: Create new text notes by providing a title and content
- Notes are persisted in the server's state

### Prompts
- **summarize_notes**: Generates a summary of all stored notes
    - Includes all note contents as embedded resources
    - Returns a structured prompt for LLM summarization

### Development & Debugging
- Easy setup: `npm install`, `npm run build`, or `npm run watch` for development
- Debugging supported via MCP Inspector (`npm run inspector`), accessible through a browser URL

### Integration
- Can be configured for use with Claude Desktop on MacOS and Windows
- Communicates over stdio as per MCP standards

## Pricing

No pricing information provided; the repository appears to be open source.