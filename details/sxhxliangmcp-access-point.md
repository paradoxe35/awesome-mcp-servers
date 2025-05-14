# sxhxliang/mcp-access-point

A lightweight protocol conversion gateway that bridges traditional HTTP services with MCP (Model Context Protocol) clients, enabling direct interaction between MCP clients and HTTP services without requiring any modifications to the server-side interface.

## Features
- **Protocol Conversion:** Bridges HTTP services and MCP clients, allowing interaction without changing server-side code.
- **Multi-Platform Support:** Works across multiple operating systems.
- **No-Code Integration:** Instantly convert web services to MCP servers with no coding required.
- **Multi-Tenancy:** Supports multiple tenants, each with independent configuration for MCP services and routing.
- **Transport Protocols:**
  - **Streamable HTTP (stateless)**
  - **SSE (Server-Sent Events)**
- **Flexible Configuration:** Uses a YAML configuration file to set up upstream services, routing rules, and multi-tenancy.
- **Docker Support:** Can be run and deployed using Docker.
- **Built on Pingora:** Uses the high-performance Pingora gateway proxy library.
- **Typical Use Case:** Acts as middleware for MCP-based AI clients to interface with legacy HTTP microservices.

## Category
mcp-middleware-orchestration

## Tags
web, integration, no-code, multi-platform

## Source
[https://github.com/sxhxliang/mcp-access-point](https://github.com/sxhxliang/mcp-access-point)

## Pricing
No pricing information is provided; the project appears to be open source.