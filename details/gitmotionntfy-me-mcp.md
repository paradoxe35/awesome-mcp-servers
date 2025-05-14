# gitmotion/ntfy-me-mcp

An ntfy MCP server for sending and fetching ntfy notifications from self-hosted servers, designed for AI agents. It highlights extensible MCP server implementations and supports both public and private ntfy servers with secure token authentication.

## Features
- **Send Notifications via ntfy:** Enables AI assistants to send real-time notifications to devices using public or self-hosted ntfy servers.
- **Secure Token Authentication:** Supports authenticated and unauthenticated ntfy endpoints, with options for secure token handling.
- **Multiple Deployment Methods:** Can be run via npx, Docker, global/local npm installation, or integrated with MCP-compatible assistants and tools (like VS Code and Smithery).
- **Automatic URL Detection:** Detects URLs in notification messages and automatically creates up to 3 clickable action buttons (ntfy's maximum).
- **Intelligent Markdown Detection:** Automatically enables markdown formatting when markdown patterns are detected in messages; can also be manually controlled.
- **Emoji Shortcode Support:** Allows use of emoji shortcodes in notification tags for visual indicators.
- **Configurable via Environment Variables:** Supports configuration via a `.env` file, including support for protected topics and token prompts.
- **Flexible Notification Parameters:**
  - `taskTitle`: Notification title (required)
  - `taskSummary`: Notification body (required)
  - `priority`: Message priority (min, low, default, high, max)
  - `tags`: Array of tags (with emoji support)
  - `markdown`: Enable/disable markdown formatting
  - `actions`: Array of view action objects for clickable links
- **Manual and Automatic Action Links:** Supports both automatic detection of URLs for action links and manual specification of action parameters.
- **Fetching and Filtering Messages:**
  - Retrieve messages by topic, time, message ID, text, title, priority, or tags
  - Returns full message details (subject to ntfy server cache policies)
- **Development Friendly:**
  - Can be built from source for customization
  - Contributions are welcome via pull requests

## Pricing
No pricing information is provided. The project is open-source and licensed under the GNU General Public License v3.0.

## Source
[https://github.com/gitmotion/ntfy-me-mcp](https://github.com/gitmotion/ntfy-me-mcp)

## Category
messaging-mcp-servers

## Tags
mcp, ntfy, notifications, ai-agent