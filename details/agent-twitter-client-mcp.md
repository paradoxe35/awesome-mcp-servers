# agent-twitter-client-mcp

[Source Code](https://github.com/ryanmac/agent-twitter-client-mcp)

## Description
A Model Context Protocol (MCP) server that integrates with Twitter (X) using the `agent-twitter-client` package, enabling AI agents or models to interact with Twitter without requiring direct API access. It supports tweet operations, user interactions, and integrates with Grok for real-time Twitter data access.

## Features
- **Authentication Options:**
  - Cookie-based authentication (recommended)
  - Username/password authentication
  - Twitter API authentication
- **Tweet Operations:**
  - Post tweets (including with images or videos)
  - Create polls
- **User Operations:**
  - Standard Twitter user actions (details depend on agent-twitter-client capabilities)
- **Grok Integration:**
  - Interact with Grok for real-time Twitter data
  - Continue conversations with Grok
  - Grok features require authentication and are subject to rate limits
- **Testing Interface:**
  - Interactive command-line REPL for testing MCP functions
- **Demo Scripts:**
  - Example scripts in a demo directory to demonstrate features
- **Port Configuration:**
  - Default port 3000, configurable via environment variables or Docker Compose
- **Docker Support:**
  - Run server directly or with Docker Compose
  - Persistent logging via Docker volume mounts
- **Logging:**
  - Logs to both console and files
- **Health Check Tool:**
  - Built-in tool to diagnose server issues
- **Security Considerations:**
  - Standard security configuration and environment variable management
- **Documentation:**
  - Quick Start, installation, advanced usage, and troubleshooting guides
- **Cross-platform Configuration:**
  - Setup instructions for both Windows and macOS

## Pricing
No pricing information provided; open-source under the MIT license.

## Category
Data Access Integration MCP Servers

## Tags
mcp, twitter, social-media, ai-integration