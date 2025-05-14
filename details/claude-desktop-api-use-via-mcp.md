# Claude Desktop API Use via MCP

- **Category:** AI Integration MCP Servers
- **Source:** [GitHub Repository](https://github.com/mlobo2012/Claude_Desktop_API_USE_VIA_MCP)
- **Tags:** mcp, ai-integration, claude, context-management, open-source

## Description
Claude Desktop API Use via MCP is an open-source server implementation that enables Claude Desktop users to integrate directly with the Claude API. It allows users to bypass Professional Plan limitations, access advanced features such as custom system prompts and conversation management, and manage longer context windows. The server can be configured easily with Claude Desktop and supports seamless switching between Professional Plan and API usage.

## Features
- **Direct Claude API Integration via MCP:** Enables Claude Desktop to connect directly to the Claude API.
- **Conversation History Tracking and Management:** Start, continue, retrieve history, and clear conversations with specific commands.
- **System Prompt Support:** Allows custom system prompts to be used in API calls.
- **Seamless Switching:** Switch between Professional Plan and API usage as needed.
- **Easy Configuration:** Setup instructions for both macOS and Windows, including environment configuration.
- **Advanced Conversation Management:** Start and manage multiple conversation threads, debug flows, and use longer context windows.
- **Custom Tooling:** Extendable with custom tools via Python decorators.
- **Cost Management:** Uses Anthropic API credits only when API-specific features are required.
- **Open Source:** Licensed under MIT, with active development and community contributions encouraged.
- **Troubleshooting Guides:** Documentation for API key, connection, and usage issues.

## Usage Examples
- Use `@claude-api` command in Claude Desktop to trigger API usage.
- Use system prompts: `@claude-api {"system_prompt": "You are an expert fitness coach"} ...`
- Manage conversation threads: start, continue, get history, and clear conversations with specific commands.

## Pricing
- **Free and Open Source** (MIT License)
- API usage may incur charges from Anthropic based on API usage/credits.

## Development
- Main server in Python (`src/claude_api_server.py`)
- Support for adding custom tools via decorators

## License
- MIT License
