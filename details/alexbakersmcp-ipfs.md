# alexbakers/mcp-ipfs

**Category:** File Management MCP Servers  
**Tags:** mcp, ipfs, decentralized-storage, ai-integration  
**Source:** [GitHub Repository](https://github.com/alexbakers/mcp-ipfs)

## Description
MCP IPFS Server is a Node.js server implementing the Model Context Protocol (MCP) for interacting with decentralized storage via the storacha.network platform and the w3 command-line interface. It enables AI assistants, agents, and other MCP clients to manage storage spaces, upload/download data, and handle delegations on decentralized storage.

## Features
- **Integration with storacha.network:** Native wrapping of the w3 CLI for interaction with decentralized storage.
- **Authentication & Agent Management:**
  - `w3_login`, `w3_reset`, `w3_account_ls` for authentication and authorization checks.
- **Space Management:**
  - List, use, get info, add, and provision storage spaces (`w3_space_ls`, `w3_space_use`, `w3_space_info`, `w3_space_add`, `w3_space_provision`).
  - Note: `w3_space_create` must be run manually due to interactive prompts.
- **Data Management:**
  - Upload, list, and remove files (`w3_up`, `w3_ls`, `w3_rm`).
- **Sharing:**
  - Generate shareable URLs via `w3_open` (produces w3s.link URLs).
- **Delegations & Proofs:**
  - Create, list, revoke delegations (`w3_delegation_create`, `w3_delegation_ls`, `w3_delegation_revoke`).
  - Add and list proofs (`w3_proof_add`, `w3_proof_ls`).
- **Keys & Tokens:**
  - Create keys and generate bridge tokens (`w3_key_create`, `w3_bridge_generate_tokens`).
- **Advanced Storage Tools:**
  - Blob, CAR, Upload, Index, Access Claim, Filecoin info management.
- **Account & Billing:**
  - Get plan information, create coupons, and generate usage reports (`w3_plan_get`, `w3_coupon_create`, `w3_usage_report`).
- **Usage with MCP Clients:**
  - Can be used with any MCP-compatible client, supports running via NPX or Docker.
- **Project Structure:**
  - Modular codebase with clear separation of server entry, tool logic, schemas, and utilities.
- **Prerequisites:**
  - Node.js 22.0.0+, w3 CLI installed and configured, environment variable `W3_LOGIN_EMAIL` required.
- **Docker Support:**
  - Dockerfile provided for containerized deployment.

## Licensing
- MIT License

## Pricing
No pricing or plans are specified; the project is open source under the MIT license.