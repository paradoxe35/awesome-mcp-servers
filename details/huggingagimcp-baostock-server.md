# HuggingAGI/mcp-baostock-server

[MCP BaoStock Server](https://github.com/HuggingAGI/mcp-baostock-server) is a server application based on BaoStock, providing access to Chinese stock market data through multiple interfaces.

## Features
- Provides queries for basic stock information (e.g., listing date, industry classification)
- Supports retrieval of historical K-line (candlestick) data, including daily K-line with adjustable date ranges and adjustment types
- Allows querying of industry classification data for stocks
- Supports querying of dividend and distribution data for stocks
- Provides access to quarterly financial indicators, including:
  - Profitability (e.g., net profit, gross margin)
  - Operating capability (e.g., accounts receivable turnover, inventory turnover)
  - Growth capability (e.g., revenue growth rate, net profit growth rate)
- Enables querying of index data (e.g., daily price data for indexes like CSI 300)
- Provides valuation indicator data (e.g., PE ratio, PB ratio) over time for stocks

## Requirements
- Python 3.10+
- baostock
- pandas

## Usage
- Install dependencies
- Run the server with: `uv run mcp-baostock-server`

## Category
Finance Market Data MCP Servers

## Tags
baostock, market-data, china, finance

## Pricing
No pricing information provided; this appears to be an open-source project.

---
[View on GitHub](https://github.com/HuggingAGI/mcp-baostock-server)
