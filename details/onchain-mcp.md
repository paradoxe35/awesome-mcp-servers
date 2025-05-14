# onchain-mcp

**Source:** [https://github.com/Bankless/onchain-mcp/](https://github.com/Bankless/onchain-mcp/)

**Category:** blockchain-crypto-mcp-servers

**Tags:** blockchain, smart-contracts, api-integration, mcp

---

## Description

Bankless Onchain MCP Server is a Model Context Protocol (MCP) server that enables structured API access to on-chain blockchain data and smart contract interactions via the Bankless API. It allows AI models and applications to query blockchain state, events, and transactions in a standardized way.

---

## Features

- **Contract Operations:**
  - **read_contract:** Read the state from smart contracts on various blockchain networks.
  - **get_proxy:** Retrieve proxy implementation contract addresses.
  - **get_abi:** Fetch the ABI (Application Binary Interface) for a contract.
  - **get_source:** Retrieve the source code for a verified contract.

- **Event Operations:**
  - **get_events:** Fetch event logs for a contract based on topics.
  - **build_event_topic:** Generate an event topic signature from event name and argument types.

- **Transaction Operations:**
  - **get_transaction_history:** Retrieve transaction history for a user address.
  - **get_transaction_info:** Get detailed information about a specific transaction.

- **Integration with AI Models:**
  - Implements the Model Context Protocol (MCP) for use as a tool provider for AI models.

- **Error Handling:**
  - Provides specific error types for different scenarios.

- **Open Source:**
  - Licensed under the MIT license.

---

## Installation & Usage

- Requires a Bankless API token (see [Bankless API documentation](https://docs.bankless.com/bankless-api/other-services/onchain-mcp)).
- Can be run directly from the command line.
- Supports integration with AI/LLM models that support MCP.

---

## Pricing

No pricing information provided; the project is open source under the MIT license.
