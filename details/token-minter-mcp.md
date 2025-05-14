# token-minter-mcp

An MCP server that provides tools for AI agents to mint ERC-20 tokens across multiple blockchains.

Source: [https://github.com/kukapay/token-minter-mcp](https://github.com/kukapay/token-minter-mcp)

Category: blockchain-crypto-mcp-servers

Tags: blockchain, erc20, token-minting, mcp

---

## Features

- **Deploy ERC-20 tokens** with customizable parameters (name, symbol, initial supply, decimals, chainId) across 21 supported blockchains.
- **Query token metadata:** Retrieve information such as name, symbol, decimals, and total supply.
- **Initiate token transfers:** Send ERC-20 tokens to other addresses (returns transaction hash without confirmation).
- **Retrieve transaction details** by transaction hash.
- **Check native token balance** of the current account (e.g., ETH, POL, BNB, etc.).
- **Access token metadata via URI** (e.g., `token://{chainId}/{address}`).
- **Interactive deployment guide:** Prompt-based assistance for deploying tokens.
- **Tools provided:**
  - `deployToken`: Deploy new ERC-20 tokens.
  - `transferToken`: Transfer ERC-20 tokens.
  - `getTransactionInfo`: Get transaction details.
  - `getTokenBalance`: Query ERC-20 token balance for the current account.
  - `getTokenInfo`: Query ERC-20 token metadata.
  - `getBalance`: Check native token balance.
- **Local testing support** via Hardhat node (chainId: 1337).
- **Supported blockchains:** Ethereum, Polygon, BSC, Arbitrum, Optimism, Linea, Base, Blast, Palm, Avalanche, Celo, zkSync, Mantle, opBNB, Scroll, Swellchain, Unichain, Starknet, Berachain, Hyperliquid, Sonic, Localhost.
- **MIT License.**

## Prerequisites

- Node.js v18.x or higher
- npm
- Infura API key for EVM network access
- Ethereum private key for signing transactions

## Installation & Usage

- Clone the repository and install dependencies.
- Configure environment variables (INFURA_KEY, PRIVATE_KEY).
- Start the server and use provided tools via prompts or API.

## Pricing

No pricing information is provided; the project is open-source under the MIT License.
