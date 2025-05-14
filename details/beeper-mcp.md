# beeper-mcp

A backend service for executing beeper transactions on Binance Smart Chain (BSC). It provides tools for interacting with the BSC blockchain, supporting token transfers, swaps, and reward claims for AI agents.

## Features
- **Wallet and Token Management**
  - Get the default wallet address
  - Get the default token address
  - Switch to a new default token address
- **Balance Operations**
  - Get BNB balance of an address
  - Get token balance of an address
- **Transfer Operations**
  - Transfer BNB to an address
  - Transfer tokens to an address
- **Trading Operations**
  - Swap tokens using Pancakeswap
  - Get token price in BNB
  - Buy tokens with BNB
  - Sell tokens for BNB
- **Reward Operations**
  - Claim rewards for a token
- **Server and Configuration**
  - Supports BSC mainnet and testnet
  - Exposes API endpoints for all operations
  - All operations return detailed responses with transaction hashes and status
  - Built-in error handling and status tracking for transactions
  - Can be run over stdio or SSE (default port 8000, configurable)
- **Requirements**
  - Python >=3.10
  - Access to BSC (mainnet or testnet)
  - Wallet account and private key
- **Other Notes**
  - All amounts are in native units (BNB, tokens)
  - Requires sufficient BNB for gas fees

## Pricing
No pricing information is provided; the project is open source on GitHub.

## Source
[https://github.com/intentos-labs/beeper-mcp](https://github.com/intentos-labs/beeper-mcp)

## Tags
mcp, blockchain, binance, crypto