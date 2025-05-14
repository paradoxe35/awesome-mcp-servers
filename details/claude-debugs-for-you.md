# claude-debugs-for-you

**Category:** Testing & Debugging Tools  
**Tags:** mcp, debugging, vscode, ai-integration

[Source code on GitHub](https://github.com/jasonjmcghee/claude-debugs-for-you)

## Description
`claude-debugs-for-you` is an MCP server and VS Code extension that enables interactive, automatic debugging for any programming language via breakpoints and expression evaluation. It allows large language models (LLMs), such as Claude, to interface with the debugging process through the Model Context Protocol (MCP), making debugging workflows accessible to AI assistants across languages.

## Features
- **Language-agnostic debugging:** Works with any programming language supported by VS Code debugging, assuming debugger console support and a valid `launch.json` configuration.
- **MCP server integration:** Exposes debugging capabilities through the Model Context Protocol, enabling LLMs to control and interact with the debugger.
- **VS Code extension:** Provides an extension for Visual Studio Code to bridge LLMs and the debugging process.
- **Breakpoints and expression evaluation:** Supports setting breakpoints and evaluating expressions programmatically via MCP.
- **LLM support:** Designed to work with any LLM (e.g., Claude, GPT-4), not just Claude, for debugging automation.
- **Multiple client compatibility:** Can be used with Claude Desktop, Continue, Cursor, or any client supporting MCP.
- **Configurable startup:** Allows for configuration via environment variables and extension settings (e.g., port selection).
- **Automatic debug server startup:** Starts the debug server automatically on VS Code initialization (can be disabled in settings).
- **Flexible transport:** Supports both node process and SSE (Server-Sent Events) based communication for different client types.
- **Demo examples and configuration guidance:** Provides detailed instructions and examples for setup with various clients.
- **Open source and extensible:** MIT licensed and open to contributions.

## Pricing
- **Free and open source** (MIT License)

## Resources
- [VS Code Marketplace Listing](https://marketplace.visualstudio.com/items?itemName=JasonMcGhee.claude-debugs-for-you)
- [GitHub Repository](https://github.com/jasonjmcghee/claude-debugs-for-you)