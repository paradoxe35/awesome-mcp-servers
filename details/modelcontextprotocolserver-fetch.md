# modelcontextprotocol/server-fetch

Efficient web content fetching and processing MCP server, designed for AI consumption and integration with the MCP framework.

[Source on GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch)

## Features

- **Web Content Fetching**: Fetches content from any provided URL.
- **HTML to Markdown Conversion**: Converts fetched HTML content to markdown for easier processing by LLMs and AI systems.
- **Response Truncation and Pagination**: Supports truncating responses and specifying a `start_index` to read webpages in chunks, allowing for incremental retrieval until all desired information is obtained.
- **Flexible Output**: Option to return raw HTML content instead of markdown.
- **Configurable via Arguments**:
  - `url` (required): The URL to fetch.
  - `max_length` (optional): Maximum number of characters to return (default: 5000).
  - `start_index` (optional): Character index to start content extraction (default: 0).
  - `raw` (optional): Whether to return raw HTML (default: false).
- **Multiple Installation Options**:
  - Via `uvx` (no installation needed, direct run).
  - Via `pip` (`pip install mcp-server-fetch`).
  - Via Docker.
- **Integration Ready**: Easily configurable for use with Claude.app, VS Code, and other MCP-compatible applications.
- **robots.txt Compliance**: Obeys robots.txt by default for model tool requests; can be disabled via configuration.
- **User-Agent Customization**: Allows specifying a custom user-agent string.
- **Proxy Support**: Can be configured to use a proxy with the `--proxy-url` argument.
- **Debugging Tools**: Compatible with the MCP inspector for debugging and development.
- **Open Source and Extensible**: Licensed under MIT, open for contributions, and extensible with new tools and enhancements.

## Pricing

No pricing information provided. The server is open source and available under the MIT License.

## Tags

`mcp`, `web`, `fetch`, `ai-integration`
