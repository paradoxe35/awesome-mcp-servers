# Heimdall

[Heimdall on GitHub](https://github.com/shinzo-labs/heimdall)

**Category:** MCP Middleware Orchestration

**Tags:** orchestration, server-management, mcp, configuration, agent-framework

## Description
Heimdall is a lightweight service designed to manage local MCP Servers, facilitating the orchestration and configuration of multiple MCP servers and the tools available to MCP-enabled agent clients. It allows centralized management of server configurations and the authorization of specific tools for MCP clients on a device.

## Features
- **Lightweight Service:** Minimal overhead for managing MCP servers and agent tools.
- **Easy Installation:** Installable with a single `npx` command.
- **Centralized Configuration:**
  - Manage server list via `~/.heimdall/config.json`.
  - Manage authorized tools for each server via `~/.heimdall/controls.json`.
- **Dynamic Tool Authorization:**
  - Add or update authorized tools for each server and have changes reflected automatically (for supporting clients).
  - Configuration updates available across multiple MCP clients on the same device.
- **Support for Multiple MCP Clients:**
  - Enables sharing the same authorized tools configuration across different clients (e.g., Claude Desktop, Cursor).
- **Logging:**
  - Logs for each MCP client instance and child server are stored separately in `~/.heimdall/logs`.
- **Manual Cleanup:**
  - Instructions provided for cleaning up orphaned child processes if a client exits unexpectedly.
- **Limits Handling:**
  - Awareness of client-side limits (e.g., Cursor supports up to 40 tools).

## Pricing
No pricing information available. (Heimdall is open source and available on GitHub.)
