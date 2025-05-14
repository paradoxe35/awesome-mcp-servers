# MCP-Framework

A framework for building Model Context Protocol (MCP) servers in TypeScript, designed for developers aiming to create production-ready or experimental MCP server implementations for AI model interactions.

- **Source:** [https://github.com/QuantGeekDev/mcp-framework](https://github.com/QuantGeekDev/mcp-framework)
- **Category:** Development Tools / MCP Servers
- **Tags:** framework, typescript, mcp, open-source

## Features

- **Automatic Discovery**: Automatically discovers and loads tools, resources, and prompts via directory-based structure.
- **Multiple Transport Support**: Built-in support for `stdio` (default) and Server-Sent Events (SSE) transports.
- **TypeScript-first**: Type safety and TypeScript support throughout the framework.
- **Based on Official MCP SDK**: Leverages the official MCP SDK for reliability.
- **Base Classes**: Easy-to-use base classes for defining tools, prompts, and resources.
- **Authentication**: Out-of-the-box authentication for SSE endpoints, supporting JWT, API Key, and custom authentication providers.
- **Flexible CORS Configuration**: Fully configurable CORS support for SSE endpoints, suitable for both development and production use.
- **CLI Tools**: Powerful CLI for project management, including project creation, adding tools, prompts, and resources.
- **Quick Development Workflow**: Simple commands to scaffold, build, and run MCP servers.
- **Integration with Claude Desktop**: Supports configuration for local development and publishing with Claude Desktop.
- **Hot Reloading**: Tools are automatically loaded on server startup after building.
- **MIT Licensed**: Open-source under the MIT license.

## Example CLI Commands

- Create a new MCP server project: `mcp create my-mcp-server`
- Add a tool: `mcp add tool price-fetcher`
- Add a prompt: `mcp add prompt price-analysis`
- Add a resource: `mcp add resource market-data`

## Transport & Authentication

- **Transports**: stdio (default), SSE (configurable port, endpoint, CORS, etc.)
- **Authentication**: JWT, API Key, or custom providers for SSE endpoints

## Pricing

- **Open Source**: Free to use under the MIT license.

## License

MIT

## Links
- [GitHub Repository](https://github.com/QuantGeekDev/mcp-framework)
- [Documentation](https://github.com/QuantGeekDev/mcp-framework#readme)
