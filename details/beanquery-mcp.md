# Beanquery MCP

Beanquery MCP is an experimental server implementation that utilizes the Model Context Protocol (MCP) to enable querying and analysis of Beancount ledger files using the Beancount Query Language (BQL) and the beanquery tool. It is designed to facilitate standardized communication between AI assistants and Beancount ledgers, making it useful for financial data tracking and report generation.

- **Source:** [https://github.com/vanto/beanquery-mcp](https://github.com/vanto/beanquery-mcp)
- **Category:** Finance Market Data MCP Servers
- **Tags:** beancount, finance, data-analysis, reporting

## Features
- Provides an MCP server interface for Beancount ledger files.
- Supports querying and analysis using Beancount Query Language (BQL).
- Integrates with the beanquery tool for data retrieval and manipulation.
- Enables AI assistants (such as Claude.ai) to interact with and analyze financial data in Beancount format.
- Designed for interoperability via the MCP standard, allowing standardized communication between clients and the server.
- Includes a sample ledger file (`sample.bean`) for testing and demonstration.
- Offers development and testing modes, including integration with tools like MCP Inspector and Claude Desktop.
- Test suite available via pytest.
- Open source under the MIT License.

## Pricing
No pricing information is provided. The project is open source and licensed under the MIT License.

## Notes
- The server is experimental and recommended for use in development environments only.
- Caution is advised regarding privacy, as the tool may transmit parts of your Beancount ledger to third-party services (e.g., LLM providers via MCP).