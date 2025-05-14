# Agent

[Source Code](https://github.com/1mcp-app/agent)

## Overview
Agent (1MCP - One MCP Server for All) is a unified Model Context Protocol (MCP) server implementation that aggregates multiple MCP servers into a single interface. This simplifies configuration and management for users working with AI assistants that require MCP servers, such as Claude Desktop, Cherry Studio, Cursor, Roo Code, and others.

## Features
- **Aggregation of Multiple MCP Servers:** Combines several MCP servers into a unified server, reducing the need to manage each server separately.
- **Unified Interface:** Provides a single endpoint for clients to access various MCP servers.
- **Dynamic Configuration Management:** Supports configuration via environment variables and a global configuration file.
- **Tag-Based Filtering:** Allows labeling of MCP servers with tags, enabling fine-grained control over which servers are available to different clients.
- **Dynamic Reloading:** Configuration can be updated and reloaded without restarting the server.
- **Resource Optimization:** Reduces system resource usage by consolidating servers.
- **Docker Support:** Can be deployed using Docker with multiple image tags available.
- **Command-line and Programmatic Usage:** Can be run directly via npx or as a standalone server.
- **Debugging Tools:** Includes an MCP Inspector for debugging and inspecting server behavior.

## Category
mcp-middleware-orchestration

## Tags
mcp, middleware, orchestration, multi-instance

## Pricing
No pricing information is provided; the project appears to be open source.