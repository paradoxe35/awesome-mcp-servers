# alpha-vantage-mcp

**MCP server integrating Alpha Vantage API, delivering real-time stock and crypto data for AI agents via Model Context Protocol.**

- **Source:** [GitHub Repository](https://github.com/berlinbra/alpha-vantage-mcp)
- **Category:** finance-market-data-mcp-servers
- **Tags:** market-data, finance, real-time, api-integration

## Features
- Provides a Model Context Protocol (MCP) server for real-time access to financial market data via the Alpha Vantage API
- Standardized interface for AI agents to retrieve:
  - Real-time stock quotes (price, volume, change, high, low)
  - Detailed company information (sector, industry, market cap, exchange, currency, description)
  - Real-time cryptocurrency exchange rates (with bid/ask prices and last updated timestamp)
  - Historical daily price data for stocks (OHLCV)
  - Historical options chain data (with advanced filtering, sorting, and Greeks)
- Five main tools implemented:
  - `get-stock-quote`: Latest stock quote for a specific company
  - `get-company-info`: Stock/company details for a symbol
  - `get-crypto-exchange-rate`: Real-time crypto exchange rates
  - `get-time-series`: Historical daily price data for a stock
  - `get-historical-options`: Historical options chain data with sorting/filtering
- Built-in error handling for:
  - Rate limit exceeded
  - Invalid API key
  - Network issues and timeouts
  - Malformed responses
- Returns clear, human-readable error messages
- Supports installation via Docker or Smithery CLI for integration with Claude Desktop and other MCP-compatible clients
- Configurable via environment variables (API key)
- Licensed under the MIT License

## Prerequisites
- Python 3.12+
- `httpx` library
- `mcp` library

## Installation
- Clone the repository and build/run with Docker, or install via Smithery CLI for Claude Desktop

## Pricing
- **Free and open source** (MIT License)

## License
- MIT License

## Contributors
- berlinbra
- zzulanas