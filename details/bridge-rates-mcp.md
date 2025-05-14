# bridge-rates-mcp

An MCP server that provides real-time cross-chain bridge rates and optimal transfer routes for onchain AI agents.

## Features
- **Get Bridge Rates**: Retrieve real-time cross-chain bridge rates for token pairs, including USD values, gas costs, route providers, and tags, presented in a Markdown table.
- **List Supported Chains**: Fetches a sorted list of blockchain networks supported by LI.FI for bridging.
- **List Supported Bridges**: Obtain a sorted list of bridges and exchanges available for cross-chain transfers.
- **Integration with MCP Clients**: Designed to be integrated with MCP-compatible clients (e.g., Claude Desktop).
- **API Tools**:
  - `getBridgeRates`: Fetches bridge rates and routes for specific token pairs between chains.
  - `getSupportedChains`: Lists all supported chains for cross-chain bridging.
  - `getSupportedBridges`: Lists all supported bridges and exchanges.
- **Markdown Output**: All main outputs (rates, chains, bridges) are provided as Markdown tables for easy integration.
- **Open Source**: Licensed under the MIT license.

## Prerequisites
- Node.js (version 18 or higher)
- npm
- MCP-compatible client (optional, for integration)

## Installation
1. Clone the repository: `git clone https://github.com/kukapay/bridge-rates-mcp.git`
2. Install dependencies: `npm install`
3. Integrate with your MCP client as documented in the repository.

## Pricing
- The project is open source and available under the MIT License (free to use).

## Source
[https://github.com/kukapay/bridge-rates-mcp](https://github.com/kukapay/bridge-rates-mcp)
