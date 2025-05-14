# xrpl-mcp-server

A comprehensive Model Context Protocol (MCP) server that provides blockchain services for the XRP Ledger ecosystem. It enables AI agents to interact with XRPL MainNet, TestNet, and DevNet through a unified interface.

**Source:** [GitHub - RomThpt/mcp-xrpl](https://github.com/RomThpt/mcp-xrpl)

## Features

### Account Management
- Connect to XRPL networks (MainNet, TestNet, DevNet)
- Retrieve account information
- Manage account properties
- Deposit preauthorization
- Regular key management

### XRP and Token Operations
- Transfer XRP between accounts
- Retrieve token metadata (name, symbol, decimals, supply)
- Check token balances
- Transfer tokens between addresses
- Approve token spending
- Token clawback

### NFT Operations
- Mint NFTs on the XRP Ledger
- View NFT metadata
- Verify NFT ownership
- Transfer NFTs between addresses
- Retrieve NFT collections

### Decentralized Identifier (DID)
- Create, resolve, update, and deactivate DIDs on XRPL

### Automated Market Maker (AMM) Operations
- Create AMMs
- Deposit to AMMs
- Place bids on AMMs
- Vote on AMM parameters
- Delete AMMs
- Clawback assets from AMMs

### Check Operations
- Create checks
- Cash checks
- Cancel checks

### Offer/DEX Operations
- Create offers
- Cancel offers

### Oracle Operations
- Set oracle data
- Delete oracle data

### Payment Channels
- Create payment channels
- Fund payment channels
- Claim from payment channels

### Escrow
- Create, finish, and cancel escrows

### Trustlines
- Set and manage trustlines

### Ticketing
- Create tickets for transaction processing

### API Tools and Resource URIs
- MCP tools for agents to perform all above operations
- Resource URIs to access ledger, account, token, NFT, transaction, and balance information

### Supported Networks
- MainNet (Production)
- TestNet (Development)
- DevNet (Experimental)

### Security Considerations
- Wallet seeds used only for transaction signing
- Environment variables for sensitive configuration
- Default operations on TestNet for safety

### Development
- Modular architecture with separate directories for each transaction type
- Easily extensible with new tools

## Installation
- Requires Node.js 18.0.0 or higher
- Clone repository, install dependencies (`npm install`), and build (`npm run build`)

## License
MIT License

## Pricing
No pricing information provided; project is open-source under MIT license.

## Tags
`blockchain` `xrp` `ledger` `open-source`