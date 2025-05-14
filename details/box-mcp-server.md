# box-mcp-server

A Model Context Protocol (MCP) server for integrating Box cloud storage, allowing file listing, reading, and searching through the MCP API.

- **Source:** [GitHub - hmk/box-mcp-server](https://github.com/hmk/box-mcp-server)
- **Category:** File Management MCP Servers
- **Tags:** box, cloud-storage, file-access, mcp

## Features

- **Box Cloud Integration:** Connects to Box cloud storage accounts.
- **File Search:** Search for files stored in Box using MCP.
- **File Reading:** Read contents of files from Box (including PDF, Word, and others).
- **MCP Protocol Support:** Exposes Box storage as an MCP server, compatible with Model Context Protocol clients.
- **Authentication:**
  - Supports Box JWT (JSON Web Token) authentication for persistent connections (requires Box enterprise or free developer account).
  - Supports developer tokens for quick setup (tokens valid for 60 minutes).
- **Environment Configuration:**
  - Can be configured with environment variables for JWT, user ID, or developer token.
- **Development Setup:**
  - Built with Node.js and npm.
  - Comes with scripts for development, including watch mode and dotenv template.

## Usage

- Requires a Box account (enterprise or developer) and the appropriate authentication credentials (JWT or developer token).
- Can be run as an MCP server using Node.js/npm.

## Pricing

- No pricing information is provided; the project is open source under BSD-3-Clause License.

## License

- BSD-3-Clause License

## Source

- [https://github.com/hmk/box-mcp-server](https://github.com/hmk/box-mcp-server)