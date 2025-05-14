# mcp-server-perplexity

**Category:** AI Integration MCP Servers  
**Tags:** mcp, perplexity, ai-integration, llm  
**Source:** [GitHub - tanigami/mcp-server-perplexity](https://github.com/tanigami/mcp-server-perplexity)

## Description
mcp-server-perplexity is an MCP server that enables interaction with the Perplexity API. It is designed to provide AI assistants, such as Claude Desktop, with access to Perplexity's capabilities through the MCP protocol.

## Features
- Provides an MCP server interface for the Perplexity API
- Main tool: `ask_perplexity` for requesting chat completions with citations from Perplexity
- Integrates with AI assistants (e.g., Claude Desktop)
- Supports configuration via environment variable (`PERPLEXITY_API_KEY`)
- Example configuration provided for both macOS and Windows
- Open source (MIT license)
- Written in Python

### Limitations
- The Claude Desktop client may timeout if Perplexity processing takes too long
- Long running operation support and progress reporting are dependent on future updates to Claude Desktop

## Pricing
No pricing information is provided. The project is open source under the MIT license.
