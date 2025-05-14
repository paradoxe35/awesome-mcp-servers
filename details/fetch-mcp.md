# fetch-mcp

[Source Code](https://github.com/zcaceres/fetch-mcp)

## Description
fetch-mcp is a flexible HTTP fetching Model Context Protocol (MCP) server that fetches and transforms web content into various formats, enabling structured access to web data.

## Features
- Fetches web content using the modern Fetch API.
- Supports custom headers for HTTP requests.
- Provides content in multiple formats:
  - **HTML**: Fetches and returns the raw HTML content of a webpage.
  - **JSON**: Fetches and parses JSON content from a URL.
  - **Plain Text**: Fetches and returns the text content of a webpage with HTML tags, scripts, and styles removed.
  - **Markdown**: Fetches a webpage and converts its content to Markdown format.
- Uses **JSDOM** for HTML parsing and text extraction.
- Uses **TurndownService** for HTML to Markdown conversion.
- Can be integrated with desktop applications as an MCP server.
- No persistent resources; fetches and transforms content on-demand.
- Built with TypeScript and JavaScript.

## Usage
- Clone the repository.
- Install dependencies with `npm install`.
- Build the server using `npm run build`.
- Start the server with `npm start` (runs on stdio).
- For development, `npm run dev` starts the TypeScript compiler in watch mode.
- Run tests with `npm test`.

## License
MIT License.

## Pricing
No pricing information provided; fetch-mcp is an open-source project.