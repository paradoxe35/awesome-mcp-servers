# evm-server

A Model Context Protocol (MCP) server enabling AI agents to interact with over 30 Ethereum-compatible blockchain networks for token transfers, contract interactions, and ENS resolution.

**Source:** [GitHub Repository](https://github.com/evmcp/EVM-MCP-Server)

**Category:** blockchain-crypto-mcp-servers

**Tags:** blockchain, evm, ethereum, mcp

---

## Features

- **Unified Interface for EVM Chains:** Supports Ethereum, Optimism, Arbitrum, Base, Polygon, and many other EVM-compatible blockchains (mainnets and testnets).
- **Blockchain Data Access:** Retrieve chain, block, transaction, and address data.
- **Token Services:**
  - ERC20: Token metadata, balances, transfers, approvals.
  - NFTs (ERC721): Metadata, ownership checks, transfers, balances.
  - ERC1155: Metadata, balances, transfers.
- **Smart Contract Interactions:**
  - Read and write to smart contracts (with ABI, function name, args).
  - Check if an address is a contract.
- **Comprehensive Transaction Support:**
  - Native token (ETH) transfers.
  - Transaction retrieval and receipts.
- **ENS Resolution:** All address fields support ENS names, which are resolved automatically.
- **MCP Tools:** Exposes all services via a consistent set of MCP tools for programmatic access.
- **MCP Resource URIs:** Standardized URIs for accessing blockchain and token data.
- **Multiple Modes:**
  - Run as a local server (stdio or HTTP with SSE for web apps).
  - Integrates with tools like Cursor and Claude CLI.
- **Configuration:** Easily configurable via project files (e.g., `.cursor/mcp.json`).
- **Open Source:** Licensed under MIT.

### API Tools Overview
- **Token Tools:** `get-token-info`, `get-token-balance`, `transfer-token`, `approve-token-spending`, `get-nft-info`, `check-nft-ownership`, `transfer-nft`, `get-nft-balance`, `get-erc1155-token-uri`, `get-erc1155-balance`, `transfer-erc1155`.
- **Blockchain Tools:** `get-chain-info`, `get-balance`, `transfer-eth`, `get-transaction`, `read-contract`, `write-contract`, `is-contract`, `resolve-ens`.

### Resource Endpoints
- `evm://{network}/chain` — Network info
- `evm://{network}/block/{blockNumber}` — Block data
- `evm://{network}/address/{address}/balance` — Native token balance
- `evm://{network}/tx/{txHash}` — Transaction details
- `evm://{network}/token/{tokenAddress}` — ERC20 token info
- `evm://{network}/nft/{tokenAddress}/{tokenId}` — NFT info
- ...and more.

---

## Pricing

No pricing information provided (open source under MIT License).
