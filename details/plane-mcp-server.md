# plane-mcp-server

[Source Code](https://github.com/kelvin6365/plane-mcp-server)

A Model Context Protocol (MCP) server that allows LLMs to interact with Plane.so for managing projects and issues through Plane's API. Designed to let language models (such as Claude) directly handle project management workflows while maintaining user control and security.

## Features
- List all projects in your Plane workspace
- Get detailed information about specific projects
- Create new issues with customizable properties (title, HTML description, priority, state, assignees)
- List and filter issues from projects (by state, priority, assignee, limit)
- Get detailed information about specific issues
- Update existing issues (title, description, priority, state, assignees)
- Tools are provided as MCP endpoints (list-projects, get-project, create-issue, list-issues, get-issue, update-issue)
- Supports multiple clients (Claude, Cursor, etc.) via Smithery
- User approval required for all operations that modify data
- Secure handling of API keys via environment variables
- Error handling for common input mistakes (such as incorrect assignee formats)
- Development and testing support (TypeScript, MCP Inspector)

## Prerequisites
- Node.js 22.x or higher
- Plane.so API key
- Plane.so workspace

## Installation
- Via Smithery CLI (recommended)
- Manual setup (clone, install dependencies, build)

## Security Considerations
- Requires proper Plane permissions
- Explicit user approval for data modification
- API keys should be secured and never committed to version control

## License
MIT License

## Pricing
No pricing information provided; open source (MIT license).