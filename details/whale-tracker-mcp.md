# whale-tracker-mcp

A Python-based Model Context Protocol (MCP) server for tracking large cryptocurrency transactions ("whale" movements) by integrating with the Whale Alert API. Designed for use with MCP-compatible clients like Claude Desktop, it enables real-time monitoring and analysis of whale activity.

**Source:** [GitHub - kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp)

## Features
- **Integration with Whale Alert API**: Tracks real-time large cryptocurrency transactions across different blockchains.
- **Tools**:
  - `get_recent_transactions`: Fetch recent whale transactions with optional filters for blockchain, minimum value, and limit.
  - `get_transaction_details`: Retrieve detailed information about a specific transaction by its ID.
- **Resources**:
  - `whale://transactions/{blockchain}`: Exposes recent transactions for a specified blockchain as contextual data.
- **Prompts**:
  - `query_whale_activity`: A reusable template for analyzing whale transaction patterns, optionally filtered by blockchain.
- **Asynchronous API Calls**: Utilizes `httpx` for efficient, non-blocking requests to the Whale Alert API.
- **Environment Variable Support**: API key management via a `.env` file for security.
- **Compatible with MCP Clients**: Integrates with clients like Claude Desktop or MCP Inspector.
- **Standalone and CLI Operation**: Can be run as a standalone server or through the MCP CLI.
- **Python 3.10+ Required**: Built in Python, with dependency management via `uv` or `pip`.

## Installation & Usage
- Clone the repository and install dependencies (`uv` or `pip`).
- Set up a Whale Alert API key in a `.env` file.
- Run the server locally, integrate with Claude Desktop, or operate via CLI.

## Licensing
- MIT License

## Pricing
- No pricing information provided; open source under the MIT License.

## Tags
`mcp`, `crypto`, `blockchain`, `tracking`, `real-time`