# ws-mcp

**ws-mcp** is a wrapper that exposes MCP (Model Context Protocol) servers over WebSockets, enabling integration with websocket-based clients.

## Features
- **Wraps MCP stdio servers with WebSocket**: Allows MCP servers to be accessed via WebSocket, useful for websocket-based clients such as kibitz.
- **Configurable server management**: Servers to be wrapped and exposed can be configured via a JSON config file.
- **Supports multiple servers**: Ability to run and expose multiple MCP servers at once, each as a WebSocket endpoint.
- **Custom command support**: Servers can be launched using custom commands, allowing flexibility in server selection and startup.
- **Environment variable support**: Supports passing environment variables directly or via `.env` files for server configuration (e.g., API keys).
- **Flexible port configuration**: Allows specification of the listening port for the WebSocket server.
- **Cross-platform**: Provides detailed instructions for both macOS and Linux environments.
- **Sample configuration**: Includes a sample config file to help users get started quickly.
- **Integration with existing MCP servers**: Out-of-the-box support for servers like `wcgw` (system operations, file management), `fetch` (HTTP requests), and other MCP-compatible servers (such as Brave search).

## Pricing
No pricing information is provided. ws-mcp is an open-source project available on GitHub.

## Source
[https://github.com/nick1udwig/ws-mcp](https://github.com/nick1udwig/ws-mcp)