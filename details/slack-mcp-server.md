# slack-mcp-server

A Model Context Protocol (MCP) server for Slack workspaces, enabling advanced channel and messaging management without requiring Slack admin permissions or bot creation.

**Source:** [GitHub Repository](https://github.com/korotovsky/slack-mcp-server)

## Features
- **Transports:** Supports both Stdio and Server-Sent Events (SSE) transports for flexible integration.
- **Proxy Support:** Can be configured to use a proxy for outbound connections.
- **No Slack Workspace Permission Requirements:** Works without needing to create bots or request admin approval in Slack workspaces.
- **Channel and Messaging Management:**
  - **conversations_history:** Retrieve messages from channels using channel ID, with cursor-based pagination and message limits.
  - **channels_list:** List channels with filtering by type (mpim, im, public_channel, private_channel) and sorting by popularity.
- **Installation Options:**
  - Can be run via `npx` (Node.js), Docker, or docker-compose.
- **Configurable via Environment Variables and Arguments:**
  - Transport selection (`--transport`): stdio or sse
  - Authentication tokens (SLACK_MCP_XOXC_TOKEN and SLACK_MCP_XOXD_TOKEN)
  - Server port and host configuration
  - Proxy URL and custom CA certificates
  - SSE API Key for authorization
  - Option to trust all SSL certificates (for insecure setups)
- **Inspector/Debugging Tools:** Integration with @modelcontextprotocol/inspector for debugging with stdio transport, and log viewing.
- **TLS/HTTPS Support:** Guidance for exposing the server securely over the internet, including ngrok usage.
- **Open Source:** Licensed under MIT.

## Setup & Usage
- Requires extraction of Slack authentication tokens (xoxc- and xoxd-) from the browser session.
- Can be integrated with Claude Desktop and other MCP-compatible tools.
- Detailed Docker and docker-compose setup instructions available in the repository.

## Pricing
- **Free and open source** (MIT License). No paid plans.

## Tags
`mcp` `slack` `messaging` `channel-management`