# wowinter13/solscan-mcp

**Description:**
A Model Context Protocol (MCP) server for querying Solana blockchain transactions, token information, and account activities using natural language via the Solscan Pro API. Implemented in Rust.

**Source:** [GitHub Repository](https://github.com/wowinter13/solscan-mcp)

**Category:** Blockchain, Crypto, MCP Servers

**Tags:** solana, blockchain, natural-language, transactions

---

## Features
- Provides an MCP server interface for Solscan Pro API on Solana blockchain.
- Enables querying of token information, account activities, and transaction details using natural language prompts.
- Integrates with Large Language Models (LLMs) to facilitate natural language queries and context-aware investigation.
- Supports complex queries, such as analyzing multiple addresses for specified activities (e.g., investigating criminal wallets based on behavior like MEV, dusting, poisoning, sandwich attacks, etc.).
- Allows uploading lists of addresses (e.g., CSV format) for batch analysis.
- Designed for easy maintenance and robust error handling (errors are ignored to prevent crashes).
- Can be installed via Cargo for Rust users; Docker support is planned (work in progress).
- Requires a Solscan Pro API key for operation.
- Open source under the MIT license.

## Installation
- Install via Cargo: `cargo install solscan-mcp`
- Configure with your Solscan API key in the environment variables (see documentation for details).
- Docker image will be available soon.

## Documentation
- Full tool documentation available in the repository's `TOOLS.md` file.

## Pricing
- No pricing information provided; open source under MIT license (free to use, but requires a Solscan Pro API key which may have its own costs).

---

For more details and usage examples, see the [GitHub repository](https://github.com/wowinter13/solscan-mcp).