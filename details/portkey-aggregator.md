# Portkey Aggregator

**Category:** MCP Middleware Orchestration  
**Tags:** gateway, load-balancing, orchestration, dashboard

## Description
Portkey Aggregator (also referred to as Multi-MCP) is a unified API gateway designed to manage multiple MCP servers. It presents a single MCP server interface to clients while orchestrating multiple backend MCP servers, supporting both stdio and SSE transports. It enables scalable, flexible, and dynamic management of MCP-based tool ecosystems, particularly useful in environments like Kubernetes or containerized deployments.

## Features
- **Unified Proxy Interface:** Exposes multiple MCP servers as a single endpoint for clients.
- **Transport Support:** Connects to MCP-compatible servers regardless of transport (STDIO or SSE).
- **Auto-Discovery:** Automatically discovers tools, prompts, and resources from backend MCP servers on startup.
- **Dynamic Server Management:** Add or remove backend MCP servers at runtime via HTTP API, without system restarts.
- **Namespacing:** Supports tools with the same name on different servers using namespacing.
- **Load Balancing:** Distributes queries among multiple backend servers for optimized performance.
- **Single Port Exposure:** Simplifies deployment (especially in Kubernetes) by exposing only one port regardless of the number of backend servers.
- **Hot-Plugging:** New servers and tools can be added or removed on-the-fly and become instantly available to clients.
- **Easy Deployment:** Can be run locally, in Docker, or as a Kubernetes pod.

## Pricing
No pricing information is provided in the available content.

## Source
[Read more on ITNEXT](https://itnext.io/multi-mcp-exposing-multiple-mcp-servers-as-one-5732ebe3ba20)