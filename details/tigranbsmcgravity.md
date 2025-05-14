# tigranbs/mcgravity

[GitHub Repository](https://github.com/tigranbs/mcgravity)

## Description
McGravity is a proxy tool designed to compose and load balance across multiple MCP (Model Context Protocol) servers, providing a unified endpoint. It enables scaling of AI tools by distributing requests across multiple MCP servers, functioning similarly to how Nginx operates for web servers.

## Features
- **Unified Endpoint:** Combines multiple MCP servers into a single service endpoint.
- **Load Balancing:** Distributes requests across multiple MCP servers, aiding in scaling.
- **CLI Tool:** Currently operates as a command-line interface tool.
- **Docker Support:** Available as a Docker image (`tigranbs/mcgravity`).
- **Configurable:** Supports YAML-based configuration for flexible setup (see `config.example.yaml`).
- **Testing Suite:** Includes integration and unit tests, with CI via GitHub Actions.
- **Example Server:** Provides an echo server example for testing.
- **TypeScript-based:** Developed in TypeScript and optimized for Bun runtime.
- **Extensible:** Plans for future full-featured proxy capabilities for Gen AI tools.

## Usage
- Can be run via CLI with options or configuration file.
- Suitable for scaling and managing multiple MCP servers for AI/ML workloads.

## Category
mcp-middleware-orchestration

## Tags
proxy, load-balancing, scaling, ai-integration

## Pricing
No pricing information provided; appears to be open source.