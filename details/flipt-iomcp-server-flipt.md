# flipt-io/mcp-server-flipt

A Model Context Protocol (MCP) server for Flipt, enabling AI assistants to interact with feature flags managed in Flipt.

- **Source:** [GitHub Repository](https://github.com/flipt-io/mcp-server-flipt)
- **Category:** Cloud DevOps MCP Servers
- **Tags:** feature-flags, devops, mcp, ai-integration

---

## Features

- List, create, update, and delete:
  - Namespaces
  - Flags
  - Segments
  - Rules
  - More related resources
- Evaluate feature flags for specific entities
- Toggle feature flags on or off
- Manage constraints, variants, distributions, and rollouts
- STDIO transport for MCP communication
- Tool and prompt registration for AI assistant interaction
- Configurable via environment variables:
  - `FLIPT_API_URL` (default: `http://localhost:8080`)
  - `FLIPT_API_KEY` (optional)
- Can be installed and run via npm, npx, or Docker
- Designed for integration with AI assistants supporting the Model Context Protocol
- Development scripts for install, dev mode, build, start, formatting, and linting

---

## Installation & Usage

- **Smithery:**
  - `npx -y @smithery/cli install @flipt-io/mcp-server-flipt --client claude`
- **Node.js:**
  - Global: `npm install -g @flipt-io/mcp-server-flipt && mcp-server-flipt`
  - Direct: `npx -y @flipt-io/mcp-server-flipt`
- **Docker:**
  - `docker run -d --name mcp-server-flipt ghcr.io/flipt-io/mcp-server-flipt:latest`

---

## License

- Apache 2.0

---

## Pricing

No pricing information provided; the project is open source under the Apache 2.0 license.