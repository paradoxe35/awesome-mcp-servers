# GeekNews MCP Server

A Model Context Protocol (MCP) server for retrieving and processing news data from GeekNews, designed for integration in the MCP server ecosystem. Implemented in Python and uses BeautifulSoup for web scraping.

## Features
- **Article Retrieval**: Fetch articles from GeekNews with the `get_articles` tool.
  - Supports specifying article type (top, new, ask, show) and the number of articles to retrieve.
  - Each article includes title, URL, points, author, time, comment count, and rank.
  - Uses cached data to reduce server load.
- **Weekly News Retrieval**: Fetch weekly news from GeekNews with the `get_weekly_news` tool.
  - Specify a particular weekly news ID or get the latest weekly news.
  - Provides details such as title, number, ID, content, URL, and item list.
  - Each item includes title, URL, and rank.
  - Uses cached data for efficiency.
- **Caching Mechanism**:
  - Automatically parses and caches data once per day.
  - Valid cached data is used instead of making redundant requests to GeekNews.
  - Cache is valid for 24 hours and auto-renews as needed.
  - A scheduler checks cache validity and refreshes it as required.
- **Implementation Details**:
  - Python codebase with modular structure: models, parser, client, config, cache, scheduler, server, and entry point (`main.py`).
  - Cache data stored in the user's home directory under `.cache/geeknews-mcp`.
  - Can be installed and run locally or via Smithery MCP server ecosystem.

## Installation & Usage
- **Via Smithery**: Add the server to your MCP configuration and run using Smithery CLI with your issued key.
- **Local Installation**: Clone the repo, set up the environment with `uv`, activate the virtual environment, and run the server for local testing.

## Notes
- The server depends on the HTML structure of GeekNews. If the website changes, parsing logic may require updates.

## License
MIT License

## Source
[https://github.com/the0807/GeekNews-MCP-Server](https://github.com/the0807/GeekNews-MCP-Server)

## Pricing
- Open source, free to use under the MIT License.
