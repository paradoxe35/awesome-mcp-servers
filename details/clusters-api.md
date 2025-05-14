# Clusters Api

[Source](https://ubos.tech/mcp/mcp-clusters-api-server/)

## Description
Clusters Api is a Model Context Protocol (MCP) server implementation that provides endpoints for wallet-based authentication, cluster management, and name registration. It serves as a direct example of an MCP server for cluster operations.

## Features
- **Authentication Endpoints**
  - Get Message
  - Get Token
  - Validate Token
- **Cluster Management Endpoints**
  - Create Cluster
  - Get Cluster by ID
  - Get Cluster by Name
  - Get Cluster ID by Address
  - Add Wallets
  - Generate Wallet
  - Update Wallets
  - Remove Wallets
  - Verify Wallet
- **Address ↔ Name Resolution Endpoints**
  - Get Data by Address
  - Get Bulk Data by Addresses
  - Get Bulk Data by Names
- **Registration Endpoints**
  - Check Name Availability
  - Get Registration Sign Data
  - Get Transaction Status
- **Transport**
  - Uses StdioServerTransport for JSON-RPC (can be modified to use HTTP transport for easier testing)
- **Environment**
  - Requires `.env` configuration with `CLUSTERS_API_KEY`

## Category
cloud-devops-mcp-servers

## Tags
mcp, cluster-management, api, authentication

## Pricing
No pricing information is provided in the available content.