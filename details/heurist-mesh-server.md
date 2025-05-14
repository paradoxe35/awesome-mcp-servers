# Heurist Mesh Server

**Category:** blockchain-crypto-mcp-servers  
**Tags:** blockchain, web3, cryptocurrency, mcp, api-integration

## Description
Heurist Mesh Server is an MCP server that enables AI systems (such as Claude and Cursor) to connect to specialized Web3 and blockchain tools for cryptocurrency research, token verification, blockchain analysis, and token security. It provides a unified interface to multiple Web3 APIs and agents through a single API key.

## Features
- **Integration with Multiple Blockchain Tools:** Connects to CoinGecko, DexScreener, GoPlus, Exa, Firecrawl, and more through the Heurist Mesh network.
- **AI Agent Support:** Interfaces with specialized AI agents handling:
  - Cryptocurrency data
  - Blockchain analysis
  - Token security
  - Web3 data analysis
- **Single API Key Access:** Access all integrated services with one API key.
- **Multiple Installation Options:**
  - UV package manager (recommended)
  - Docker
- **Supports Claude Desktop and Cursor:**
  - stdio transport for Claude Desktop
  - SSE transport for Cursor
  - Hosted SSE endpoint also available
- **Customizable Agent Selection:**
  - Edit the DEFAULT_AGENTS list in configuration to add or remove agents.
- **Available Tools:**
  - **CoinGecko:**
    - Search for token by name
    - Get detailed token information
    - Fetch trending coins
  - **DexScreener:**
    - Get trading pair info by chain and address
    - Retrieve all trading pairs for a token
    - Get info on latest tokens
    - Search pairs by token name, symbol, or address
  - **Twitter Intelligence:**
    - Get trending tokens on Twitter
    - Analyze Twitter accounts for mentions and stats
    - Search for token/topic mentions
  - **Web Search (via Exa):**
    - Direct answers to queries
    - Webpage search
    - Combined search and answer operations
  - **Token Security:**
    - Security analysis of blockchain token contracts
- **Shared Hosted SSE Endpoint:** Available for quick setup with common agents pre-included.
- **Open Source:** Python-based, available on GitHub.

## Installation
- Python 3.10+ required
- Optionally use UV package manager or Docker
- Requires a Heurist API key (free credits available with invite code)

## Usage
- Integrates with Claude Desktop and Cursor via configuration files
- Can be used via local install or hosted SSE endpoint
- Full documentation and agent metadata available online

## Pricing
- No pricing information provided in the available content. (Free API credits may be available with an invite code.)

## Source
[Heurist Mesh Server Documentation](https://playbooks.com/mcp/heurist-mesh-web3-tools)