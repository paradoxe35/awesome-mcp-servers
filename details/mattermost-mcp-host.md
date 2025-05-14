# mattermost-mcp-host

A Mattermost integration that connects to Model Context Protocol (MCP) servers, using a LangGraph-based AI agent to provide intelligent interaction and tool execution within Mattermost channels.

**Source:** [GitHub - jagan-shanmugam/mattermost-mcp-host](https://github.com/jagan-shanmugam/mattermost-mcp-host)

## Features

- **LangGraph Agent Integration**: Utilizes a LangGraph agent to interpret user requests and orchestrate responses.
- **MCP Server Integration**: Connects to multiple MCP servers as defined in a configuration file.
- **Dynamic Tool Loading**: Automatically discovers and loads tools from connected MCP servers, making them accessible as structured tools for the AI agent.
- **Thread-Aware Conversations**: Maintains context within Mattermost threads for coherent, contextual interactions.
- **Intelligent Tool Use**: The AI agent can determine when and how to use available tools (including chaining multiple tool calls) to fulfill user requests.
- **MCP Capability Discovery**: Users can list available servers, tools, resources, and prompts through direct commands.
- **Direct Command Interface**: Interact with MCP servers using a command prefix (default: `#`).
- **Configurable LLM Backend**: Supports multiple AI providers (Azure OpenAI by default, OpenAI, Anthropic Claude, Google Gemini) via environment variables.
- **Direct Chat & Commands**: Chat naturally in the channel or use direct commands for specific actions (help, list servers, list/call tools, list resources, list prompts).
- **Demo Scenarios**: Includes demonstration of searching GitHub issues/PRs and creating new issues, and searching the internet with results posted to Mattermost.

## Usage
- **Direct Chat**: Converse with the bot in configured channels; the AI agent uses tools and maintains thread context.
- **Direct Commands**: Use commands like `#help`, `#servers`, `#<server_name> tools`, `#<server_name> call <tool_name> <json_arguments>`, `#<server_name> resources`, `#<server_name> prompts`.

## Setup & Requirements
- **Python 3.13.1+**
- **uv package manager**
- **Mattermost server and bot account with API token**
- **LLM API access (Azure OpenAI default, other providers optional)**
- **MCP servers configured (optional for extended features)**

See the repository README for full setup instructions, including configuration of environment variables and MCP servers.

## Category
messaging-mcp-servers

## Tags
mcp, mattermost, messaging, bot

## Pricing
Open source (MIT License). No pricing plans specified.