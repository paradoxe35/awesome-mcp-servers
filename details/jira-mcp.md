# jira-mcp

A Go-based MCP (Model Control Protocol) connector for Jira that enables AI assistants like Claude to interact with Atlassian Jira. It provides a standardized interface for AI models to perform common Jira operations.

**Source:** [https://github.com/nguyenvanduocit/jira-mcp](https://github.com/nguyenvanduocit/jira-mcp)

## Features
- Get detailed issue information
- Create, update, and search issues (including child issues)
- List all available issue types and statuses
- Add and retrieve comments
- Add worklogs to issues
- List and manage sprints
- Retrieve issue history and relationships
- Link issues and get related issues
- Transition issues through workflows
- Docker and binary installation options
- Integrates with Claude and Cursor for AI-driven Jira management

## Installation
- Download pre-built binaries from GitHub Releases (Linux, macOS, Windows)
- Install with `go install github.com/nguyenvanduocit/jira-mcp@latest`
- Use Docker image (`ghcr.io/nguyenvanduocit/jira-mcp:latest`)

## Configuration
- Requires setting environment variables for Atlassian authentication: `ATLASSIAN_HOST`, `ATLASSIAN_EMAIL`, `ATLASSIAN_TOKEN`
- Supports configuration via Docker, .env file, or shell environment
- Example configurations provided for Cursor integration (Docker or local binary)

## License
MIT License

## Pricing
This is an open-source project, available for free under the MIT license.