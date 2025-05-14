# codex-mcp

Codex MCP is a Model Context Protocol (MCP) server that integrates with the Codex API to provide real-time, enriched blockchain and market data across 60+ networks. It is suitable for use with AI agents and MCP-compatible clients such as Claude Desktop and Claude CLI.

## Features
- Provides enriched blockchain and market data via the Codex API
- Supports more than 60 blockchain networks
- Real-time data delivery
- Compatible with any MCP-compatible client (e.g., Claude Desktop, Claude CLI)
- Can be run directly using npx (no installation required)
- Option for local installation and development with auto-reload
- Easy integration into developer environments (e.g., via CLI or embedding in tools)
- Requires Codex API key for operation
- Open-source (ISC License)
- Written in TypeScript

## Installation & Usage
- Clone the repository and install dependencies with `pnpm install`
- Build the project using `pnpm build`
- Alternatively, run directly with `npx @codex-data/codex-mcp`
- Can be started in stdio mode for CLI tool embedding
- Integration instructions available for Claude Desktop and Claude CLI

## Integration
- Works as an MCP server for Claude Desktop (via Developer tab and config)
- Can be added to Claude CLI as an MCP server
- Requires setting the `CODEX_API_KEY` environment variable

## License
ISC License

## Source
[https://github.com/Codex-Data/codex-mcp](https://github.com/Codex-Data/codex-mcp)

## Pricing
No pricing information available; the project is open-source under the ISC license.