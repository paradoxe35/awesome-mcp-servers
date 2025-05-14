# evm-mcp-server

A comprehensive Model Context Protocol (MCP) server for blockchain services across 30+ EVM-compatible networks. Enables AI agents and applications to interact with Ethereum, Optimism, Arbitrum, Polygon, Base, and many more chains through a unified interface.

**Source:** [GitHub - mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server)

## Features

### Blockchain Data Access
- Multi-chain support for 30+ EVM-compatible networks (Ethereum, Optimism, Arbitrum, Polygon, Base, Avalanche, BSC, etc.)
- Chain information retrieval (blockNumber, chainId, RPC URLs)
- Access block data by number, hash, or latest
- Retrieve transaction details and receipts with decoded logs
- Address balance queries for native tokens and all supported token standards
- ENS resolution for human-readable Ethereum addresses (e.g., 'vitalik.eth')

### Token Services
- **ERC20:**
  - Get token metadata (name, symbol, decimals, supply)
  - Check token balances
  - Transfer tokens
  - Approve spending allowances
- **NFTs (ERC721):**
  - Get collection and token metadata
  - Verify token ownership
  - Transfer NFTs
  - Retrieve token URIs and count holdings
- **ERC1155 (Multi-tokens):**
  - Get token balances and metadata
  - Transfer tokens with quantity
  - Access token URIs

### Smart Contract Interactions
- Read contract state (view/pure functions)
- Write to contracts with private key signing
- Contract verification (distinguish contract from EOA)
- Retrieve and filter event logs

### Transactions
- Native token transfers across all supported networks
- Gas estimation for transactions
- Transaction status and receipt information
- Error handling with descriptive messages

### ENS Support
- ENS name resolution for all address parameters in tools/resources

### API and Tools
- Exposes MCP tools for ERC20/NFT/ERC1155/token operations, contract reads/writes, ENS resolution, etc.
- Resource URIs for chain, block, address, transaction, token, NFT, and ERC1155 data
- Supports both CLI (stdio) and HTTP/SSE server modes
- Integration with Cursor and Claude CLI

### Security Considerations
- Private keys are only used for transaction signing (never stored)
- Recommendations for HTTPS, authentication, and rate limiting in production

### Developer Experience
- Easily extensible (add new services/tools/resources/networks)
- Hardcoded config (chain, server port/host) can be modified in source

## Supported Networks (selection)
- Mainnets: Ethereum, Optimism, Arbitrum, Base, Polygon, Avalanche, BSC, zkSync, Linea, Celo, Gnosis, Fantom, Filecoin, Moonbeam, Cronos, Scroll, Mantle, Blast, and more
- Testnets: Sepolia, Goerli, Holesky, Fuji, Amoy, and others

## Installation & Usage
- Requires [Bun](https://bun.sh/) 1.0.0+ or Node.js 18.0.0+
- Install dependencies with `bun install` or `npm install`
- Run server via `bun start`, `bun start:http`, or with `npx @mcpdotdirect/evm-mcp-server`
- Integrate with Cursor via `.cursor/mcp.json` or with Claude CLI

## License
MIT License

## Pricing
Free and open source (MIT License). No pricing plans.

---
**Category:** blockchain-crypto-mcp-servers  
**Tags:** blockchain, evm, smart-contracts, nft, mcp