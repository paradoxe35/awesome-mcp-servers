# lamemind/mcp-server-multiverse

A middleware server that enables multiple isolated instances of the same MCP servers to coexist independently with unique namespaces and configurations.

- **Source:** [GitHub Repository](https://github.com/lamemind/mcp-server-multiverse)
- **Category:** mcp-middleware-orchestration
- **Tags:** middleware, namespaces, mcp, multi-instance

## Features

- **Multiple Instance Isolation:**
  - Run multiple instances of the same MCP server type independently and simultaneously, each in its own isolated "universe".
  - Each universe maintains its own configuration, filesystem access, and function naming.
- **Automatic Server Restart:**
  - File watching capability during development allows automatic detection of changes and graceful restart of servers.
- **JSON-based Configuration System:**
  - Flexible and simple configuration using JSON files.
  - Each server instance can have its own configuration.
- **Function Hiding:**
  - Selectively hide specific functions from wrapped servers using the `hideFunctions` array to restrict access to certain server functionality.
- **Selective Server Enabling/Disabling:**
  - Use the `enabled` flag to temporarily disable specific servers in your configuration without removing them.
- **Filesystem Path Resolution:**
  - Optionally hide the root path from the client for more secure filesystem access.

## Pricing

No pricing information provided; the project is open source under the MIT License.

## License

MIT License.