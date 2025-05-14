# mcp-teams-server

**Category:** Messaging MCP Servers  
**Tags:** mcp, messaging, microsoft-365, teams

## Description
mcp-teams-server is an open-source MCP (Model Context Protocol) server implementation for integrating with Microsoft Teams. It provides capabilities for reading, posting, mentioning users, and listing threads in Teams channels.

**Source:** [GitHub - InditexTech/mcp-teams-server](https://github.com/InditexTech/mcp-teams-server)

## Features
- **Read Messages:** Retrieve messages from Microsoft Teams channels.
- **Create Messages:** Post new messages in Teams channels, including starting threads.
- **Reply to Messages:** Add replies to existing threads.
- **Mentions:** Mention users in messages and replies.
- **List Channel Team Members:** Get a list of members in a Teams channel.
- **Read Thread Replies:** Retrieve replies in a specific thread.
- **List Channel Messages:** List all messages in a channel.
- **Start Threads:** Initiate new threads in channels with a title and content, optionally mentioning users.
- **Update Threads:** Add message replies and mentions to existing threads.
- **Docker Support:** Pre-built Docker image available for quick deployment.
- **Environment Configuration:** Supports configuration via environment variables or .env files.
- **Integration with LLMs:** Can be set up for use with language models (LLM) as per documentation.

## Prerequisites
- Python 3.10
- `uv` package manager
- Microsoft Teams account and Azure resources setup

## Installation & Usage
- Clone the repository and install Python dependencies using `uv`.
- Configure required environment variables (such as Teams App ID, password, tenant ID, etc.).
- Run the server with `uv run mcp-teams-server` or use the Docker image.
- See README and documentation for full setup details.

## License
Apache-2.0

## Pricing
This project is open-source and available under the Apache-2.0 license. No pricing or paid plans are required.