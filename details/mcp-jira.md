# mcp-jira

[Source Code](https://github.com/aashari/mcp-server-atlassian-jira)

A TypeScript-based Model Context Protocol (MCP) server that integrates Atlassian Jira with AI systems (such as Claude, Anthropic, Cursor AI, etc.), enabling LLMs to access, retrieve, and manage Jira project data in real time.

## Features

- **MCP Server for Jira**: Bridges AI assistants and Jira Cloud via the Model Context Protocol.
- **Real-time Jira Access**: AI assistants can access up-to-date Jira project and issue data.
- **Issue & Project Management**: Supports retrieving, listing, and searching Jira projects and issues.
- **Ticket Creation**: Allows creation and management of Jira tickets via AI.
- **Detailed Information Retrieval**: For projects and issues, retrieves all relevant data (description, fields, comments, components, versions, links, attachments) by default.
- **JQL Support**: Enables advanced searching/filtering of issues using Jira Query Language.
- **Minimal Setup**: Credentials can be configured via a global file or environment variables.
- **Multi-client Compatibility**: Compatible with Claude Desktop, Cursor AI, and other MCP-compatible clients.
- **CLI Tool**: Use directly from the command line for scripting or manual operations.
- **Security**: Access is secured via Atlassian API tokens; sensitive operations are contained.
- **Rich Output Philosophy**: Simple inputs yield detailed, context-rich outputs for AI consumption.
- **Debug Logging**: Debug logs can be enabled for troubleshooting.
- **Open Source**: Released under the ISC license.

### Available Tools
- **list-projects**: List all Jira projects (with optional filtering).
- **get-project**: Retrieve details for a specific project (by key or ID).
- **list-issues**: Search for issues using JQL, get keys/IDs for further queries.
- **get-issue**: Retrieve comprehensive details for a specific issue (by key or ID).

### Usage
- **Integration with AI clients**: Easily add as an MCP server to Claude Desktop or Cursor AI.
- **CLI usage**: Run commands like `list-projects`, `get-project`, `list-issues`, `get-issue` from the terminal after setup.

## Pricing

- **Open Source**: Free to use under the ISC license. No paid plans mentioned.

## Tags

`mcp` `jira` `project-management` `llm`