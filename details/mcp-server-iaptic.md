# mcp-server-iaptic

A Model Context Protocol (MCP) server for interacting with the Iaptic API. This server enables integration with Iaptic, allowing queries and management of customer data, purchases, transactions, app revenue, and statistics—demonstrating CDP (Customer Data Platform) integration with MCP servers.

- **Source:** [GitHub Repository](https://github.com/iaptic/mcp-server-iaptic)
- **Category:** Business & Commerce > MCP Servers
- **Tags:** mcp, cdp, business, integration

---

## Features

### Customer Management
- `customer_list`: List customers
- `customer_get`: Get customer details by ID

### Purchases
- `purchase_list`: List purchases with support for:
  - Pagination: `limit` (default 100, max 1000), `offset`
  - Date filtering: `startdate`, `enddate`
  - Customer filtering: `customerId`
- `purchase_get`: Get purchase details by ID

### Transactions
- `transaction_list`: List transactions with pagination and date filtering
  - `limit`, `offset`, `startdate`, `enddate`, `purchaseId`
- `transaction_get`: Get transaction details by ID

### Statistics
- `stats_get`: Get general statistics about transactions and revenue
- `stats_app`: Get app-specific statistics

### Events
- `event_list`: List recent events with pagination and date filtering
  - `limit`, `offset`, `startdate`, `enddate`

### App Management
- `iaptic_switch_app`: Switch to a different Iaptic app (requires `appName` and `apiKey`)
- `iaptic_reset_app`: Reset to the default Iaptic app
- `iaptic_current_app`: Get information about the currently active app

### Installation & Usage
- Install via Smithery or manually with npm/npx
- Supports integration with Claude Desktop via configuration
- CLI options for API key and app name
- Development support: install dependencies, run in development mode, build for production

### Requirements
- Node.js >= 18
- An Iaptic account with API credentials

### License
- MIT License

## Pricing
No pricing information is provided; the repository is open source under the MIT license.