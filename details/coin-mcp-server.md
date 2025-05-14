# coin-mcp-server

An MCP server using the Bitget API to fetch cryptocurrency prices.

- **Source:** [GitHub Repository](https://github.com/pwh-pwh/coin-mcp-server)
- **Category:** blockchain-crypto-mcp-servers
- **Tags:** mcp, crypto, market-data, api-integration

## Features
- Runs a server to query real-time cryptocurrency prices (paired with USDT) via the Bitget API
- Powered by FastMCP and uses `zod` for validation
- Provides the following tools/endpoints:
  - `getTokenPrice`: Fetches the latest price of a specific token (e.g., BGB, BTC, ETH)
  - `getAnnouncements`: Retrieves announcements (from Bitget)
  - `getCoinInfo`: Provides detailed information about a specified token, such as transferability, supported chain list, and chain network status
- Simple and fast API for market data retrieval
- Returns errors with logging if the token does not exist or if there is an API issue
- Configuration via `config.json`
- Runs in stdio mode
- Written in Deno
- Open source under the MIT License

## Pricing

No pricing information provided. The project is open source under the MIT license.