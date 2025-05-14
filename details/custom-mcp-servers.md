# Custom MCP Servers

- **Category:** Business & Commerce / MCP Servers
- **Tags:** finance, csv, personal-finance, mcp
- **Source:** [GitHub Repository](https://github.com/financial-datasets/mcp-server)

## Description
Custom MCP Servers is an open-source Model Context Protocol (MCP) server designed to process and categorize financial transaction data. It interacts with the Financial Datasets stock market API and provides organized data outputs (such as CSV files) for personal finance management. The server exposes a set of tools for retrieving various financial data, making it useful for AI assistants and finance-related applications.

## Features
- **Stock Market Data Access:** Provides access to financial data via the Financial Datasets API.
- **Available Tools:**
  - `get_income_statements`: Retrieve income statements for a specific stock.
  - `get_balance_sheets`: Retrieve balance sheets for a stock.
  - `get_cash_flow_statements`: Retrieve cash flow statements for a stock.
  - `get_current_price`: Get the latest stock price information.
  - `get_prices`: Fetch historical stock prices with customizable date ranges and intervals.
  - `get_news`: Retrieve the latest news for a stock.
- **MCP Server Implementation:** Can be integrated with AI assistants (such as Claude Desktop) via the MCP protocol.
- **Personal Finance Management:** Organizes and outputs transaction data into CSV files for easier personal finance tracking and management.
- **Python-Based:** Implemented in Python (requires Python 3.10+).
- **Open Source:** Licensed under the MIT License.
- **Customizable & Extensible:** Can be set up and configured locally, and extended for additional finance-related tasks.

## Setup Requirements
- Python 3.10 or higher
- `uv` package manager
- Financial Datasets API key

## Integration
- Compatible with Claude Desktop for direct use by AI assistants.

## Pricing
- **Open Source:** Free to use under the MIT license (no pricing plans mentioned).

---
For more details and installation instructions, visit the [GitHub repository](https://github.com/financial-datasets/mcp-server).