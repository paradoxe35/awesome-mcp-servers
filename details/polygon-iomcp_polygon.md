# polygon-io/mcp_polygon

**Description:**

An experimental Model Context Protocol (MCP) server that provides access to Polygon.io's financial market data APIs for stocks, indices, forex, options, and more. It is designed to be LLM-friendly, exposing all Polygon.io API endpoints as tools for programmatic access.

**Source:** [https://github.com/polygon-io/mcp_polygon](https://github.com/polygon-io/mcp_polygon)

**Category:** Finance Market Data MCP Servers

**Tags:** polygon-io, market-data, finance, api-integration

---

## Features

- Exposes all Polygon.io API endpoints as MCP tools accessible via LLMs or programmatically
- Access to comprehensive financial market data, including:
  - Stock, options, forex, and crypto aggregates (OHLC) and bars
  - Real-time and historical trades and quotes
  - Market snapshots for tickers
  - Ticker details and reference data
  - Dividends and splits data
  - Financial fundamentals for companies
  - Market status and trading holidays
  - News articles for tickers
- Implements endpoints as tools (examples):
  - `get_aggs`: Stock aggregates (OHLC) for a ticker
  - `list_trades`: Historical trade data
  - `get_last_trade`: Latest trade for a symbol
  - `list_ticker_news`: Recent news for tickers
  - `get_snapshot_ticker`: Current market snapshot for a ticker
  - `get_market_status`: Current market status and trading hours
  - `list_stock_financials`: Company fundamentals
- LLM-friendly: Converts responses to standard JSON for easy processing
- Can be integrated both with Claude Code (CLI) and Claude Desktop
- Dockerfile and docker-compose included for easy deployment
- Debugging support via MCP Inspector browser interface
- Open source (MIT License)

## Installation & Requirements

- Python 3.8+
- Polygon.io API key
- Astral UV (Python environment manager)
- Supports installation for both CLI and desktop environments

## Development

- Codebase primarily in Python
- Supports local development and debugging
- Contributions welcome via GitHub issues and PRs (preferably discussed beforehand)

## Pricing

No pricing information is provided for the MCP server itself. A valid Polygon.io API key (which may be subject to Polygon.io's own pricing) is required to access data.

---

**Note:** This project is experimental and may be subject to breaking changes.