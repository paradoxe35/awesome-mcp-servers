# mcp-openai

A Model Context Protocol (MCP) server that enables seamless use of OpenAI's models from the Claude Desktop app, allowing integration of OpenAI capabilities into MCP workflows.

**Source:** [https://github.com/mzxrai/mcp-openai](https://github.com/mzxrai/mcp-openai)

## Features
- Direct integration with OpenAI's chat models from Claude Desktop
- Supports multiple OpenAI models:
  - gpt-4o (default)
  - gpt-4o-mini
  - o1-preview
  - o1-mini
- Simple message passing interface for sending and receiving chat messages
- Basic error handling
- Tool: `openai_chat` for sending messages to OpenAI's chat completion API
  - Arguments:
    - `messages`: Array of messages (required)
    - `model`: Model to use (optional, defaults to gpt-4o)
- Easy configuration via `claude_desktop_config.json`
- Alpha software with active development; source code and installation scripts provided
- Requires Node.js >= 18 and an OpenAI API key

## Requirements
- Node.js >= 18
- Claude Desktop app
- OpenAI API key

## Verified Platforms
- macOS
- Linux (unverified as of current release)

## License
MIT

## Pricing
No pricing information provided; project is open source under the MIT license.

## Category
ai-integration-mcp-servers

## Tags
mcp, openai, chat, ai-integration