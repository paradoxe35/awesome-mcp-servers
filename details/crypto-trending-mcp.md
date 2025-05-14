# crypto-trending-mcp

An MCP server that tracks and monitors the latest trending tokens on CoinGecko, providing real-time insights into the most popular cryptocurrencies.

**Source:** [https://github.com/kukapay/crypto-trending-mcp](https://github.com/kukapay/crypto-trending-mcp)

## Features
- **Trending Token Tracking:** Monitors the latest trending cryptocurrencies on CoinGecko.
- **Real-Time Market Data:** Provides up-to-date information, including price, volume, and market cap for trending tokens.
- **Markdown Output Tool:** Implements a `get_trending_md_doc` tool that returns a Markdown table of trending coins, including columns for Rank, Name, Symbol, Price, 1h Change, 24h Change, 7d Change, 24h Volume, and Market Cap.
- **LLM-Ready Parsing Prompt:** Provides a `parse_trending_md_doc` prompt to guide language models in extracting and analyzing structured data from the Markdown table.
- **Seamless Integration:** Designed for use with Claude Desktop, enabling natural language queries for AI-powered crypto analysis.
- **Lightweight & Extensible:** Minimal dependencies and simple architecture, making it easy to deploy or extend.
- **Open Source:** Licensed under the MIT License.
- **Python Based:** Implemented entirely in Python.
- **Playwright Support:** Uses Playwright for browser automation dependencies.

## Installation
- **Requirements:** Python 3.10+, Node.js (for Playwright), uv (dependency manager), Claude Desktop (optional for integration).
- **Install Steps:**
  1. Clone the repository.
  2. Install dependencies with `uv sync` and `playwright install`.

## Usage
- Can be integrated with Claude Desktop for natural language queries about trending cryptocurrencies.
- Returns data as Markdown, which can be parsed into structured formats for further analysis.

## Pricing
- **Open Source:** No cost; licensed under MIT.

## License
- MIT License.