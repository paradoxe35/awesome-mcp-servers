# Defectdojo Mcp

[GitHub Repository](https://github.com/jamiesonio/defectdojo-mcp)

## Description
Defectdojo Mcp is an experimental Model Context Protocol (MCP) server that bridges AI agents and MCP clients to DefectDojo, a widely used open-source vulnerability management system. It enables programmatic and natural language interaction with security findings, products, and engagements, simplifying security analysis and automating reporting through a lightweight middleware integration.

## Features
- **MCP Server for DefectDojo:** Implements an MCP server allowing interaction with DefectDojo's API.
- **AI-Powered Security Workflows:** Connects large language models (LLMs) to DefectDojo for enhanced security automation.
- **Natural Language Interaction:** Enables querying and managing security data using natural language interfaces.
- **Vulnerability Management:** Tools to manage key DefectDojo entities such as findings, products, and engagements.
- **Available Tools via MCP:**
  - Get findings
  - Search findings
  - Update finding status
  - Add note to finding
  - Create finding
  - List products
  - List engagements
  - Get engagement
  - Create engagement
  - Update engagement
  - Close engagement
- **Flexible Installation:** Can be run using `uvx` (recommended) or installed via `pip`.
- **Configurable:** Requires environment variables to connect to your DefectDojo instance, configurable via MCP client settings.
- **Open Source:** Licensed under the MIT License.

## Category
security-attestation-mcp-servers

## Tags
security, vulnerability, mcp, integration

## Pricing
No pricing plans are provided; the project is open source and licensed under MIT.