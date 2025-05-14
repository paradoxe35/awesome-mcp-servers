# MCP Gateway

A gateway service that bridges the stdio-based Model Context Protocol (MCP) implementation in Claude Desktop with HTTP/SSE-based MCP servers.

## Features
- Acts as a protocol translator between stdio-based MCP clients (such as Claude Desktop) and HTTP/SSE-based MCP servers.
- Enables Claude Desktop to communicate with MCP servers that use Server-Sent Events (SSE) over HTTP.
- Configurable connection to different MCP servers via environment variable.
- Defaults to connecting with the MCP Hub server at https://server.mcphub.ai/api/mcp.
- Installation via npm and global usage support.
- Configuration instructions for both macOS and Windows environments.
- Open source, released under the Apache 2.0 License.

## Pricing
- The MCP Gateway is open source and free to use.

## Source
[https://github.com/lightconetech/mcp-gateway](https://github.com/lightconetech/mcp-gateway)

## Tags
`gateway` `sse` `middleware` `integration`