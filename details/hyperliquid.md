# Hyperliquid MCP Server

**Category:** Finance Market Data MCP Servers  
**Tags:** trading, market-data, crypto, mcp, ai-assistant  
**Source:** [Hyperliquid MCP Server Documentation](https://ubos.tech/mcp/hyperliquid-mcp-server/)

## Description
The Hyperliquid MCP Server is a comprehensive Model Context Protocol (MCP) server that provides a full-featured wrapper around the Hyperliquid SDK. It enables AI assistants to interact programmatically with the Hyperliquid crypto exchange for spot and futures trading, allowing for data retrieval, trading execution, account and position management, and more.

## Features

### API Coverage
- **Market Data APIs:**
  - `getAllMids`: Retrieve mid prices for all cryptocurrencies
  - `getL2Book`: Access order book data for a symbol
  - `getCandleSnapshot`: Fetch historical candle data
  - `getMetaAndAssetCtxs`: Metadata/asset contexts for perpetual futures
  - `getSpotMetaAndAssetCtxs`: Metadata/asset contexts for spot markets

- **Account Information APIs:**
  - `getClearinghouseState`: Perpetual futures account state
  - `getSpotClearinghouseState`: Spot account state
  - `getUserOpenOrders`: Open orders
  - `getUserFills` / `getUserFillsByTime`: Trade fills (by time range)
  - `getUserFunding`: Funding payments
  - `getFundingHistory`: Funding rate history
  - `getPredictedFundings`: Predicted funding rates

- **Order Management APIs:**
  - `placeOrder`: Place market, limit, or trigger orders
  - `placeTwapOrder`: Place TWAP orders
  - `cancelOrder`, `cancelOrderByCloid`, `cancelTwapOrder`: Cancel orders
  - `modifyOrder`: Modify existing orders

- **Position Management APIs:**
  - `updateLeverage`: Update leverage for a symbol
  - `updateIsolatedMargin`: Update isolated margin
  - `marketClose`: Close a position with market order
  - `closeAllPositions`: Close all positions

- **Transfer and Withdrawal APIs:**
  - `usdTransfer`: Transfer USDC to another wallet
  - `initiateWithdrawal`: Withdraw USDC to Arbitrum
  - `spotTransfer`: Transfer spot assets
  - `transferBetweenSpotAndPerp`: Transfer between spot and perpetual accounts

- **Vault Management APIs:**
  - `createVault`: Create a vault
  - `getVaultDetails`: Get vault details
  - `vaultTransfer`: Transfer funds between vault and wallet
  - `vaultDistribute`: Distribute funds from vault to followers
  - `vaultModify`: Modify vault configuration

- **Sub-Account Management APIs:**
  - `createSubAccount`: Create sub-accounts
  - `getSubAccounts`: List sub-accounts
  - `subAccountTransfer`: Transfer funds between sub-accounts (perpetual)
  - `subAccountSpotTransfer`: Transfer spot assets between sub-accounts

- **Miscellaneous APIs:**
  - `setReferrer`, `referral`: Referral management
  - `setDisplayName`: Set leaderboard display name
  - `getUserRole`: Retrieve user role
  - `approveAgent`: Approve agent trading
  - `approveBuilderFee`: Approve builder fee

### Technical Features
- **Authentication:** Supports both private key and wallet address authentication, with validation for all operations.
- **WebSocket Support:** Real-time data via WebSocket connections.
- **Comprehensive Error Handling:**
  - Client, authentication, and parameter validation
  - Clear error messages and logging for all operations
- **Implementation Details:**
  - Market orders implemented as aggressive limit orders with IOC
  - Spot market symbols managed with “-SPOT” suffix
  - Numeric values converted from strings to numbers for usability
- **Configuration:**
  - Supports environment variables and configuration file (`.hyperliquid-config.json`)
- **Security:** Operations require appropriate authentication, and all sensitive actions are validated.

## Prerequisites
- Requires configuration through environment variables or a JSON config file.

## Resources
- Market data, account, order, position, transfer, vault, sub-account, and miscellaneous tools for interacting with the Hyperliquid exchange.

## Pricing
No pricing information provided in the available content.

---
**Disclaimer:** Cryptocurrency trading involves significant risk. This tool is for educational and informational use only.