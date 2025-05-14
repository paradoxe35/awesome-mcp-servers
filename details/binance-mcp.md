# Binance MCP

[GitHub Repository](https://github.com/snjyor/binance-mcp)

## Description
Binance MCP is a Model Context Protocol (MCP) server that integrates with the Binance cryptocurrency exchange to provide real-time market data, including prices, order books, candlestick charts, trading volume, and historical information. It enables AI agents and applications to access Binance market data without requiring API keys.

## Features
- Provides real-time cryptocurrency market data from Binance
- Does not require API keys for access
- Exposes multiple tools for accessing various types of market information:
  - `get_price`: Retrieve the current price for a specified cryptocurrency
  - `get_order_book`: Access order book data
  - `get_recent_trades`: List recent trades
  - `get_historical_trades`: Access historical trade data
  - `get_aggregate_trades`: List aggregate trades
  - `get_klines`: Get K-line (candlestick) data
  - `get_ui_klines`: Get UI-optimized K-line data
  - `get_avg_price`: Retrieve current average price
  - `get_24hr_ticker`: Obtain 24-hour price change statistics
  - `get_trading_day_ticker`: Get trading day market information
  - `get_book_ticker`: Access order book ticker
  - `get_rolling_window_ticker`: Obtain rolling window price change statistics
- Can be integrated with AI agents and MCP-compatible environments (e.g., Cursor, Claude, Windsurf)
- Usage examples provided for querying prices, price movements, and candlestick data
- Open-source (Apache 2.0 license)

## Pricing
No pricing information provided; the project is open-source under the Apache 2.0 license.

## Tags
binance, market-data, real-time, crypto