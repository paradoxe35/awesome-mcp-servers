# Ihor-Sokoliuk/mcp-searxng

A Model Context Protocol (MCP) server for interfacing with SearXNG search engine instances, providing MCP-compliant search capabilities.

- **Source:** [GitHub Repository](https://github.com/ihor-sokoliuk/mcp-searxng)
- **Category:** Web Search MCP Servers
- **Tags:** mcp, search, searxng, privacy
- **License:** MIT

## Features

- **Web Search:** Execute general web queries, including news and articles, using the SearXNG API.
- **Pagination:** Supports controlling the number of results per page and pagination offset.
- **Configurable Instance:** Can connect to any public or local SearXNG instance by setting the `SEARXNG_URL` environment variable.
- **MCP-Compliant:** Provides an MCP-compliant server interface for search.
- **Tool Integration:**
  - `searxng_web_search` tool for executing searches with parameters:
    - `query` (string): Search terms
    - `count` (number, optional): Results per page (default: 20)
    - `offset` (number, optional): Pagination offset (default: 0)
- **Deployment Options:**
  - Installable via `Smithery` for integration with Claude Desktop.
  - Docker support for containerized deployment.
- **Open Source:** Licensed under MIT, allowing free use, modification, and distribution.

## Pricing

- **Open Source:** Free to use under the MIT License. No paid plans or pricing tiers.

## Usage Notes

- Requires access to a running SearXNG instance (public or local).
- Easily configurable for different environments via environment variables.
