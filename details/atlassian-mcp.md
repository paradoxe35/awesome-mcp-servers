# Atlassian MCP

Connect AI agents to Atlassian Jira and Confluence for seamless project and content management through a standardized interface.

## Features
- **Integration with Atlassian Products**: Connects with Jira and Confluence, allowing AI assistants to interact with these tools.
- **Natural Language Interface**: Enables users to perform actions and retrieve information from Jira and Confluence using natural language commands.
- **Jira Capabilities**:
  - View and search for issues based on various criteria
  - Get details about specific issues
  - Create, update, and manage issues
  - Transition issues through different workflow stages
  - Assign issues to team members
  - Manage agile boards and sprints (view, add issues to sprints, start/close sprints)
- **Confluence Capabilities**:
  - View page content and details
  - Create, update, and manage pages
  - Manage page hierarchies
  - View and add comments to pages
  - See and manage page attachments
  - Manage page versions
- **Standardized MCP Server**: Acts as a bridge between AI assistants and Atlassian APIs, enabling automation and workflow enhancements.
- **Installation Methods**:
  - Via Smithery CLI for Claude Desktop
  - Manual setup with Atlassian credentials
- **Configuration**:
  - Requires Atlassian instance URL, username/email, and API token
  - Credentials stored in a configuration file
- **Security Considerations**: API token required; permissions match those of the user. Advice to use limited-permission tokens and keep credentials secure.
- **Cursor Integration**: Can be added globally or per-project in Cursor for easy access by AI agents.
- **Written in Go**

## Installation & Setup
- Node.js environment required
- Atlassian account with API access
- API token from Atlassian

## Provider & Release
- Provider: Phuc Nguyen
- Release date: May 05, 2025

## Source & Documentation
- [Official page and documentation](https://playbooks.com/mcp/phuc-nt-atlassian)

## Pricing
- *No pricing information provided in the content.*

## Tags
- mcp, atlassian, project-management, ai-integration