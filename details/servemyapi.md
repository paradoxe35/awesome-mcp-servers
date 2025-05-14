# servemyapi

A personal MCP server for securely storing and accessing API keys across projects using the macOS Keychain.

## Features
- **Secure Storage in macOS Keychain:** API keys are stored securely using the macOS Keychain, never visible in .env or config files, and only accessible to the current user.
- **Consistent MCP Interface:** Access and manage API keys through a consistent Model Context Protocol interface.
- **CLI Interface:** Command-line tool for storing, retrieving, listing, and deleting API keys directly from the terminal.
- **Support for stdio and HTTP/SSE Transports:** Can run as a stdio server (for tools like Claude Desktop) or as an HTTP server.
- **Cross-Project Access:** Use the same API keys across multiple projects without duplication.
- **Natural Language Integration:** When used with LLMs like Claude, allows storing and retrieving keys via natural language.
- **Compatible with Any MCP Client:** Works with clients such as Claude Desktop and Windsurf, with example configuration files provided.
- **Smithery Hosted Service:** Optionally available as a hosted service on Smithery for easier integration.
- **MCP Tools:**
  - `store-api-key`: Store an API key.
  - `get-api-key`: Retrieve an API key.
  - `delete-api-key`: Delete an API key.
  - `list-api-keys`: List all stored API keys.
- **Security:** Keys are never stored in plaintext or logged, and access to the keychain requires authentication.
- **Development Tools:** Includes scripts for development mode, linting, and building for production.

## Roadmap
- Code scanner tool to find API endpoints, sensitive URLs, and environment variables in codebases and suggest secure storage.
- Cross-platform support (Windows, Linux) under investigation.
- Integration with popular frameworks (Next.js, Express, etc.).
- Web UI for key management.

## Installation
- Clone the repo: `git clone https://github.com/Jktfe/serveMyAPI.git`
- Install dependencies: `npm install`
- Build the project: `npm run build`

## Usage
- Install CLI globally: `npm run build && npm link`
- CLI commands:
  - List keys: `api-key list`
  - Get a key: `api-key get <name>`
  - Store a key: `api-key store <name> <key>`
  - Delete a key: `api-key delete <name>`
  - Help: `api-key help`
- Run as stdio server: `npm start`
- Run as HTTP server: `node dist/server.js`

## Compatibility
- **macOS only:** Relies on macOS Keychain, not compatible with Windows or Linux.
- Works with Claude Desktop, Windsurf, and any MCP client.

## License
MIT

## Source
[https://github.com/Jktfe/serveMyAPI](https://github.com/Jktfe/serveMyAPI)

## Pricing
- Open source, MIT licensed. No paid plans.