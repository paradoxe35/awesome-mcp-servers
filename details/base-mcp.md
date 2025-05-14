# base-mcp

[MCP Server for Base Blockchain and Coinbase API](https://github.com/base/base-mcp)

## Overview
base-mcp is a Model Context Protocol (MCP) server that enables Claude AI to interact with the Base blockchain and the Coinbase API. It provides tools for cryptocurrency operations such as wallet management, fund transfers, and smart contract deployment.

## Features
- **Wallet Address Retrieval:** Retrieve wallet addresses managed by the server.
- **Get Testnet ETH:** Obtain testnet ETH (on Base Sepolia) for the wallet.
- **List Wallet Balances:** List all balances for the wallet across supported assets.
- **Fund Transfers:** Transfer funds between wallets, specifying destination address, asset ID, and amount.
- **Smart Contract Deployment:** Deploy smart contracts to the blockchain, including providing constructor arguments, contract name, Solidity input JSON, and compiler version.
- **Integration with Claude Desktop:** Easily integrate the server with Claude Desktop via configuration.
- **Coinbase SDK Integration:** Uses the Coinbase SDK to interact with both the Base blockchain and Coinbase services.
- **Test and Verification Scripts:** Provides scripts to verify server operation and available tools.
- **npm Package:** Available as an npm package for easy installation and updates.
- **Open Source:** Licensed under MIT and open to contributions.

## Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Coinbase API credentials
- Wallet seed phrase (mnemonic)

## Installation
- Install globally via npm: `npm install -g base-mcp`
- Or install locally in your project: `npm install base-mcp`
- Alternatively, clone and build from source.

## Security Considerations
- Sensitive credentials (API keys, seed phrases) must be stored securely.
- Use environment variables or secure credential managers.
- Exercise caution with irreversible blockchain operations.

## License
MIT License

## Pricing
base-mcp is open source and free to use (MIT License).