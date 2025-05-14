# duckduckgo-mcp-server

A Model Context Protocol (MCP) server that provides web search capabilities through DuckDuckGo, with additional features for content fetching and parsing. Implemented in both TypeScript and Python.

**Source:** [https://github.com/nickclyde/duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server)

## Features
- **Web Search:** Enables DuckDuckGo web search with advanced rate limiting and result formatting.
- **Content Fetching:** Retrieves and parses webpage content with intelligent text extraction.
- **Rate Limiting:**
  - Search: 30 requests per minute
  - Content fetching: 20 requests per minute
  - Automatic queue management and wait times
- **Error Handling:** Comprehensive error catching and logging, with graceful degradation on rate limits or timeouts.
- **LLM-Friendly Output:** Results formatted for optimal consumption by large language models (LLMs).
- **Result Processing:**
  - Removes ads and irrelevant content
  - Cleans up DuckDuckGo redirect URLs
  - Truncates long content where needed
- **Tools:**
  - `search(query: str, max_results: int = 10)`: Performs a DuckDuckGo search and returns formatted results (titles, URLs, snippets).
  - `fetch_content(url: str)`: Fetches and cleans text content from a webpage.
- **Installation options:**
  - Via Smithery (`npx -y @smithery/cli install @nickclyde/duckduckgo-mcp-server --client claude`)
  - Via PyPI using `uv pip install duckduckgo-mcp-server`

## Pricing
- Open source, licensed under the MIT License. No cost to use.

## Category
- data-access-integration-mcp-servers

## Tags
- mcp
- duckduckgo
- web-search
- privacy