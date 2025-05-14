## duckduckgo-server

A TypeScript-based Model Context Protocol (MCP) server providing programmatic DuckDuckGo search functionality, built using the duck-duck-scrape library. It serves as a concrete MCP server project for integrating DuckDuckGo search into applications.

**Source:** [GitHub - zhsama/duckduckgo-mcp-server](https://github.com/zhsama/duckduckgo-mcp-server)

### Features
- **DuckDuckGo Search Integration:**
  - Provides a search tool (`duckduckgo_search`) to perform web searches via the DuckDuckGo API.
  - Required parameter: `query` (max 400 characters).
  - Optional parameters:
    - `count` (number of results, 1-20, default 10)
    - `safeSearch` (strict/moderate/off, default moderate)
  - Returns formatted Markdown search results.
- **Rate Limiting:**
  - Maximum 1 request per second.
  - Maximum 15,000 requests per month.
- **Error Handling:**
  - Includes support for error handling.
- **Development Support:**
  - Built with TypeScript.
  - Easy setup for Node.js (>=18) and pnpm (>=8.0.0).
  - Scripts for building, running, and watching for changes.
  - Debugging support via MCP Inspector (access debugging tools in browser).
- **Integration:**
  - Example configuration provided for use with Claude Desktop on MacOS and Windows.

### Installation & Usage
- Install dependencies with pnpm.
- Build and run the server using provided scripts.
- Debug using the MCP Inspector.

### License
- MIT License

### Pricing
- No pricing information provided; the project is open source under the MIT license.