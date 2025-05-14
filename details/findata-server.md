# Findata Server

[GitHub Repository](https://github.com/xBlueCode/findata-mcp-server)

## Description
Findata Server is an MCP server that integrates with the Alpha Vantage API to provide stock market data. It is designed for use with LLM and MCP workflows, enabling access to both current and historical stock information.

## Features
- Integrates with the Alpha Vantage API to access financial market data
- Provides endpoints for:
  - **getStockQuote**: Retrieve the current quote for a specified stock symbol (e.g., AAPL)
  - **getHistoricalData**: Retrieve historical data for a specified stock, with output structure depending on the interval parameter
- Can be used as a context provider to LLMs (such as Claude Desktop)
- Supports installation via Smithery or manual setup

## Category
Finance Market Data MCP Servers

## Tags
finance, market-data, api-integration, mcp

## Pricing
No specific pricing information is provided. The server itself is open-source and released under the MIT License, but use of the Alpha Vantage API may require obtaining an API key, which may have its own terms or limits.