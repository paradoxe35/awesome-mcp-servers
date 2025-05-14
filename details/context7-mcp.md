# Context7 MCP

Connects to Context7.com's documentation database as an MCP server, providing intelligent access to library and framework documentation for developers and AI assistants.

- **Source:** [GitHub Repository](https://github.com/upstash/context7-mcp)
- **Category:** Documentation & Learning Resources

## Features

- Provides up-to-date, version-specific documentation and code examples for libraries and frameworks.
- Integrates with LLMs and AI code editors (e.g., Cursor, Windsurf, Claude Desktop, VSCode, Claude Code).
- Fetches documentation and code examples directly into the prompt context for LLMs, reducing outdated or hallucinated code.
- Supports various installation methods (Smithery, npx, bunx, deno) for different clients and environments.
- Two main tools via MCP protocol:
  - `resolve-library-id`: Resolves a general library name into a Context7-compatible library ID, with optional reranking.
  - `get-library-docs`: Fetches documentation for a library using its ID, with optional topic focus and adjustable token limit.
- Configuration examples provided for multiple editors (Cursor, Windsurf, VSCode, Claude Desktop).
- Open-source under the MIT License.
- Supports local development, building, and testing via bun and MCP Inspector.
- Handles module resolution issues with recommended workarounds (e.g., using bunx).

## Pricing

Context7 MCP is open-source and available under the MIT License. No pricing information or paid plans are mentioned.

## Tags

mcp, documentation, ai-assistant, integration