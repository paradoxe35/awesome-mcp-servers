# ClickUp MCP

[Source Code](https://github.com/nazruden/clickup-mcp-server)

## Description
ClickUp MCP is a Model Context Protocol (MCP) server that integrates with ClickUp, enabling AI assistants to interact with ClickUp workspaces. It allows for task creation, project management, and workflow automation for teams using AI-powered assistants. The server communicates via standard input/output as per the MCP specification when invoked by an MCP client.

## Features
- **Task Management**: Create and manage tasks in ClickUp workspaces.
- **Team & List Management**: Manage teams and lists within ClickUp.
- **Board Management**: Handle boards for project organization.
- **Space Management**: Manage spaces within ClickUp.
- **Folder Management**: Organize and manage folders.
- **Custom Field Management**: Set and manage custom fields for tasks and projects.
- **Doc Management**: Manage ClickUp Docs (with some API limitations, e.g., content handled as Markdown, no direct deletion via API).
- **View Management**: Manage views for different project perspectives.
- **Authentication**: Uses ClickUp Personal API Token.
- **Runs via Stdio**: Operates according to MCP specification for client-server communication.
- **Docker Support**: Includes Dockerfile for containerized deployment.
- **Development Tools**: TypeScript-based with Jest for testing.

## Category
Project Management MCP Servers

## Tags
clickup, project-management, workflow, ai-assistant

## Pricing
No pricing information provided; the project is open-source under the MIT License.