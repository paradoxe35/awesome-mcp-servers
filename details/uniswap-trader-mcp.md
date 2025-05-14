# uniswap-trader-mcp

An MCP server for AI agents to automate token swaps on Uniswap DEX across multiple blockchains.

## Features
- Provides an MCP (Multi-Chain Protocol) server interface for AI agents.
- Automates token swaps on Uniswap DEX.
- Supports multiple blockchains:
  - Ethereum (Mainnet)
  - Optimism (Layer 2)
  - Polygon (MATIC)
  - Arbitrum (Arbitrum One)
  - Celo (CELO)
  - BNB Chain (Binance Smart Chain)
  - Avalanche (AVAX)
  - Base (Coinbase's Layer 2)
- Requires configuration for each chain (RPC URL, WETH address, SwapRouter address).
- Exposes two main tools/prompts:
  1. `getPrice`: Fetches a price quote for a Uniswap swap.
  2. `executeSwap`: Executes a swap on Uniswap.
- Designed for easy integration with AI agents and automation workflows.

## Source
[https://github.com/kukapay/uniswap-trader-mcp](https://github.com/kukapay/uniswap-trader-mcp)

## Category
blockchain-crypto-mcp-servers

## Tags
mcp, uniswap, blockchain, trading, ai-agent

## Pricing
No pricing information provided. The project is licensed under MIT License.