# mcp-proxy

A model context protocol (MCP) proxy server to connect and interact with JetBrains IDEs, including IntelliJ, PyCharm, WebStorm, and Android Studio.

- **Source:** [GitHub Repository](https://github.com/JetBrains/mcpProxy)
- **Plugin:** [JetBrains Plugin Page](https://plugins.jetbrains.com/plugin/26071-mcp-server)
- **License:** Apache-2.0

## Features

- Proxies requests between clients and JetBrains IDEs (IntelliJ, PyCharm, WebStorm, Android Studio)
- Supports integration with external clients and tools (e.g., Claude Desktop, LibreChat, Docker containers)
- Customizable connection parameters:
  - Specify IDE port (`IDE_PORT`)
  - Specify IDE host/address (`HOST`)
  - Enable detailed logging (`LOG_ENABLED`)
- Works with multiple IDEs on the same machine
- Easy configuration via environment variables for advanced use cases
- Supports both local and external network connections
- Troubleshooting guidance for Node.js version compatibility and platform-specific setup (e.g., macOS nvm path issues)
- Build instructions available (uses Node.js and pnpm)

## Usage Examples

- Integration with Claude Desktop by updating `claude_desktop_config.json`
- Configuration for external access (LAN IP, port, etc.)

## Requirements

- Node.js version 18 or later
- pnpm (for building from source)

## Pricing

- **Free and open source** (Apache-2.0 License)

## Tags

`mcp`, `jetbrains`, `ide`, `proxy`, `integration`
