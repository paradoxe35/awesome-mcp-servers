# defi-yields-mcp

An MCP server enabling AI agents to explore DeFi yield opportunities across multiple platforms, powered by DefiLlama.

## Features
- **Data Fetching Tool**: Provides the `get_yield_pools` tool to retrieve DeFi yield pool data from DefiLlama, with filtering options by blockchain (e.g., Ethereum, Solana) or project (e.g., Lido, Aave).
- **AI Analysis Integration**: The `analyze_yields` prompt generates tailored instructions for AI agents, enabling analysis of yield pool data with a focus on metrics such as APY, 30-day mean APY, and trend predictions.
- **Direct Server Execution**: Can be run directly as a server using `uvx defi-yields-mcp` for ease of deployment.
- **Claude Desktop Integration**: Supports installation and configuration for Claude Desktop, either automatically or manually, allowing seamless integration with AI workflows.
- **Example Outputs**: Returns structured data including pool, project, TVL (Total Value Locked), APY, 30-day mean APY, and predictions (e.g., predicted class, probability, confidence).
- **Open Source**: Released under the MIT License.

## Pricing
- No pricing information is provided; the project is open source under the MIT License.

## Links
- [Source Code on GitHub](https://github.com/kukapay/defi-yields-mcp)