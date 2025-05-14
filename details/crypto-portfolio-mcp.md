# crypto-portfolio-mcp

An MCP server for tracking and managing cryptocurrency portfolio allocations, designed for integration with AI agents.

**Source:** [GitHub Repository](https://github.com/kukapay/crypto-portfolio-mcp)

## Features
- **Portfolio Management:** Add and track cryptocurrency holdings with real-time Binance prices.
- **Price Retrieval:** Fetch current prices for any Binance trading pair (e.g., BTC/USDT).
- **Value History:** Generate visual charts (PNG) of portfolio value over time.
- **Portfolio Analysis Prompt:** Pre-built prompt for portfolio analysis, including diversification and risk suggestions based on current holdings and Binance market trends.
- **SQLite Storage:** Persistent storage of holdings in a local SQLite database (`portfolio.db`).
- **MCP Tools Exposed:**
  - `get_portfolio_summary`: Retrieves a text summary of the current portfolio.
  - `add_holding(coin_symbol: str, amount: float)`: Adds a cryptocurrency holding (e.g., "BTC", 0.1).
  - `get_price(coin_symbol: str)`: Fetches the current price of a trading pair from Binance.
  - `portfolio_value_history()`: Generates a PNG chart of portfolio value history.
- **AI Integration:** Designed for use with AI agents (e.g., Claude Desktop) to enable real-time querying and optimization of portfolio strategies.
- **Database Schema:**
  - Table: `holdings`
    - `id`: Primary key
    - `coin_symbol`: Cryptocurrency trading pair (e.g., "BTC/USDT")
    - `amount`: Quantity of the asset
    - `purchase_date`: ISO format timestamp
- **Open Source:** Licensed under the MIT License.

## Pricing
- The project is open source and free to use under the MIT License. No pricing plans are mentioned.

## Tags
`mcp`, `crypto`, `portfolio-management`, `ai-integration`

## Category
blockchain-crypto-mcp-servers