# contentful-mcp

**Source:** [GitHub Repository](https://github.com/ivo-toby/contentful-mcp)

## Description
contentful-mcp is an MCP (Model Context Protocol) server implementation for the Contentful Management API. It provides comprehensive content management capabilities for Contentful Spaces, allowing automated updates, creation, and deletion of content, content models, and assets.

## Features
- **Entry Management:** Tools for managing entries within Contentful Spaces.
- **Asset Management:** Tools for managing assets (media, files, etc.) in Contentful.
- **Content Type Management:** Tools to manage content types/models.
- **Space & Environment Management:** Manage different spaces and environments, with options for scoping operations to specific space or environment IDs.
- **Bulk Operations:** Efficiently handle bulk actions like content migrations, mass updates, or batch publishing. Bulk operations can be performed on multiple content items simultaneously.
- **Pagination:** List operations (such as `search_entries` and `list_assets`) are paginated and limited to 3 items per request to support LLM context window limits. Each response includes pagination details.
- **Development Tools:**
  - **MCP Inspector:** A development/debugging tool to inspect MCP server operations.
  - **Hot Reload:** `npm run dev` rebuilds and reloads the server on every code change.
- **Authentication:**
  - Supports both Management Token and App Identity authentication. App Identity allows temporary AppTokens for backend and agent-based operations.
- **Configuration:**
  - Flexible configuration via environment variables or command-line arguments.
  - Experimental support for scoping space and environment IDs to restrict operations.
- **Error Handling:** Comprehensive error handling implemented for robust operation.

## Integration
- Can be used with Claude Desktop and configured via `claude_desktop_config.json`.
- Can be installed automatically via Smithery.
- Suitable for use by agents that consume MCP resources (such as chat-agents).

## License
MIT License

## Pricing
No pricing information provided; the project is open source.