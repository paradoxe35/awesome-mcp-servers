# minhyeoky/mcp-server-ledger

A Model Context Protocol (MCP) server for interacting with Ledger CLI, enabling AI assistants and Large Language Models to query and analyze financial data through a standardized interface. This server facilitates financial reporting, budget analysis, and general accounting tasks by exposing Ledger CLI functionality.

**Source:** [GitHub Repository](https://github.com/minhyeoky/mcp-server-ledger)

## Features
- **Integration with Ledger CLI**: Provides a server interface for the double-entry accounting system, Ledger CLI.
- **Standardized MCP Interface**: Allows AI assistants (e.g., Claude Desktop) to perform accounting queries and analysis.
- **Ledger CLI Command Mapping**:
  - `ledger_balance`: Shows account balances with filtering options (query pattern, date ranges, display options).
  - `ledger_register`: Displays transaction register with detailed history (query pattern, date ranges, sorting options).
  - `ledger_accounts`: Lists all accounts in the ledger file (optional query pattern).
  - `ledger_payees`: Lists all payees from transactions (optional query pattern).
  - `ledger_commodities`: Lists all commodities/currencies used (optional query pattern).
  - `ledger_print`: Prints transactions in ledger format (query pattern, date ranges).
  - `ledger_stats`: Shows statistical summaries of the ledger (optional query pattern).
  - `ledger_budget`: Provides budget analysis (query pattern, date ranges, reporting period).
  - `ledger_raw_command`: Allows running raw Ledger CLI commands (input as command arguments).
- **AI Assistant Integration**: Can be used with AI assistants like Claude Desktop for natural language queries about financial data.
- **Flexible Configuration**: Ledger file path can be set via environment variable or command-line argument.
- **Security**: Includes basic validation to prevent command injection (recommended for trusted clients only).
- **Open Source**: Licensed under the MIT License.

## Prerequisites
- Ledger CLI must be installed and available in your PATH.
- A valid Ledger file with your financial data is required.

## Installation & Usage
- Recommended installation via `uv` package manager.
- Can be integrated with Claude Desktop or used for local testing and development.

## Pricing
- **Open Source**: No cost; available under the MIT License.

## Tags
`ledger`, `personal-finance`, `reporting`, `open-source`