# yfinance-trader-mcp-claudedesktop

**Category:** Finance Market Data MCP Servers  
**Source:** [GitHub Repository](https://github.com/SaintDoresh/YFinance-Trader-MCP-ClaudeDesktop.git)

## Description
YFinance Trader MCP ClaudeDesktop is a Model Context Protocol (MCP) tool that provides stock market data and trading capabilities using the yfinance library, specifically adapted for Claude Desktop. It allows users to access real-time and historical financial data, company metrics, analyst recommendations, and more directly within the Claude Desktop environment.

## Features
- **Real-time Stock Quotes:** Retrieve current price, change, volume, and other details for stocks.
- **Company Information & Financial Metrics:** Access key company data such as sector, market cap, P/E ratio, dividend yield, 52-week high/low, etc.
- **Historical Price Data:** Fetch daily historical price data for stocks.
- **Symbol Search:** Search for stocks and other securities by name or ticker.
- **Analyst Recommendations:** Get up-to-date analyst ratings and recommendations for stocks.
- **Insider Transaction Tracking:** View recent insider trading activity for companies, including transaction details.
- **Cryptocurrency Support:** Limited data for cryptocurrencies using tickers like BTC-USD, ETH-USD, DOGE-USD.
- **Error Handling:** Robust error messages if data cannot be retrieved or processed.
- **Integration with Claude Desktop:** Easily configure as an MCP server for Claude Desktop.
- **Python 3.10+ Support:** Requires Python 3.10 or higher.
- **Direct MCP Integration:** Uses the MCP library directly for Claude Desktop integration.
- **Customizable Configuration:** Adaptable MCP configuration for user setups.

## Available Tools/Endpoints
1. **get_stock_quote:** Real-time stock quote information.
2. **get_company_overview:** Company profile & financial metrics.
3. **get_time_series_daily:** Historical daily price data.
4. **search_symbol:** Symbol search functionality.
5. **get_recommendations:** Analyst recommendations.
6. **get_insider_transactions:** Insider trading information.

## Differences from Similar Projects
- Uses MCP library directly (not FastAPI).
- Adapted for Claude Desktop instead of Cursor.
- Improved error handling and response formats.
- Updated configuration method.

## Setup
- Requires Python 3.10 or higher.
- Install dependencies with `pip install -r requirements.txt`.
- Integrate into Claude Desktop by updating your MCP configuration.

## License
MIT License

## Pricing
- **Open Source / Free** (No pricing plans or paid tiers indicated)

---
For more detailed setup instructions and usage, visit the [GitHub repository](https://github.com/SaintDoresh/YFinance-Trader-MCP-ClaudeDesktop.git).