# hibp-server

**Category:** Security Attestation MCP Servers  
**Tags:** mcp, security, hibp, api-integration

**Source:** [https://github.com/Cyreslab-AI/hibp-mcp-server](https://github.com/Cyreslab-AI/hibp-mcp-server)

## Description

hibp-server is a Model Context Protocol (MCP) server that integrates with the Have I Been Pwned (HIBP) API. It enables AI models and agents to check whether accounts (emails) or passwords have been compromised in data breaches.

## Features

- **Integration with Have I Been Pwned API:** Allows checking if email accounts or passwords have been found in data breaches.
- **Four Main Tools:**
  - Check if an email address has been breached.
  - Check if a password has been compromised.
  - Retrieve details about specific breaches.
  - List all known breaches.
- **MCP Compatibility:** Can be configured for use with Claude Desktop and the Claude VSCode extension.
- **API Key Support:** Requires an HIBP API key (except for password checking), provided via environment variable.
- **Cross-platform Configuration:** Instructions for macOS and other platforms.

## Security Notes

- Requires an HIBP API key for most features (except password checking).
- The API key must be set as an environment variable (`HIBP_API_KEY`).

## Installation

- Clone the repository.
- Install dependencies.
- Build the server.
- Configure in your MCP settings file.

## License

MIT License

## Pricing

No pricing information provided; open source under MIT license.