# semgrep/mcp

A Model Context Protocol (MCP) server integrating Semgrep for scanning codebases for security vulnerabilities. Designed to allow AI agents, LLMs, and IDEs to leverage Semgrep's static code analysis capabilities via a standardized API.

[Source Code](https://github.com/semgrep/mcp)

## Features
- **MCP Server Integration**: Implements the Model Context Protocol (MCP) to expose Semgrep functionality to clients such as LLMs, agents, and IDEs (e.g., Cursor, VS Code, Windsurf).
- **Code Security Scanning**: Utilizes Semgrep to perform fast, deterministic static analysis for security vulnerabilities across many programming languages.
- **5,000+ Semgrep Rules**: Leverages Semgrep's extensive rule set for comprehensive code analysis.
- **Multiple Transports**:
  - **Standard Input/Output (stdio)**: For local and CLI integrations.
  - **Server-Sent Events (SSE)**: Supports server-to-client streaming via HTTP POST for remote/streaming integrations.
- **Flexible Deployment**:
  - Available as a Python package (via pip, pipx, uv, poetry, etc.).
  - Distributed as a Docker container (from ghcr.io/semgrep/mcp).
- **IDE Integrations**:
  - Out-of-the-box support for Cursor IDE, VS Code, Windsurf, Claude Desktop, and custom clients via configuration.
- **Semgrep AppSec Platform Integration**: Can connect to Semgrep AppSec Platform via API token for enhanced features.
- **Prompts and Resources**: Provides reusable prompts and exposes data/resources to LLMs for standardized interactions.
- **Open Source**: Source code available under open license.
- **Community Driven**: Actively developed with community feedback, contributions, and feature requests encouraged.

## Usage
- **Install as Python package**: `pip install semgrep-mcp` (or via pipx, uv, poetry, etc.).
- **Run as Docker container**: `docker run ghcr.io/semgrep/mcp`
- **Supports both stdio and SSE transport modes**.
- **Configurable via environment variables and JSON config files for different IDEs and clients.**

## Pricing
- No pricing information is provided; the project is open source and free to use.

## Category
- repository-code-analysis-mcp-servers

## Tags
- mcp, semgrep, code-analysis, security