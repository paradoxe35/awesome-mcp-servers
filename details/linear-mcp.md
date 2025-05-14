# Linear MCP

A server that integrates Linear's project management system with the Model Context Protocol (MCP), allowing large language models (LLMs) to interact programmatically with Linear issues and project data.

**Source:** [GitHub - jerhadf/linear-mcp-server](https://github.com/jerhadf/linear-mcp-server)

## Features
- **MCP Server for Linear:** Exposes Linear's project management and issue tracking system to LLMs via the MCP protocol.
- **Issue Management Tools:**
  - `linear_create_issue`: Create new issues in Linear with support for title, team, description, priority, and status.
  - `linear_update_issue`: Update existing issues, including title, description, priority, and status.
  - `linear_search_issues`: Search issues with filters like query, team, status, assignee, labels, priority, and result limits.
  - `linear_get_user_issues`: Retrieve issues assigned to a user, with options for archived status and result limits.
  - `linear_add_comment`: Add comments to issues, with support for markdown, custom username, and avatar.
- **Resource Access:**
  - View individual issue details (`linear-issue:///{issueId}`)
  - View all issues for a team (`linear-team:///{teamId}/issues`)
  - View issues assigned to a user (`linear-user:///{userId}/assigned`)
  - View organization information (`linear-organization:`)
  - View current user context (`linear-viewer:`)
- **Integration with Claude Desktop:**
  - Supports both automatic and manual installation for use with Claude Desktop.
  - Example prompts provided for common project management queries and workflows.
- **Development Ready:**
  - Open source under the MIT License.
  - Written in JavaScript/TypeScript.
  - Includes instructions for installation, configuration, and development setup.

## Pricing
- **Open Source:** Licensed under the MIT License. Free to use, modify, and distribute.

## Tags
mcp, linear, project-management, ai-integration