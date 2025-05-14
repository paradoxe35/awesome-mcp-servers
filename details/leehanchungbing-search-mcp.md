# leehanchung/bing-search-mcp

**Source:** [leehanchung/bing-search-mcp on GitHub](https://github.com/leehanchung/bing-search-mcp)

**Category:** Web Search MCP Servers

**Tags:** mcp, web-search, bing, search

---

## Description
A Model Context Protocol (MCP) server that integrates with the Microsoft Bing Search API, enabling AI assistants and MCP-compatible clients to perform web, news, and image searches via Bing.

---

## Features
- **Web Search:** Perform general information searches across the web using Bing.
- **News Search:** Retrieve recent news articles and current events.
- **Image Search:** Search for visual content such as images.
- **Rate Limiting:** Prevents abuse of the Bing Search API by limiting requests.
- **Comprehensive Error Handling:** Handles various error conditions gracefully.
- **MCP Protocol Support:** Designed to work with MCP-compatible clients (e.g., Claude Desktop, Cursor).
- **Configurable:** Set environment variables for API key and endpoint.
- **Available Search Tools:**
  - `bing_web_search(query, count=10, offset=0, market="en-US")`
  - `bing_news_search(query, count=10, market="en-US", freshness="Day")`
  - `bing_image_search(query, count=10, market="en-US")`
- **Python-based:** Requires Python 3.10 or higher.
- **Docker Support:** Includes a Dockerfile for containerized deployment.

---

## Requirements
- Python 3.10+
- Microsoft Bing Search API key
- MCP-compatible client

---

## Installation & Configuration
- Clone the repository
- Install dependencies using `uv pip install -e .`
- Set environment variables for your Bing API key
- Run the server with `uvx bing-search-mcp`

---

## License
MIT License

---

## Pricing
No pricing information is provided; the project is open-source under the MIT license. Use of the Microsoft Bing Search API may incur costs as determined by Microsoft Azure.