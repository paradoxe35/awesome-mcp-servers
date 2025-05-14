# vercel-ai-docs-mcp

A Model Context Protocol (MCP) server that provides AI-powered search and querying capabilities for the Vercel AI SDK documentation. It enables developers to ask questions about the Vercel AI SDK and receive accurate, contextualized responses based on the official documentation.

**Source:** [GitHub Repository](https://github.com/IvanAmador/vercel-ai-docs-mcp)

## Features
- **Direct Documentation Search:** Query the Vercel AI SDK documentation index directly using similarity search.
- **AI-Powered Agent:** Ask natural language questions about the Vercel AI SDK and receive comprehensive answers.
- **Session Management:** Maintains conversation context across multiple queries.
- **Automated Indexing:** Tools to fetch, process, and index the latest Vercel AI SDK documentation.
- **MCP Server:** Exposes tools via the Model Context Protocol for integration with AI assistants.
- **DocumentFetcher:** Crawls and processes the Vercel AI SDK documentation.
- **VectorStoreManager:** Creates and manages a FAISS vector index for semantic search.
- **AgentService:** Provides AI-powered answers to questions using the Google Gemini model.
- **DirectQueryService:** Offers direct semantic search of the documentation.
- **Clear Memory Tool:** Clears session memory for specific or all sessions.
- **Integration Support:** Compatible with Claude Desktop, Cursor, and any client supporting MCP.
- **Build Scripts:** Scripts for building TypeScript files and indexing documentation.

## Usage
- The MCP server exposes three primary tools:
  - `agent-query`: Query documentation using an AI agent.
  - `direct-query`: Perform direct similarity search against documentation.
  - `clear-memory`: Clear conversation memory for sessions.
- Supports integration with AI assistants like Claude Desktop and Cursor via MCP configuration.

## Requirements
- Node.js 18+
- npm
- Google API key for Gemini model access

## License
MIT

## Pricing
No pricing information is provided; the project is open source under the MIT license.