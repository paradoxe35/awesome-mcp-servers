# Filesystem MCP

[Source Code](https://github.com/sylphlab/filesystem-mcp)

## Overview
Filesystem MCP is a Node.js/TypeScript-based Model Context Protocol (MCP) server that provides secure, efficient, and token-saving access to project files for AI agents (such as Cline or Claude). It implements a notes system, enabling users to create, access, and generate summaries of text notes via URIs and tools, and is designed as a concrete MCP server implementation for use in AI-driven environments.

## Features
- **Secure Filesystem Access:** Operates within a defined project root directory, confining access for security.
- **MCP Protocol Implementation:** Provides a robust set of filesystem tools via the MCP protocol for AI agents.
- **Notes System:** Allows users to create, access, and generate summaries of text notes using URIs and integrated tools.
- **Batch Operations:** Tools that accept multiple paths or operations process each item individually and return detailed status reports.
- **Detailed Error Reporting:** Returns comprehensive status and error information for each operation.
- **Token Efficiency:** Supports batch processing to reduce the number of commands and tokens used by agents.
- **Low Latency API:** Provides direct API access, reducing overhead compared to shell command alternatives.
- **Multiple Installation Methods:**
  - Use via npx or bunx for latest version without local install
  - Official Docker image for containerized deployment
  - Local build option for development
- **Easy Setup:** Designed for straightforward integration with MCP host environments (e.g., Roo/Cline, VSCode).
- **MIT Licensed:** Open source and free to use and modify.

## Installation
- **npx/bunx:** Recommended for always using the latest version
- **Docker:** Official Docker image available
- **Local Build:** For development purposes

## Comparison with Alternatives
| Feature/Aspect           | Filesystem MCP Server   | Individual Shell Commands | Custom Scripts |
|-------------------------|------------------------|--------------------------|---------------|
| Security                | High (root confined)   | Low (shell access)       | Variable      |
| Efficiency (Tokens)     | High (batching)        | Low                      | Variable      |
| Latency                 | Low (direct API)       | High                     | Variable      |
| Batch Operations        | Yes (most tools)       | No                       | Maybe         |
| Error Reporting         | Detailed (per item)    | Basic                    | Variable      |
| Setup                   | Easy (npx/Docker)      | Secure shell setup       | Custom        |

## Pricing
No pricing information is provided; the project is open source under the MIT License.

## License
MIT License