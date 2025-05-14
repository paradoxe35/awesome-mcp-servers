# Bilibili MCP

A tool for fetching Bilibili's trending videos and searching Bilibili content, with integration examples for LangChain. Implements MCP (Media Control Protocol) servers and is based on FastMCP and Bilibili's public API.

**Source:** [GitHub - xspadex/bilibili-mcp](https://github.com/xspadex/bilibili-mcp.git)

## Features
- Fetches trending (hot list) videos from Bilibili using public API.
- Implements an MCP server based on FastMCP.
- Can be registered as a tool in Cursor or other MCP clients for real-time access to popular Bilibili video data.
- Provides a `get_popular` tool:
  - Returns up to 10 of the most popular videos (configurable with `top_k`, default 3).
  - Each video entry includes: `title`, `link`, `desc`, `view`, `like`.
- Asynchronous HTTP requests with `httpx`.
- Communication via stdio with MCP clients (e.g., Cursor).
- Example project structure and installation instructions provided.
- Uses Python ≥ 3.12.
- Open-source under the MIT License.

## Technical Details
- Default User-Agent is set to "qwq" (can be modified).
- For educational and research use; avoid excessive querying of the Bilibili API.

## Tags
`mcp`, `media-processing`, `bilibili`, `langchain`, `open-source`

## Category
Media Processing MCP Servers

## Pricing
- Free and open-source (MIT License)