# freqtrade-mcp

**Description:**

freqtrade-mcp is an MCP (Multi-Channel Protocol) server that integrates with the Freqtrade cryptocurrency trading bot via its REST API. It enables seamless interaction between AI agents and the Freqtrade bot for automated cryptocurrency trading operations.

**Source:** [GitHub - kukapay/freqtrade-mcp](https://github.com/kukapay/freqtrade-mcp)

**Category:** blockchain-crypto-mcp-servers

**Tags:** crypto, trading, automation, mcp

---

## Features

- **Integration with Freqtrade:** Connects to a running Freqtrade instance via its REST API (requires Freqtrade with API enabled).
- **Automated Trading Operations:** Enables AI agents to interact with and control Freqtrade for automated trading.
- **MCP Tools Exposed:** Provides a set of tools mapped to Freqtrade API endpoints, including:
  - Fetch market data (OHLCV for pairs/timeframes)
  - Fetch bot status (open trades)
  - Fetch profit summary
  - Fetch account balance
  - Fetch performance metrics
  - Fetch whitelist/blacklist of trading pairs
  - Fetch trade history
  - Fetch bot configuration
  - Fetch trade locks
  - Place trades (buy/sell with specified amount)
  - Start/stop the bot
  - Reload bot configuration
  - Add/remove pairs to/from blacklist
  - Delete trade locks
- **Configurable:** Environment variables and configuration files allow for custom setup (API URL, credentials, etc.).
- **Open Source:** Licensed under the MIT License.
- **Python-based:** Requires Python 3.13+ and uses Python ecosystem for installation and running.

## Installation

- Clone the repository and install dependencies via pip or uv.
- Configure client and Freqtrade API access as per documentation.

## Usage

- Exposes Freqtrade API endpoints as MCP tools, usable via AI agent prompts or CLI.
- Example prompts and tool parameters are provided in the documentation.

## Pricing

- **Open Source:** Free to use under the MIT License.

---

**License:** MIT License
