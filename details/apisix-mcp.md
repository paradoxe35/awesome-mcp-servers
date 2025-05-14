# apisix-mcp

**APISIX Model Context Protocol (MCP) server** for bridging large language models (LLMs) with the APISIX Admin API to query and manage Apache APISIX resources.

- **Source:** [https://github.com/api7/apisix-mcp](https://github.com/api7/apisix-mcp)
- **Category:** API Integration MCP Servers
- **Tags:** mcp, apisix, api-integration, ai-integration

---

## Features

- **Natural Language Interaction:** Enables LLMs to interact with APISIX resources using natural language via MCP-compatible AI clients.
- **Resource Management:**
  - Retrieve resources (routes, services, upstreams, etc.)
  - Delete resources by ID
  - Send requests to the APISIX gateway
- **API Resource Operations:**
  - Create, update, and delete routes, services, upstreams, and SSL certificates
  - Manage protobuf definitions
  - Manage stream routes
- **Plugin Operations:**
  - List all available plugin names
  - Retrieve plugin configuration, schema, and types
  - Create and update plugin configurations
  - Manage global plugin rules and plugin metadata
- **Security Configuration:**
  - Manage secrets (get, create, update)
  - Manage consumers (create/update, delete)
  - Manage consumer credentials (get, create/update, delete)
  - Manage consumer groups (create, delete)
- **Flexible Deployment:**
  - Install via Smithery for Claude Desktop or manually via npm/source code
- **Configurable Environment:**
  - Customizable via environment variables (server host, ports, admin API prefix, admin key)
- **TypeScript Implementation:**
  - Written primarily in TypeScript
- **Open Source:**
  - Licensed under Apache-2.0

## Installation & Configuration
- Install via [Smithery](https://smithery.sh/) or npm
- Can be configured for AI clients such as Cursor, Claude, Copilot, etc.
- Customizable with environment variables for different APISIX deployments

## Pricing
No pricing information is provided; the project is open source under the Apache-2.0 license.
