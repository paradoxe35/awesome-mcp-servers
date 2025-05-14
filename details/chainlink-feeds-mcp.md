# chainlink-feeds-mcp

An MCP server granting real-time access to Chainlink's decentralized price feeds for AI agents and autonomous systems.

**Source:** [GitHub Repository](https://github.com/kukapay/chainlink-feeds-mcp)

**Category:** blockchain-crypto-mcp-servers

**Tags:** chainlink, price-feeds, real-time, blockchain

---

## Features
- **Real-time Price Feeds:** Provides real-time access to Chainlink's decentralized on-chain price feeds.
- **MCP Protocol Support:** Exposes five tools via the MCP protocol, accessible through platforms like Claude Desktop (for natural language queries) or MCP Inspector (for JSON inputs).
- **Supported Tools:**
  - `getLatestPrice`: Fetches the latest price for a given pair on a specified chain.
  - `queryPriceByRound`: Queries the price for a given pair and round ID on a specified chain.
  - `listSupportedChains`: Returns a list of all supported blockchain networks.
  - `listSupportedFeeds`: Returns a Markdown list of all supported chains and their price feed names.
  - `listSupportedFeedsByChain`: Returns a list of price feed names for a specified blockchain network.
- **Multi-Chain Support:** Supports 9 blockchain networks (ethereum, bsc, base, starknet, linea, mantle, scroll, zksync, celo) with a total of 329 price feeds.
- **Customizable Feeds:** Additional chains and feeds can be added by updating a configuration file (`feeds.json`).
- **Integration Ready:** Optimized for seamless integration into AI agents and autonomous systems.
- **Open Source:** Licensed under the MIT License.

## Pricing
No pricing information is provided. The server is open source and available under the MIT License.