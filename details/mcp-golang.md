# mcp-golang

[mcp-golang](https://github.com/metoro-io/mcp-golang) is an open-source, type-safe Golang framework for building Model Context Protocol (MCP) servers and clients with comprehensive protocol implementation and validation.

## Features

- **Type Safety**: Define tool arguments as native Go structs. The framework handles schema generation, deserialization, and error handling automatically.
- **Low Boilerplate**: Generates all MCP endpoints for tools, prompts, and resources, minimizing the amount of code required to set up a server or client.
- **Custom Transports**:
  - Built-in support for stdio (full feature support, including bidirectional communication and notifications)
  - HTTP (stateless communication; does not support bidirectional features)
  - Gin HTTP transport for integration with the Gin framework
  - Experimental custom transport and HTTPS with custom authentication support (in progress)
- **Modular Design**: The library is split into three components (transport, protocol, server/client). Use all or just the ones you need.
- **Bi-directional Support**: Full support for both server and client implementations using stdio transport.
- **Automatic Endpoint Generation**: Programmatically generates endpoints for tools, prompts, and resources.
- **Notifications & Pagination**: Planned support for change notifications and pagination for tools, prompts, and resources.
- **Client Features**:
  - Call tools, prompts, and resources
  - List tools, prompts, and resources
- **Extensive Examples**: Provides examples for server and client implementations, including HTTP, Gin, and stdio transports.
- **Integration**: Example integration with Claude Desktop.
- **Open Source**: Licensed under MIT, with contributions welcome.

## Usage Examples

- **Server Setup**: Minimal code required to register tools, prompts, and resources.
- **HTTP/Gin Support**: Easily create stateless MCP servers using HTTP or Gin framework.
- **Client Usage**: Call tools and process responses using type-safe arguments.

## Pricing

mcp-golang is open source and released under the MIT license. There are no associated costs.

## Links

- [Source Code & Documentation](https://github.com/metoro-io/mcp-golang)
- [Project Website & Docs](https://mcpgolang.com)

## Tags

golang, framework, mcp, open-source