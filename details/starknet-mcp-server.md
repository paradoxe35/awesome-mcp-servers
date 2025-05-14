# starknet-mcp-server

**Source:** [GitHub Repository](https://github.com/mcpdotdirect/starknet-mcp-server)

**Category:** blockchain-crypto-mcp-servers

**Tags:** blockchain, starknet, smart-contracts, mcp

---

## Description

`starknet-mcp-server` is a Model Context Protocol (MCP) server designed to integrate with the Starknet blockchain. It provides tools and resources for AI agents (such as LLMs) and applications to interact with the Starknet ecosystem, including native token operations, smart contract interactions, and StarknetID resolution. The server supports both stdio and HTTP modes, making it suitable for use with AI assistants, CLI tools, and web applications.

---

## Features

### Starknet Integration
- Full integration with Starknet via Starknet.js
- Supports both Mainnet and Sepolia testnet

### StarknetID Support
- Resolve Starknet IDs to addresses and vice versa
- Get full StarknetID profiles and validate domains

### Native Token Operations
- Query ETH and STRK balances for any address or StarknetID
- Transfer ETH and STRK between accounts
- View combined native token balances

### ERC20 Token Operations
- Query any ERC20 token balance and information
- Transfer ERC20 tokens between accounts
- View token supply and metadata

### NFT Operations
- Check NFT ownership by token ID
- Query NFT collections and balances

### Smart Contract Interaction
- Call read-only functions on Starknet smart contracts
- Execute contract writes with transaction handling
- Access contract storage, ABIs, and class information

### Blockchain Data Access
- Query chain info, blocks, transactions, and receipts
- View address and contract details

### Tooling and API
- Exposes a set of MCP tools for all supported operations (balance, transfer, contract calls, etc.)
- Exposes MCP resources for chain, block, address, transaction, and ID data
- Provides prompts for LLMs to explore blocks, addresses, transactions, and IDs

### Dual Transport Modes
- Can run as a stdio server (for CLI/AI integrations) or HTTP server (REST API + SSE)

### AI Assistant Compatibility
- Designed for integration with Claude, GPT, Cursor, and other LLM-powered tools

### Security
- Private keys are only used for transaction signing (not stored)
- All token amounts are handled in human-readable format
- Input validation and security best practices recommended for production use

### Extensible and Configurable
- Easily add custom MCP tools, resources, and prompts
- Open source, MIT-licensed, written in TypeScript

---

## Usage

- Install via npm/Yarn/pnpm or run directly with npx
- Can be used as a CLI, background service, or HTTP API
- Supports configuration for network, port, and host
- Easily integrated into AI workflow tools like Cursor and Claude CLI

---

## API Summary

### MCP Tools (Examples)
- `get_starknet_chain_info`, `get_supported_starknet_networks`
- `get_starknet_eth_balance`, `get_starknet_token_balance`, `get_starknet_strk_balance`, `get_starknet_native_balances`
- `resolve_starknet_name`, `resolve_starknet_address`, `get_starknet_profile`, `validate_starknet_domain`
- `get_starknet_block`, `get_starknet_block_transactions`, `get_starknet_transaction`, `get_starknet_transaction_receipt`, `check_starknet_transaction_status`
- `call_starknet_contract`, `execute_starknet_contract`, `get_starknet_contract_class`
- `get_starknet_token_info`, `get_starknet_token_supply`, `check_starknet_nft_ownership`, `get_starknet_nft_balance`
- `transfer_starknet_eth`, `transfer_starknet_strk`, `transfer_starknet_token`

### MCP Resources
- Network, block, address, transaction, and ID endpoints (see README for full list)

### MCP Prompts
- Prompts to explore blocks, addresses, transactions, Starknet IDs, and ID profiles

---

## Supported Networks
- Starknet Mainnet
- Starknet Sepolia Testnet

---

## Prerequisites
- Bun 1.0.0+ (recommended)
- Node.js 18.0.0+

---

## Installation & Running
- **npx:** `npx @mcpdotdirect/starknet-mcp-server` (stdio) or `npx @mcpdotdirect/starknet-mcp-server http` (HTTP)
- **npm global:** `npm install -g @mcpdotdirect/starknet-mcp-server`
- **Project install:** `npm install @mcpdotdirect/starknet-mcp-server`
- **From source:** Clone repo, install dependencies, run via npm scripts

---

## Licensing
- MIT License

---

## Pricing

This is an open-source project licensed under MIT. There are no pricing plans; usage is free.

---