# HackMD MCP

**Category:** File Management MCP Servers  
**Tags:** mcp, hackmd, document-management, markdown  
**Source:** [github.com/yuna0x0/hackmd-mcp](https://github.com/yuna0x0/hackmd-mcp)

## Description
HackMD MCP is a Model Context Protocol (MCP) server that enables integration with the HackMD note-taking platform, allowing AI assistants and MCP clients to perform document operations (create, read, update, delete) within collaborative markdown environments.

## Features
- **User API:**
  - Get authenticated user information
- **User Notes API:**
  - List all notes owned by the user
  - Get a note by its ID
  - Create a new note
  - Update an existing note
  - Delete a note
  - View user's reading history
- **Teams API:**
  - List all teams accessible to the user
- **Team Notes API:**
  - List all notes in a team
  - Create a new note in a team
  - Update an existing note in a team
  - Delete a note in a team
- **Integration:**
  - Works with Claude Desktop and other MCP clients
  - Can be installed via Smithery CLI or mcp-get
  - Supports local development and Docker deployment
  - MCP Inspector support for testing and debugging
- **Configuration:**
  - Requires HackMD API token and optionally a custom API endpoint
  - Environment variable configuration via `.env` file
- **Security:**
  - API token management and guidance to keep credentials secure

## Requirements
- Node.js 18+

## Installation Methods
- Via Smithery CLI for Claude Desktop or other MCP clients
- Via `mcp-get` CLI
- Manual configuration in `claude_desktop_config.json`
- Docker image available on Docker Hub
- Local development with Bun package manager

## License
MIT License

## Pricing
No pricing information provided. The project is open source under the MIT License.