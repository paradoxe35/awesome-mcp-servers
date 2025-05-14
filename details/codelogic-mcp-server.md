# codelogic-mcp-server

**Official MCP server for CodeLogic, providing access to code dependency analytics, architectural risk analysis, and impact assessment tools.**

- **Source:** [GitHub Repository](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server)
- **Category:** repository-code-analysis-mcp-servers
- **Tags:** mcp, code-analysis, analytics, integration

---

## Features

- **Software Dependency Data Integration:** Exposes CodeLogic's software dependency and impact analysis data to AI programming assistants and IDEs.
- **Two Main Tools:**
  - `codelogic-method-impact`: Fetches impact assessment for a given code method and its class via the CodeLogic API.
  - `codelogic-database-impact`: Analyzes impacts between code and database entities (columns, tables, views).
- **IDE Integrations:**
  - Visual Studio Code (with GitHub Copilot agent mode)
  - Claude Desktop
  - Windsurf IDE
  - Cursor
- **Configuration via JSON:** Easily configure server and authentication details for different IDEs.
- **Environment Variables Support:** Fully customizable via environment variables such as `CODELOGIC_SERVER_HOST`, `CODELOGIC_USERNAME`, `CODELOGIC_PASSWORD`, `CODELOGIC_WORKSPACE_NAME`, and `CODELOGIC_DEBUG_MODE`.
- **Debug Mode:** When enabled, generates additional debug files (e.g., timing logs, impact data dumps).
- **Version Pinning:** Ability to pin the MCP server to a specific version for compatibility.
- **API Version Compatibility:**
  - v0.3.1 and below: Compatible with all CodeLogic API versions
  - v0.4.0 and above: Requires CodeLogic API version 25.10.0 or later
- **Testing Support:**
  - Unit tests (mock data, no external dependencies)
  - Optional integration tests (against a real CodeLogic server)
- **Open Source:** Licensed under MPL-2.0

## Usage Instructions

- Configure your IDE (VS Code, Claude Desktop, Windsurf, or Cursor) as described in the repository docs, using the provided JSON snippets and environment variables.
- Pin the version if desired for stability.
- Use the IDE's agent mode to access impact analysis and database relationship tools.
- Add recommended AI assistant rules/instructions for best results.

## Requirements

- Python environment (primary language: Python)
- Astral UV (runtime dependency)
- Access to a CodeLogic server instance

## Pricing

- **No pricing information provided.**

## License

- MPL-2.0

---

For full documentation and updates, visit the [GitHub repository](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server).