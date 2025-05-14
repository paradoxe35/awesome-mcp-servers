# Search1API MCP

- **Category:** Data Access Integration MCP Servers
- **Tags:** web-search, api-integration, data-access, mcp
- **Source:** [GitHub Repository](https://github.com/fatwang2/search1api-mcp)

## Description
Search1API MCP is a Model Context Protocol (MCP) server that integrates web and news search, crawling, and reasoning capabilities via the Search1API (requires a paid API key). It is designed for integration with the MCP server ecosystem and supports anti-bot crawling and enrichment of search indices.

## Features
- **Web Search Functionality:** Perform web searches using Search1API with configurable search services and result limits.
- **News Search Functionality:** Search for news articles using Search1API, also with configurable services and result limits.
- **Web Page Content Extraction:** Extract the content of a web page via URL crawling.
- **Website Sitemap Extraction:** Retrieve all related links from a given URL (sitemap extraction).
- **Reasoning Tool:** Deep thinking and complex problem solving using the DeepSeek R1 model (or other models supported by Search1API), with web search integration.
- **Integration:** Seamlessly integrates with Claude Desktop, Cursor, and Windsurf MCP server environments.
- **Anti-bot Crawling:** Supports crawling with anti-bot measures.
- **Tool-based API:** Offers distinct tools for search, news, crawl, sitemap, and reasoning, each with their own parameters.
- **Open Source:** Licensed under the MIT License.

## Setup & Integration
- Requires a Search1API key (register at Search1API for key and free credits).
- Can be configured for Claude Desktop, Cursor, and Windsurf via provided configuration files and environment variables.

## Pricing
- Requires a paid Search1API key (Search1API provides 100 free credits upon registration). Further usage requires payment as per Search1API's pricing.

## Version History
- **v0.1.4:** Added reasoning tool with DeepSeek R1 and updated configuration guides.
- **v0.1.3:** Added news search functionality.
- **v0.1.2:** Added sitemap functionality.
- **v0.1.1:** Added web crawling functionality.
- **v0.1.0:** Initial release with search functionality.