# MCP Atlassian

**Category:** Project Management MCP Servers  
**Tags:** mcp, atlassian, project-management, integration  
**Source:** [GitHub - sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian)

## Description
MCP Atlassian is an open-source Model Context Protocol (MCP) server that integrates with Atlassian Confluence and Jira, supporting both Cloud and Server/Data Center deployments. It enables searching, reading, creating, and managing content across Atlassian workspaces, making it a comprehensive MCP server solution for Atlassian environments.

## Compatibility
- **Confluence Cloud**: Fully supported
- **Confluence Server/Data Center**: Supported (version 7.9+)
- **Jira Cloud**: Fully supported
- **Jira Server/Data Center**: Supported (version 8.14+)

## Features
- **Integration with Confluence & Jira**: Supports both Cloud and Server/Data Center deployments.
- **Flexible Installation Methods**:
  - Via `uvx` (recommended), `pip`, or Docker.
- **Authentication**: Supports API tokens for Cloud and personal access tokens for Server/Data Center.
- **Configurable**:
  - Use only Confluence, only Jira, or both.
  - Command line and environment variable configuration.
  - Optional arguments for SSL verification, transport type (stdio/SSE), port, search filters (spaces/projects), read-only mode, and logging verbosity.
- **IDE Integration**:
  - Ready-to-use integration configurations for Claude Desktop, Cursor IDE, and Docker setups.
- **Resource Filtering**: Only shows Confluence spaces and Jira projects the user is actively involved with.
- **Available Tools**:
  - **Confluence**:
    - Search content using CQL
    - Get content, children, ancestors, and comments of pages
    - Create, update, and delete pages
  - **Jira**:
    - Get issue details
    - Search issues using JQL
    - Get all issues for a project
    - Create, update, and delete issues
    - Get and transition issue status
    - Add/get worklogs
    - Link issues to Epics and get Epic issues
- **Transport Options**: Supports stdio (default) and SSE (Server-Sent Events) transports.
- **Read-only Mode**: Option to disable all write operations.
- **Development & Debugging**:
  - Local development setup instructions
  - MCP Inspector for debugging
  - Log viewing guidance
- **Security**: Emphasizes secure handling of API tokens and environment files.
- **MIT Licensed**

## Pricing
- **Open Source**: Free to use under the MIT license.

## Links
- [Source Code & Documentation](https://github.com/sooperset/mcp-atlassian)
