# jaipandya/producthunt-mcp-server

**Description:**
An MCP server for Product Hunt, enabling interactions with posts, comments, and users. It showcases MCP server integrations for web services and is designed to connect Product Hunt's API to any LLM or agent that speaks the Model Context Protocol (MCP).

**Source:** [GitHub Repository](https://github.com/jaipandya/producthunt-mcp-server)

**Category:** api-integration-mcp-servers

**Tags:** mcp, producthunt, web, integration

---

## Features
- **Plug-and-play MCP server**: Easily integrates Product Hunt API with any MCP-compatible system such as AI assistants or chatbots.
- **Multiple Installation Methods**: Install via PyPI, from GitHub, or from source. Docker support is also available.
- **Command-line Tool**: Provides the `product-hunt-mcp` command for integration into other tools (e.g., Claude Desktop, Cursor).
- **Comprehensive API Tools**: Supports a wide range of Product Hunt API actions via MCP tools:
  - `get_post_details`: Retrieve details about a specific post.
  - `get_posts`: List posts with various filters (topic, order, count, etc.).
  - `get_comment`: Fetch information about a specific comment.
  - `get_post_comments`: Retrieve comments for a post with filters.
  - `get_collection`: Get details for a specific collection.
  - `get_collections`: List collections with filters.
  - `get_topic`: Fetch info about a topic.
  - `search_topics`: Search for topics.
  - `get_user`: Retrieve information about a user.
  - `get_viewer`: Get information about the authenticated user.
  - `check_server_status`: Check server and API authentication status.
- **Rate Limiting Awareness**: Respects Product Hunt API rate limits and notifies when limits are reached and reset.
- **Security Guidance**: Provides instructions to avoid leaking sensitive tokens.
- **Open Source**: Licensed under MIT.

## Pricing
No pricing information is provided. The project appears to be open-source and free to use under the MIT license.