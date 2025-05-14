# Grasshopper MCP

**Connects Grasshopper design software to Claude via a bidirectional MCP server, enabling natural language control of modeling workflows. Illustrates MCP server applications in design automation.**

- **Source:** [https://github.com/alfredatnycu/grasshopper-mcp](https://github.com/alfredatnycu/grasshopper-mcp)
- **Category:** AI Integration, MCP Servers
- **Tags:** ai-integration, design, claude, workflow, mcp

## Features
- Bridges Grasshopper (a visual programming environment for Rhino) with Claude Desktop using the Model Context Protocol (MCP) standard.
- Enables natural language control of Grasshopper modeling workflows via Claude Desktop.
- Bidirectional communication between Grasshopper and Claude.
- Modular architecture:
  - Grasshopper MCP Component (GH_MCP) for Grasshopper.
  - Python MCP Bridge Server for handling communication.
- Flexible installation:
  - Pre-compiled plugin (GH_MCP.gha) for Grasshopper.
  - MCP Bridge Server installable via PyPI, GitHub, or from source.
  - Supports installation of specific versions.
- Supports both manual and auto-start connection methods for Claude Desktop.
- Example commands for using Claude Desktop to control Grasshopper.
- Troubleshooting guidance for component loading, server startup, and connection issues.
- Open source (MIT License).
- Contributions via GitHub are welcome.

## Installation
- Install the Grasshopper MCP Component (download or build from source).
- Install the Python MCP Bridge Server (via PyPI, GitHub, or source).
- Start Rhino and Grasshopper, add the MCP component.
- Run the MCP Bridge Server.
- Connect Claude Desktop to the MCP Bridge.

## Usage
- Use Claude Desktop to issue natural language commands to Grasshopper for design automation.

## Pricing
- **Open Source** (MIT License) — Free to use.
