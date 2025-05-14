# cursor-installer

A Model Context Protocol (MCP) server for Cursor IDE that simplifies the installation and configuration of other MCP servers, streamlining MCP ecosystem expansion and management.

- **Source:** [GitHub Repository](https://github.com/matthewdcage/cursor-mcp-installer)
- **Category:** mcp-middleware-orchestration
- **Tags:** mcp, installer, deployment, cursor

## Features
- Installs MCP servers from npm packages
- Installs MCP servers from local directories
- Installs MCP servers from Git repositories (clones, installs dependencies, configures entry point)
- Configures MCP servers for Cursor IDE
- Adds custom MCP server configurations
- Supports installation via npm, npx, or Python's uv/uvx
- Handles special server types:
  - OpenAPI Schema servers: detects schema files and configures accordingly
  - Python-based MCP servers: detects and configures to run as Python modules, sets up environment variables
- Supports adding arguments and environment variables for MCP server configurations
- Example supported servers:
  - @modelcontextprotocol/server-fetch (Web access)
  - @modelcontextprotocol/server-filesystem (File system access)
  - @modelcontextprotocol/server-github (GitHub access)
  - mcp-openapi-schema (OpenAPI Schema Explorer)
- Provides troubleshooting for common issues (Node.js/Python not installed, path errors, permission issues)
- Open source, licensed under MIT

## Installation Methods
- **npm (recommended):** `npm install -g cursor-mcp-installer-free`
- **npx (no installation required):** Use directly with `npx cursor-mcp-installer-free`
- **uv/uvx (Python users):** Use with `uvx cursor-mcp-installer-free`
- **Direct from GitHub:** Clone, install dependencies, and build locally

## Usage
- Add the installer to your Cursor configuration file (`~/.cursor/mcp.json` or `%USERPROFILE%\.cursor\mcp.json`)
- Restart Cursor IDE to apply changes
- Use Cursor or Claude to interactively install or configure MCP servers (from npm, local, or git sources)
- Supports adding arguments, environment variables, and custom server definitions

## Prerequisites
- Node.js (for npm packages)
- Cursor IDE
- uv (optional, for Python packages)

## Pricing
- **Free and open source** (MIT License)

## License
MIT License

## Resources
- [GitHub Repository](https://github.com/matthewdcage/cursor-mcp-installer)
- Readme and documentation available in the repository