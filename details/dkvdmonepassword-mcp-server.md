# dkvdm/onepassword-mcp-server

**Category:** Security Attestation MCP Servers  
**Tags:** mcp, security, credentials, automation

## Description
`dkvdm/onepassword-mcp-server` is a proof-of-concept MCP (Machine Control Protocol) server that enables secure retrieval of credentials stored in 1Password, making them accessible to Agentic AI systems. The server uses the 1Password Python SDK to access credentials and exposes them via the MCP Python SDK, allowing integration with tools like Claude Desktop and automation of browser tasks.

## Features
- Securely retrieves credentials from a 1Password account using the 1Password Python SDK.
- Provides credentials to Agentic AI via the MCP Python SDK interface.
- Designed for integration with Claude Desktop and other Agentic AI clients.
- Supports configuration through Smithery for easy installation.
- Can be used in conjunction with other MCP servers, such as `mcp-browser-use`, to automate browser tasks using retrieved credentials.
- Requires a dedicated 1Password service account with appropriate vault permissions.
- Configuration flexibility via environment variables and JSON config for client integration.
- Distributed as a Python project, with Dockerfile available for containerization.
- Intended for educational and proof-of-concept use only.

## Prerequisites
- Python 3.11 or higher
- `uv` (Python package installer)
- 1Password account with an "AI" vault and service account token

## Installation
- Install via Smithery CLI:  
  `npx -y @smithery/cli install @dkvdm/onepassword-mcp-server --client claude`
- Manual setup involves installing dependencies with `uv`, configuring the service account, and setting up the server for use by an Agentic AI client.

## Usage
- Configure the MCP server settings in your AI client's configuration file (e.g., `claude_desktop_config.json`).
- Launch the AI client and use prompts to request credentials for specific services.
- Can be paired with browser automation MCP servers for end-to-end automation workflows.

## Pricing
No pricing information is provided; the project is open source and available on GitHub.

## Source
[https://github.com/dkvdm/onepassword-mcp-server](https://github.com/dkvdm/onepassword-mcp-server)