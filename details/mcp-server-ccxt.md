# mcp-server-ccxt

A high-performance MCP server built on the CCXT library, enabling access to real-time cryptocurrency market data and trading functions across 20+ exchanges for AI agents and language models.

## Features
- **Unified API for Multiple Exchanges:** Connects to 20+ cryptocurrency exchanges via the CCXT library through the Model Context Protocol (MCP).
- **Real-Time Market Data:** Provides real-time access to crypto market data.
- **Trading Operations:** Supports execution of trading operations (buy, sell, etc.) across supported exchanges.
- **LLM Integration:** Designed as a bridge to allow language models (LLMs) to access and interact with crypto exchanges.
- **Modular Architecture:** Organized into three main modules for maintainability and extensibility.
- **Public and Private API Tools:** Offers tools for both public (market data) and private (trading, account) API endpoints; private endpoints require exchange API keys.
- **Configuration & Utility Tools:** Includes tools for configuration and utility operations.
- **Performance Optimizations:**
  - LRU (Least Recently Used) caching system for efficient data retrieval.
  - Adaptive rate limiting to comply with exchange API limits.
  - Exchange connection management for stability and reliability.
- **Security Best Practices:**
  - Recommendations for creating dedicated API keys.
  - Guidance on limiting API key permissions.
  - Secure storage of sensitive credentials.
- **Flexible Usage:** Can be run as a standalone server or used as a module in Node.js projects.
- **Installation Options:** Available via npm, Smithery, or manual installation from source.
- **MIT Licensed:** Open source under the MIT license.

## Pricing
No pricing information provided; the project is open source and available under the MIT License.

## Source
[https://github.com/doggybee/mcp-server-ccxt](https://github.com/doggybee/mcp-server-ccxt)
