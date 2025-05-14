# Tavily MCP Server

**Category:** Data Access Integration MCP Servers  
**Tags:** web-search, search, api-integration, mcp  
**Source:** [GitHub - kshern/mcp-tavily](https://github.com/kshern/mcp-tavily.git)

## Description
Tavily MCP Server is an implementation of the Model Context Protocol (MCP) server for the Tavily AI search API. It provides advanced search and content extraction features, allowing integration of Tavily's capabilities within the MCP protocol.

## Features
- **Multiple Search Tools:**
  - `search`: Basic search functionality with customizable options.
  - `searchContext`: Context-aware search for improved relevance.
  - `searchQNA`: Search focused on question and answer retrieval.
- **Content Extraction:**
  - Extract content from URLs, with configurable options such as extraction depth and inclusion of images.
- **Rich Configuration Options:**
  - Control search depth (basic/advanced), topic (general/news/finance), time range, max results, inclusion/exclusion of domains, inclusion of images and their descriptions, inclusion of answers, raw content, and token limits.
- **Error Handling:**
  - Descriptive error messages for all operations.
- **Installation Methods:**
  - Install via Smithery, npm, or npx.
- **Development and Debugging:**
  - Supports debugging and testing via MCP Inspector.
- **Open Source:**
  - Licensed under the MIT License.
- **Requirements:**
  - Node.js 16 or higher, npm or yarn, and a Tavily API key.

## Installation
- **Via Smithery:**
  - `npx -y @smithery/cli install @kshern/mcp-tavily --client claude`
- **Via npm:**
  - `npm install @mcptools/mcp-tavily`
- **Via npx:**
  - `npx @mcptools/mcp-tavily`

## Setup
- Set the Tavily API key via environment variable `TAVILY_API_KEY`.

## Usage
- Add as an MCP server in your configuration, with support for command-line and environment variable setup.

## Pricing
No pricing information is provided; the project is open source and licensed under MIT. Usage of the Tavily API may be subject to Tavily's own pricing policies (not covered here).

## License
MIT License

## Contributing
- Contributions are welcome via pull requests on GitHub.