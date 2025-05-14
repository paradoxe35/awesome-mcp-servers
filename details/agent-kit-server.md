# agent-kit-server

A Model Context Protocol (MCP) server that enables AI agents, such as Claude, to interact with the Solana blockchain through a standardized interface. Powered by the Solana Agent Kit, this server facilitates advanced blockchain integration for AI-driven workflows.

**Source:** [https://github.com/sendaifun/solana-mcp](https://github.com/sendaifun/solana-mcp)

## Features
- **Solana Blockchain Integration:** Seamlessly interact with the Solana blockchain for onchain operations.
- **Standardized MCP Interface:** Implements the Model Context Protocol specification for AI agent compatibility.
- **Transaction Execution:** Execute standard Solana transactions.
- **Account Management:** Query account information and manage Solana wallets.
- **Available Blockchain Tools:**
  - `GET_ASSET`: Retrieve information about a Solana asset or token.
  - `DEPLOY_TOKEN`: Deploy new tokens on Solana.
  - `GET_PRICE`: Fetch price information for tokens.
  - `WALLET_ADDRESS`: Get the wallet address.
  - `BALANCE`: Check wallet balance.
  - `TRANSFER`: Transfer tokens between wallets.
  - `MINT_NFT`: Mint new NFTs.
  - `TRADE`: Execute token trades.
  - `REQUEST_FUNDS`: Request funds (useful for testing and development).
  - `RESOLVE_DOMAIN`: Resolve Solana domain names.
  - `GET_TPS`: Get current transactions per second on Solana.
- **Supports 40+ Protocol Actions:** Extensible for a wide range of blockchain operations (see repository for full list).
- **Integration with Claude Desktop:** Easily integrates with Claude Desktop for AI workflows.
- **Multiple Installation Methods:**
  - Quick install script
  - npm (global or local)
  - Build from source
- **Configurable via Environment Variables:** Secure management of private keys and RPC URLs.
- **Security Recommendations:**
  - Use environment variables for sensitive data
  - Dedicated wallet usage for AI operations
  - Monitor and audit agent activities
- **Open Source:** MIT licensed, contributions welcome.

## Dependencies
- `@solana/web3.js`
- `@modelcontextprotocol/sdk`
- `solana-agent-kit`

## Pricing
No pricing information is provided; the project is open source under the MIT license.