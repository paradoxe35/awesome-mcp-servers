# solana-mcp-kit

A specialized MCP (Model Context Protocol) SDK and server for integrating the Solana blockchain with MCP servers, enabling AI assistants (such as Claude AI) to interact with the Solana ecosystem through a standardized protocol.

- **Source:** [https://github.com/sendaifun/solana-mcp](https://github.com/sendaifun/solana-mcp)
- **Category:** Blockchain, Crypto, MCP Servers
- **Tags:** solana, blockchain, ai-integration, sdk

---

## Features

- **MCP Server for Solana:** Implements a Model Context Protocol server to standardize Solana blockchain interactions for AI agents and assistants.
- **AI Integration:** Extends the capabilities of AI assistants (e.g., Claude AI) to interact with Solana blockchain.
- **Solana Blockchain Operations:**
  - Execute transactions
  - Query account and wallet information
  - Manage Solana wallets
- **Built on Solana Agent Kit:** Uses Solana Agent Kit for core blockchain operations.
- **Available Blockchain Tools:**
  - `GET_ASSET`: Retrieve information about a Solana asset or token
  - `DEPLOY_TOKEN`: Deploy a new token on Solana
  - `GET_PRICE`: Fetch price information for tokens
  - `WALLET_ADDRESS`: Get the wallet address
  - `BALANCE`: Check wallet balance
  - `TRANSFER`: Transfer tokens between wallets
  - `MINT_NFT`: Create and mint new NFTs
  - `TRADE`: Execute token trades
  - `REQUEST_FUNDS`: Request funds (for testing/development)
  - `RESOLVE_DOMAIN`: Resolve Solana domain names
  - `GET_TPS`: Get the current transactions per second on Solana
- **Integration with Claude Desktop:** Can be configured as an MCP server for Claude Desktop via JSON configuration.
- **Multiple Installation Options:**
  - Install via quick install script
  - Install from npm (globally or locally)
  - Build from source
- **Environment Configuration:** Supports environment variables for private keys, RPC URLs, and optional OpenAI API key.
- **Security Recommendations:** Advises on best practices for key management and testnet/mainnet usage.
- **Dependencies:**
  - `@solana/web3.js`
  - `@modelcontextprotocol/sdk`
  - `solana-agent-kit`
- **Open Source:** Licensed under the MIT License.

---

## Pricing

No pricing information provided; the project is open source under the MIT License.

---

## Requirements

- Node.js v16 or higher
- pnpm (recommended), npm, or yarn
- A Solana wallet with a private key
- Solana RPC URL (mainnet, testnet, or devnet)

---

## Links

- [GitHub Repository](https://github.com/sendaifun/solana-mcp)
- [Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit)
