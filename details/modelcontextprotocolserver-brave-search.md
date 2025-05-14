# modelcontextprotocol/server-brave-search

MCP server for web search using Brave's Search API, part of the official Model Context Protocol servers.

- **Source:** [GitHub Repository](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search)

## Features
- **Web Search**: Supports general queries, news, and articles with pagination and options to control content freshness.
- **Local Search**: Find businesses, restaurants, and services with detailed information.
- **Flexible Filtering**: Allows control over result types, safety levels, and content freshness for both web and local searches.
- **Smart Fallbacks**: Local search will automatically fall back to web search if no local results are found.
- **brave_web_search Tool**:
  - Execute web searches with pagination and filtering.
  - Inputs:
    - `query` (string): Search terms
    - `count` (number, optional): Results per page (max 20)
    - `offset` (number, optional): Pagination offset (max 9)
- **brave_local_search Tool**:
  - Search for local businesses and services.
  - Inputs:
    - `query` (string): Local search terms
    - `count` (number, optional): Number of results (max 20)
  - Automatically falls back to web search if no local results found.
- **Deployment Options**: Can be run via Docker or NPX, and can be configured for usage with platforms like Claude Desktop.
- **Open Source**: Licensed under the MIT License.

## Pricing
- **Free Tier**: Available with 2,000 queries/month (requires Brave Search API account).
- Other plans available via Brave Search API (details on their developer dashboard).

## Tags
`mcp` `web-search` `brave` `integration`