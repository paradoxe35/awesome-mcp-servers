# blockbeats-mcp

An MCP server that delivers blockchain news and in-depth articles from BlockBeats for AI agents.

## Features
- **Fast News Retrieval**: Fetches the latest blockchain fast news articles from BlockBeats using the `get_latest_news` tool.
- **In-Depth Articles**: Retrieves detailed blockchain articles via the `get_latest_articles` tool.
- **Multi-Language Support**: Supports English (`en`), Simplified Chinese (`cn`), and Traditional Chinese (`cht`).
- **Configurable Parameters** for both tools:
  - `size` (int): Number of articles per page (default: 5)
  - `max_pages` (int): Maximum number of pages to fetch (default: 1)
  - `type` (str): Filter for important news/articles (default: 'push')
  - `lang` (str): Language selection (default: 'en')
- **API Endpoints Used**:
  - News: BlockBeats open-api/open-flash
  - Articles: BlockBeats open-api/open-information
- **Designed for AI Integration**: Intended for use by AI agents to access blockchain news and articles.

## Installation
- Clone the repository: `git clone https://github.com/kukapay/blockbeats-mcp.git`
- Install dependencies: `pip install mcp[cli] httpx`
- Run the server in development: `mcp dev main.py`
- For production with Claude Desktop: `mcp install main.py --name "BlockBeats News"`

## License
MIT License

## Source
[https://github.com/kukapay/blockbeats-mcp](https://github.com/kukapay/blockbeats-mcp)

## Pricing
No pricing information provided; open source under the MIT License.