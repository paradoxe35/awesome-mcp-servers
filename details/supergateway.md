# Supergateway

A service to run MCP stdio servers over Server-Sent Events (SSE), enabling scalable and real-time connectivity between clients and MCP servers.

- **Category:** mcp-middleware-orchestration
- **Tags:** gateway, stdio, sse, real-time
- **Source:** [Supergateway on MCP.so](https://mcp.so/server/supergateway/supercorp-ai)

## Overview
Supergateway is a tool designed to run MCP stdio-based servers over Server-Sent Events (SSE), enabling remote access and debugging. It allows seamless communication between MCP servers and SSE-based clients, improving connectivity and interoperability.

## Features
- Simple installation and execution via `npx` (no local install needed)
- Creates an SSE endpoint for MCP stdio servers
- Supports remote access and debugging of MCP servers
- Integrates with tools like MCP Inspector and ngrok for external/public connectivity
- Compatible with any MCP server that communicates over stdio
- Enables sharing of local MCP servers over the internet (with ngrok)
- Can be configured for production use (with security considerations)

## How It Works
- Run Supergateway via a command such as: `npx -y supergateway --stdio "uvx mcp-server-git"`, which starts the MCP server and opens an SSE endpoint for client connections.

## Use Cases
- Connecting remote clients to MCP servers that operate over stdio
- Debugging MCP servers using SSE protocols
- Sharing local MCP servers publicly over the internet (e.g., for collaboration or remote debugging)

## Pricing
No pricing information is provided.
