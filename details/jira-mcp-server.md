# Jira MCP Server

[Source Code](https://github.com/KS-GEN-AI/jira-mcp-server)

## Description
Jira MCP Server is a TypeScript-based MCP server that enables interaction with Jira via the MCP protocol. It provides tools for executing JQL queries, managing Jira tickets, listing projects and statuses, and more. It is designed for integration with AI assistants and other clients that support the MCP protocol.

## Features
- **JQL Query Execution**: Run JQL queries against Jira and retrieve results.
- **Ticket Management**:
  - Create Jira tickets (specifying project, summary, description, type, and optional parent).
  - Edit Jira tickets (summary, description, labels, parent).
  - Delete Jira tickets.
  - Assign tickets to users.
- **Project and Status Listing**:
  - List Jira projects.
  - Retrieve all available statuses.
- **User Management**:
  - Query assignable users in a project.
- **Attachment Handling**:
  - Add attachments to tickets via image URLs.
- **Fetch Ticket Details**: Retrieve ticket name and description via JQL.
- **Integration**: Designed to be used with Claude Desktop and similar AI assistants via MCP protocol.
- **Development Tools**:
  - Inspector tool for debugging MCP communication.
  - Scripts for building and running the server with auto-rebuild support.

## Installation & Configuration
- Install dependencies with `npm install`.
- Build the server with `npm run build`.
- For development with auto-rebuild, use `npm run watch`.
- Configure environment variables for Jira URL, API mail, and API key.
- Example configuration provided for integration with Claude Desktop.

## Pricing
No pricing information is provided. The project appears to be open source on GitHub.