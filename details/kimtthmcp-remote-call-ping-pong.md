# kimtth/mcp-remote-call-ping-pong

An experimental and educational MCP server app for demonstrating remote MCP calls using a Ping-Pong server.

## Features
- **FastAPI/FastMCP backend:** Provides a backend for remote MCP (Model Context Protocol) calls via API endpoints and Server-Sent Events (SSE).
- **MCP Integration:** Supports command handling for the Ping-Pong demo (commands: `ping`, `pong`, `count`).
- **Thread-safe session management:** Ensures safe handling of concurrent sessions.
- **API Endpoints:**
  - `GET /ping-pong?prompt_name=<prompt_name>`: Retrieve a specific prompt.
  - `POST /ping-pong`: Invoke MCP tool commands (`ping`, `pong`, `count`).
- **SSE Communication:**
  - Example scripts provided for both SSE server and client for real-time command exchange.
- **Sample UI:**
  - `mcp-api-client.html` can be used in a browser to interact with the server.
- **Educational Examples:**
  - Includes code samples and references for using FastAPI, SSE, and MCP together.

## References
- FastAPI SSE MCP
- MCP Weather SSE
- MCP Chinese Getting Started Guide

## License
MIT

## Source
[https://github.com/kimtth/mcp-remote-call-ping-pong](https://github.com/kimtth/mcp-remote-call-ping-pong)

## Tags
mcp, reference-implementation, examples, educational

## Category
reference-implementations-examples

## Pricing
This is an open source project licensed under MIT; there is no pricing.