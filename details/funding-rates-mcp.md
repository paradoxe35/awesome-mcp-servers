# funding-rates-mcp

[GitHub Repository](https://github.com/kukapay/funding-rates-mcp)

An MCP server that provides real-time funding rate data across major crypto exchanges, enabling agents to detect arbitrage opportunities.

## Features
- **Real-Time Funding Rates**: Fetches current funding rate data from major crypto exchanges including Binance, OKX, Bybit, Bitget, Gate, and CoinEx.
- **Pivoted Table Output**: Presents funding rates in a pivoted Markdown table with symbols as rows, exchanges as columns, and a Divergence column showing the maximum funding rate difference per symbol.
- **MCP Tool `compare_funding_rates`**: Allows querying of funding rates for multiple trading pairs across specified exchanges, with options to specify symbols and exchanges.
- **MCP Prompt `compare_funding_rates_prompt`**: Generates natural language prompts for comparing funding rates, suitable for integration with Claude Desktop.
- **Claude Desktop Integration**: Can be run as an MCP server for interactive queries and tools within Claude Desktop.
- **Arbitrage Detection**: The divergence column helps identify the largest funding rate differences, assisting in arbitrage opportunity detection.
- **Open Source**: Licensed under the MIT License.

## Installation
- Requires Python 3.10+, `uv` for dependency management, and optionally Claude Desktop for interactive use.
- Clone the repository and install dependencies using `uv sync`.
- Integration instructions are provided for Claude Desktop on macOS and Windows.

## Usage
- Query funding rates using the provided MCP tools or via Claude Desktop.
- Returns Markdown tables with real-time data for specified symbols and exchanges.

## Pricing
- **Free and Open Source**: Licensed under the MIT License.

## License
MIT License.