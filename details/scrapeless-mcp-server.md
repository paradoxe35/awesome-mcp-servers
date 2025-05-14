# Scrapeless MCP Server

A Scrapeless Model Context Protocol (MCP) server connector for the Google SERP API, facilitating web search within the MCP ecosystem.

- **Source:** [GitHub - scrapeless-ai/scrapeless-mcp-server](https://github.com/scrapeless-ai/scrapeless-mcp-server)
- **Category:** Data Access Integration / MCP Servers
- **Tags:** web-search, google, data-access, mcp

## Features
- Implements the Model Context Protocol (MCP) to enable seamless integration of LLM (Large Language Model) applications with external data sources.
- Acts as a bridge between LLMs (like ChatGPT, Claude, etc.) and Scrapeless's Google SERP API.
- Allows real-time retrieval of Google Search, Google Flights, Google Maps, Google Jobs, and more into LLM applications.
- Provides a standardized way to connect LLMs with dynamic context for enhancing chat interfaces, AI-driven IDEs, or custom AI workflows.
- Exposes a search tool (`google-search`) with the following parameters:
  - `query` (required): The search query (supports Google advanced operators like `inurl:`, `site:`, `intitle:`, etc).
  - `gl` (optional, default: "us"): Country code for Google search localization.
  - `hl` (optional, default: "en"): Language code for Google search results.
- Can be used as a live MCP endpoint (e.g., via `mcp.so` or `glama.ai`).
- Available as an npm package (`scrapeless-mcp-server`).
- Open source with MIT license.
- Written primarily in TypeScript.

## Installation & Setup
- Requires Node.js 22 or higher and npm/yarn.
- Clone the repository and install dependencies via `npm install`.
- Build the server using `npm run build`.
- Requires a Scrapeless API key (register for a free trial and generate an API key).
- Can be configured as part of a larger MCP server setup using environment variables.

## Pricing
- No explicit pricing details are listed for the server itself; however, a free trial is mentioned for the Scrapeless API key (actual API usage may be subject to Scrapeless service pricing).

## License
- MIT License

---
For more information and usage examples, visit the [GitHub repository](https://github.com/scrapeless-ai/scrapeless-mcp-server).