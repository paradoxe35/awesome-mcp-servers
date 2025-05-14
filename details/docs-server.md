# docs-server

**Category:** Documentation & Learning Resources  
**Tags:** mcp, documentation, search, integration

## Description
A Model Context Protocol (MCP) server that scrapes, processes, indexes, and searches documentation for third-party libraries and packages. It supports versioning and hybrid search and is directly relevant as an MCP server.

**Source URL:** [https://ubos.tech/mcp/docs-mcp-server-2/](https://ubos.tech/mcp/docs-mcp-server-2/)

---

## Features
- **Documentation Fetching & Scraping:** Fetches content from specified URLs and scrapes documentation for software libraries and packages.
- **Processing & Indexing:** Processes and splits documentation into meaningful chunks using semantic splitting techniques.
- **Vector Embedding:** Generates vector embeddings (default: OpenAI, but supports Google Vertex, Gemini, AWS Bedrock, Microsoft Azure) and stores them in an SQLite database.
- **Hybrid Search:** Combines vector similarity search (using sqlite-vec) and full-text search (using FTS5) for efficient and accurate hybrid search results.
- **Versioning Support:** Stores and queries documentation for different library versions, including unversioned content.
- **MCP Tools Exposure:** Exposes MCP tools for configuration and integration with AI assistants.
- **Customizable Embedding Model:** Environment variables allow configuration of the embedding provider and model.
- **Multiple Deployment Options:**
  - **Docker:** Recommended for ease of use; no need for Node.js.
  - **npx:** For cases needing local file access, requires Node.js.
  - **From Source:** For development and advanced setup.
- **CLI Tools:**
  - Manage documentation (fetch, scrape, search, list, remove, find-version).
  - CLI can be used via Docker or npx, matching the server environment.
- **Debugging Tools:** MCP Inspector package script for debugging when running from source.
- **Automated Release Process:** Uses semantic-release and Conventional Commits for changelog, version bumps, npm publish, and GitHub releases.
- **Architecture Documentation:** Detailed architecture and design principles available in the project documentation.

## CLI Commands
- **fetch-url:** Fetches a single URL and converts its content to Markdown (no crawling or storing).
- **scrape:** Scrapes and indexes documentation from a URL for a specific library.
- **search:** Searches the indexed documentation, filterable by version.
- **find-version:** Finds the best matching version for a library.
- **list:** Lists all indexed libraries.
- **remove:** Removes indexed documentation for a specific library and version.

## Configuration
- **Embedding Model:** Configurable via environment variables (`DOCS_MCP_EMBEDDING_MODEL`).
- **Supported Providers:** OpenAI (default), Google Vertex, Gemini, AWS Bedrock, Microsoft Azure, and OpenAI-compatible APIs.
- **Vector Dimension:** Supports embedding models with vector dimension ≤ 1536 (with exceptions for providers like Gemini).
- **Environment Variables:** Can be set for Docker, npx, or source deployments.

## Deployment Options
- **Docker:** Recommended for most users; environment variables passed via `-e`.
- **npx:** For local file system access (requires Node.js).
- **From Source:** For development, requires cloning the repo, installing dependencies, and configuration.

## Pricing
No pricing information is provided. The project appears to be open-source.

---

**More information:** [docs-server documentation](https://ubos.tech/mcp/docs-mcp-server-2/)