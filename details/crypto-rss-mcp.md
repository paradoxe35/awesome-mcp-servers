# crypto-rss-mcp

[Source Code](https://github.com/kukapay/crypto-rss-mcp)

## Description
crypto-rss-mcp is an MCP server that aggregates real-time cryptocurrency news from multiple RSS feeds, designed to help AI agents and workflows make informed decisions in a fast-paced market.

## Features
- **Feed Retrieval**: Fetches the latest entries from specified RSS feeds and formats them as Markdown with plain-text summaries.
- **Keyword Filtering**: Filters feeds by keywords found in their descriptions or categories.
- **OPML Support**: Allows import of feed lists from a local OPML file (such as those provided by Chainfeeds).
- **LLM Integration**: Provides a prompt for analyzing feed content to summarize key points and identify trends in the cryptocurrency market.
- **Available Tools**:
  - `get_crypto_rss_list`: Lists available RSS feeds from an OPML file, with optional keyword filtering.
  - `get_rss_feed`: Fetches and formats the latest 10 entries from a specified RSS feed.
  - `analyze_rss_feed`: Creates a prompt for analyzing RSS feed content to summarize key points and trends.

## Prerequisites
- Python 3.10
- [uv](https://github.com/astral-sh/uv): Python package and dependency manager

## Installation
- Clone the repository: `git clone https://github.com/kukapay/crypto-rss-mcp.git`
- Install dependencies: `uv sync`

## Usage
- Start the server in development mode: `uv run mcp dev cli.py`
- Install as a Claude Desktop application if desired.

## License
MIT License

## Pricing
No pricing information is provided; the project is open source and licensed under MIT.