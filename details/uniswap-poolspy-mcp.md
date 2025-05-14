# uniswap-poolspy-mcp

An MCP server that tracks newly created liquidity pools on Uniswap across multiple blockchains.

- **Source:** [GitHub Repository](https://github.com/kukapay/uniswap-poolspy-mcp)
- **Category:** blockchain-crypto-mcp-servers
- **Tags:** uniswap, blockchain, monitoring, mcp

## Features
- Tracks newly created Uniswap V3 liquidity pools across 9 blockchain networks:
  - Ethereum
  - Base
  - Optimism
  - Arbitrum
  - Polygon
  - BNB Smart Chain (BSC)
  - Avalanche
  - Celo
  - Blast
- Provides real-time data for DeFi analysts, traders, and developers.
- Customizable time range and result limits for querying new pools.
- Supports sorting by:
  - Timestamp
  - Transaction count
  - Volume
  - TVL (Total Value Locked)
- Query parameters:
  - `chain`: Blockchain network (e.g., "ethereum", "base", etc.)
  - `order_by`: Sort field ("timestamp", "txcount", "volume", "tvl")
  - `time_range_seconds`: Lookback period in seconds (default: 300)
  - `limit`: Maximum number of pools to return (default: 100)
- Example output includes pool address, tokens, creation timestamp, block number, transaction count, volume (USD), and TVL (USD).
- Usable as an MCP plugin (e.g., with Claude Desktop).
- Open-source under the MIT License.

## Prerequisites
- Python 3.10 or higher
- `uv` for package management
- A valid The Graph API key
- MCP-compatible environment for full functionality (e.g., Claude Desktop)

## Installation & Usage
- Clone the repository and set up the environment
- Install dependencies using `uv`
- Configure The Graph API key in a `.env` file
- Run the MCP server with `uv run main.py`
- Integrate as an MCP plugin if required

## Pricing
- Open-source, licensed under MIT License. No pricing information or paid plans are specified.