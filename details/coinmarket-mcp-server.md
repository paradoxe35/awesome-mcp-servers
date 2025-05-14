# coinmarket-mcp-server

**Description:**

Coinmarket MCP Server is an open-source server that integrates the Coinmarket API through the Model Context Protocol (MCP), allowing AI agents or clients to fetch cryptocurrency listings and real-time quotes.

**Source:** [GitHub Repository](https://github.com/anjor/coinmarket-mcp-server)

**Category:** Blockchain & Crypto MCP Servers

**Tags:** mcp, api-integration, market-data, crypto

---

## Features

- Implements selected Coinmarket API endpoints for cryptocurrency data access.
- Provides a custom `coinmarket://` URI scheme for accessing individual note resources.
- Each note resource includes a name, description, and is served with a `text/plain` MIME type.
- Exposes two main tools:
  - `get-currency-listings`: Fetches the latest cryptocurrency listings.
  - `get-quotes`: Retrieves quotes for tokens, accepting either a `slug` (e.g., "bitcoin") or a `symbol` (e.g., "BTC") as an argument.
- Requires a Coinmarket API key for operation.
- Written entirely in Python.
- MIT License.

## Configuration

- Requires configuration of the Coinmarket API key via environment variable `COINMARKET_API_KEY`.
- Can be set up for use with Claude Desktop or other MCP-compatible environments.

## Pricing

- Open source and free to use under the MIT License. No paid plans or commercial tiers are mentioned.
