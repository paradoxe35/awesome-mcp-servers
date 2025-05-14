# Context7

[Context7](https://github.com/upstash/context7) is a lightweight, modular MCP-compatible memory and agent protocol server focused on privacy-first, on-device AI agents. It provides up-to-date, version-specific documentation and code examples directly into AI coding assistants and LLM prompts, helping developers avoid outdated or hallucinated APIs and reducing errors in code generation.

## Features

- **MCP-Compatible Server:** Implements the Model Context Protocol (MCP), enabling seamless integration with various AI coding assistants and LLMs.
- **Privacy-First, On-Device AI:** Designed to run locally, ensuring user privacy and control over data.
- **Supports Local and Cloud LLMs:** Can be used with both local and cloud-based large language models.
- **Persistent, Session-Aware Memory:** Maintains session context and persistent memory for enhanced agent interactions.
- **Up-to-Date Documentation:** Fetches real-time, version-specific documentation and code examples from source repositories.
- **Context Injection:** Integrates documentation and examples directly into your prompt context for LLMs and coding assistants like Cursor, Windsurf, Claude Desktop, VS Code, Zed, and more.
- **No Tab Switching:** Eliminates the need to switch tabs or search for docs manually.
- **Multiple Installation Methods:** Can be installed via Node.js (npx, bun, deno), Docker, and through integrations in various editors and environments.
- **Available Tools:** Provides utilities like `resolve-library-id` (to resolve general library names) and `get-library-docs` (fetch documentation by library ID, with topic/tokens options).
- **Open Source:** Licensed under MIT, with active development and community contributions.
- **Multilingual Documentation:** Docs available in multiple languages (English, Chinese, Korean, Spanish, French, Portuguese, Italian, Indonesian, German).

## Installation & Integration

- Installable via `npx`, `bunx`, or `deno`.
- Docker support with provided Dockerfile.
- Integrates with:
    - Cursor
    - Windsurf
    - Claude Desktop
    - Claude Code
    - VS Code (and VS Code Insiders)
    - Zed
- Configuration snippets provided for each supported client/editor.

## Requirements

- Node.js >= v18.0.0 (for local installs)
- Compatible MCP client/editor (Cursor, VS Code, Windsurf, Claude Desktop, etc.)

## Development

- Clone the repo and install dependencies with `bun i`.
- Build with `bun run build`.

## License

MIT

## Links

- [GitHub Repository](https://github.com/upstash/context7)
- [Official Website](https://context7.com)

## Pricing

No pricing information is provided; Context7 is open source (MIT licensed).
