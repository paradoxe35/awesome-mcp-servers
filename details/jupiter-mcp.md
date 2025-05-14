# jupiter-mcp

An MCP server for executing token swaps on the Solana blockchain using Jupiter's Ultra API, designed to empower AI agent trading strategies.

- **Source:** [GitHub Repository](https://github.com/kukapay/jupiter-mcp)
- **Category:** blockchain-crypto-mcp-servers
- **Tags:** mcp, solana, blockchain, trading, ai-agent

---

## Features

- **Jupiter Ultra API Integration:** Fetches swap orders from Jupiter's Ultra API, combining DEX routing and RFQ (Request for Quote) to find optimal pricing.
- **Swap Execution:** Executes token swaps on the Solana blockchain via the Ultra API, handling slippage, priority fees, and transaction landing.
- **Tools Provided:**
  - `get-ultra-order`: Fetches swap orders with specified input/output mints, amount, and slippage tolerance.
  - `execute-ultra-order`: Executes swap transactions on behalf of the wallet owner, based on returned order data.
- **JSON-Based Interaction:** Interactions are handled via JSON requests/responses for easy integration.
- **Node.js Compatibility:** Requires Node.js version 18 or higher.
- **Solana Wallet Support:** Requires a Solana wallet private key (base58-encoded) to sign transactions.
- **Custom RPC Configuration:** Allows specifying a custom Solana RPC endpoint.
- **Open Source:** Licensed under MIT License.

## Example Usage

### Fetching a Swap Order
- **Input:** Specify input token, output token, amount, and slippage.
- **Output:** Returns a JSON object with request ID, base64-encoded transaction, pricing info, and amounts.

### Executing a Swap
- **Input:** Provide request ID and transaction data from the previous step.
- **Output:** Returns status, transaction ID, slot, actual amounts, and swap events.

## Installation
- Clone the repository and install dependencies via npm.
- Configure client with environment variables for Solana RPC URL and private key.

## Pricing
No pricing information is provided; the software is open source under the MIT License.

## License
MIT License.
