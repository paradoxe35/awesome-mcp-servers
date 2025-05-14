# ac3xx/mcp-servers-kagi

A Model Context Protocol (MCP) server implementation that integrates the Kagi Search API, enabling Kagi-powered search capabilities within the MCP ecosystem. Built in TypeScript, the server provides tools for performing web searches via Kagi, and is designed to work with clients like Claude Desktop.

## Features

### Implemented Tools
- **kagi_search**: Perform web searches using Kagi's API.
  - Accepts a query string and optional limit parameter.
  - Returns search results from Kagi.

### Planned Tools (Not Yet Implemented)
- **kagi_summarize**: Generate summaries of web pages or text.
- **kagi_fastgpt**: Get quick responses using Kagi's FastGPT.
- **kagi_enrich**: Fetch enriched news results on specific topics.

### Development & Usage
- TypeScript-based implementation.
- Can be installed and run via npm and Smithery CLI for integration with Claude Desktop.
- Requires a Kagi API key set in a `.env` file.
- Supports development workflows with auto-rebuild and an inspector tool for debugging.
- Can be configured for use with Claude Desktop via JSON config.

### License
- MIT License.

## Pricing
No pricing information is provided; the project is open-source and available under the MIT license.

## Source
[GitHub Repository](https://github.com/ac3xx/mcp-servers-kagi)

## Tags
search, api-integration, kagi, open-source