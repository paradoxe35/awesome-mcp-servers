# Cg MCP

A real-time cryptocurrency data MCP server built on Node.js and Express, interfacing with CoinGecko's API and managing API endpoint switching. It is designed for reliable and extensive crypto data access, suitable for AI integrations, dashboards, portfolio trackers, and trading bots.

[Visit Source](https://creati.ai/mcp/coingeckomcp/)

## Features
- Built with Node.js and Express
- Seamless integration with CoinGecko's free and Pro APIs
- Real-time cryptocurrency market data access
- Supports RESTful endpoints and MCP (Market Communication Protocol) for AI assistant integration
- Automatic fallback between free and Pro APIs to handle rate limiting and API failures
- Comprehensive data endpoints:
  - Price data
  - Coin markets
  - Global stats
  - Trending coins
  - MCP-specific methods
- Request caching for improved performance
- Error handling with detailed responses
- Easy deployment with minimal configuration (via npm/npx, .env setup)
- Data freshness:
  - 1-2 minutes for Pro API
  - 10-30 minutes for free API
- Multi-endpoint support for large-scale applications
- Suitable for AI-powered crypto advisors, dashboards, portfolio tracking, analysis tools, and trading systems
- Optional API key usage (required for Pro API)
- Extensive documentation available

## Pricing
- Supports both free and Pro API modes (CoinGecko's API pricing applies; no additional pricing information provided for this MCP server)

## Category
- Blockchain/Crypto MCP Servers

## Tags
mcp, crypto, market-data, real-time