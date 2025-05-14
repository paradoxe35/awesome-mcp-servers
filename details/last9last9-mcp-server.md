# last9/last9-mcp-server

An open-source Model Context Protocol (MCP) server by Last9 that brings real-time production context—logs, metrics, and traces—into local development environments for automated code fixes.

- **Source:** [GitHub Repository](https://github.com/last9/last9-mcp-server)
- **Category:** Monitoring
- **Tags:** monitoring, logs, metrics, real-time, observability
- **License:** Apache-2.0

---

## Features

- **Real-time Production Context**: Seamlessly integrates production logs, metrics, and traces into local development setups.
- **AI Agent Integration**: Enables AI agents to auto-fix code faster using real production data.
- **MCP Tools Implemented**:
    - `get_exceptions`: Retrieve server-side exceptions over customizable time ranges.
    - `get_service_graph`: Visualize upstream and downstream service dependencies and throughput for a given endpoint/span.
    - `get_logs`: Filter and retrieve logs by service name, severity, or time window.
    - `get_drop_rules`: View log filtering rules that prevent certain logs from reaching Last9.
    - `add_drop_rule`: Add new filtering rules for logs based on attributes, values, and operators.
- **IDE & Tool Support**:
    - Works with Claude desktop app, Cursor, Windsurf, and VSCode (with Github Copilot).
    - Provides detailed setup instructions for each supported tool.
- **Flexible Installation**:
    - Install via Homebrew or NPM.
    - Supports running as a CLI or with npx for quick usage.
- **Configurable Authentication**:
    - Requires environment variables for authentication and API access (LAST9_AUTH_TOKEN, LAST9_BASE_URL, LAST9_REFRESH_TOKEN).
- **Open Source**: Actively maintained with regular releases and community contributions.

---

## Installation

- **Homebrew**
    - `brew tap last9/tap`
    - `brew install last9-mcp`
- **NPM**
    - `npm install -g @last9/mcp-server`
    - Or run with `npx @last9/mcp-server`

---

## Configuration

- Requires environment variables for authentication:
    - `LAST9_AUTH_TOKEN`
    - `LAST9_BASE_URL`
    - `LAST9_REFRESH_TOKEN`
- Obtain credentials from the Last9 dashboard after signup and integration setup.

---

## Usage

- **Claude Desktop App, Cursor, Windsurf, VSCode**: Detailed configuration steps are provided for each tool to connect and use the MCP server.
- **VS Code**: Requires v1.99+ and setup via `.vscode/mcp.json` or user settings.

---

## Pricing

- No pricing information is provided; the project is open-source under the Apache-2.0 license.

---

## Resources

- [Official Documentation & Readme](https://github.com/last9/last9-mcp-server)
- [Last9 MCP Server Homepage](https://last9.io/mcp)

---

## Languages

- Go (85.2%)
- JavaScript (7.6%)
- Shell (7.2%)