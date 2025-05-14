# sergehuber/inoyu-mcp-unomi-server

**Description:**

An MCP (Model Context Protocol) server for accessing and updating profiles on Apache Unomi CDP, demonstrating customer data platform capabilities through MCP servers. Enables integration with Claude to maintain user context and manage user profiles via Apache Unomi.

**Source:** [GitHub Repository](https://github.com/sergehuber/inoyu-mcp-unomi-server)

**Category:** business-commerce-mcp-servers

**Tags:** mcp, cdp, unomi, customer-data

---

## Features

- **Profile Access:** Retrieve and update user profiles stored in Apache Unomi.
- **Scope Management:**
  - Automatic management and creation of scopes for user profiles.
  - Support for default and custom scopes.
  - Manual creation of scopes possible with custom names and descriptions via the `create_scope` tool.
- **User Recognition:**
  - Supports identification of users via email lookup (if `UNOMI_EMAIL` is set).
  - Fallback to a default profile ID if email is not set.
  - The response indicates the source used for profile resolution.
- **Context Management:** Enables Claude to maintain context about users through Unomi's profile system.
- **Integration Features:**
  - Designed for integration with Claude Desktop (via configuration in `claude_desktop_config.json`).
  - Communicates over stdio as per MCP requirements.
- **Configuration:**
  - Requires environment variables for Unomi server details and authentication.
  - Unomi server must have protected events and CORS properly configured.
  - Unomi key must match between server and client configuration.
- **Session ID Generation:** Automatically generates session IDs based on profile ID and the current date.
- **Debugging Tools:**
  - MCP Inspector available for browser-based debugging.
  - Logging supported via Claude Desktop and Unomi server logs.
- **Troubleshooting:**
  - Guidance provided for common issues such as protected events failing, profile not found, session issues, and connection problems.
- **Development:**
  - Standard Node.js project structure.
  - Support for dependency installation, building, and auto-rebuild for development.

**Note:**
- This is an early implementation intended for demonstration purposes.
- Other Unomi features (events, segments, session properties, etc.) are not implemented yet.

---

## Pricing

No pricing information is provided; the repository is open source.

---