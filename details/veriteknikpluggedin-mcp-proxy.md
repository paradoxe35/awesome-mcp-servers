# VeriTeknik/pluggedin-mcp-proxy

[GitHub Repository](https://github.com/VeriTeknik/pluggedin-mcp-proxy)

## Overview

**pluggedin-mcp-proxy** is a middleware proxy server that aggregates multiple Model Context Protocol (MCP) servers into a single unified interface. It enables discovery, management, and debugging of multiple MCP servers, making it easier to integrate with any MCP client (such as Claude, Cline, Cursor, etc.) and manage complex AI toolchains.

## Features

- **Universal MCP Compatibility**: Works with any MCP client, including Claude Desktop, Cline, and Cursor.
- **Multi-Server Support**: Can connect to both STDIO (command-line) and WebSocket (HTTP-based) MCP servers.
- **Namespace Isolation**: Keeps joined MCPs organized and separated using proper prefixing.
- **Multi-Workspace Layer**: Switch between different sets of MCP configurations easily.
- **Simplified Architecture**: Streamlined codebase for faster startup and reduced complexity.
- **API-Driven Proxy**: Fetches capabilities (tools, resources, templates, prompts) from plugged.in App APIs rather than direct discovery.
- **Full MCP Support**: Handles tools, resources, resource templates, and prompts.
- **Custom Instructions**: Supports server-specific instructions formatted as MCP prompts.
- **Centralized Discovery**: Centralized capability discovery for tools, resources, templates, and prompts.
- **Integration with plugged.in App**: Web-based management, multi-workspace support, custom instructions, and an interactive playground for testing MCP tools.
- **Docker Support**: Can be built and run via Docker for containerized deployments.
- **Flexible Configuration**: Supports configuration via environment variables and command-line arguments.
- **Testing Tools**: Can be tested using MCP Inspector for debugging.
- **User Authentication & API Key Management**: Requires API key from plugged.in App for secure access.

## Configuration Options

- **Environment Variables**
  - `PLUGGEDIN_API_KEY` (required): API key from plugged.in App
  - `PLUGGEDIN_API_BASE_URL` (optional): Base URL for plugged.in App (default: `https://plugged.in`)
- **Command Line Arguments**: Command-line arguments override environment variables (e.g., `--pluggedin-api-key`, `--pluggedin-api-base-url`)

## System Architecture

The proxy acts as a bridge between MCP clients and multiple underlying MCP servers, routing requests and resolving capabilities through the plugged.in App API.

## Integration

- Works seamlessly with the plugged.in App for managing MCP server configurations, capability discovery, custom instructions, and multi-workspace support.
- Includes support for Docker deployment and integration/testing with MCP Inspector.

## License

- Apache-2.0 License

## Pricing

No pricing information is provided in the content. The project appears to be open source.

## Tags

`proxy`, `orchestration`, `discovery`, `debugging`