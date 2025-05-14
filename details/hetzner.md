# Hetzner MCP Server

- **Category:** Cloud DevOps MCP Servers
- **Source:** [GitHub Repository](https://github.com/dkruyt/mcp-hetzner)

## Description
Hetzner MCP Server is a Model Context Protocol (MCP) server designed to interact with the Hetzner Cloud API. It enables language models to manage Hetzner Cloud resources through structured MCP functions, facilitating automation and integration with cloud infrastructure.

## Features
- Manage Hetzner Cloud resources programmatically via MCP functions
- **Server Management:** Create, configure, and manage cloud servers
- **Volume Management:** Handle volumes attached to servers
- **Firewall Management:** Create and manage firewall rules
- **SSH Key Management:** Manage SSH keys for secure access
- Supports two transport modes (including SSE for compatibility with Claude Code)
- Customizable host and port settings for server deployment
- Includes a test client for verifying server functionality
- Example workflows for:
  - Basic server management
  - Volume management
  - Firewall management
  - SSH key management
  - Infrastructure planning
- Can be installed directly or as a Python package
- MIT License

## Installation
- Install directly or as a Python package
- Requires Hetzner Cloud API token (configured via `.env` file)

## Pricing
- **Open Source:** Free to use (MIT License)

## Tags
`hetzner` `cloud` `resource-management` `mcp` `automation`