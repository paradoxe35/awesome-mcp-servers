# mcp-server-asana

**Description:**  
mcp-server-asana is a Model Context Protocol (MCP) server implementation for Asana, enabling interaction with Asana's API from MCP clients such as Claude Desktop. It allows users to manage Asana tasks, projects, workspaces, comments, and more via standardized MCP tools.

**Source:** [GitHub - roychri/mcp-server-asana](https://github.com/roychri/mcp-server-asana)

**Category:** Project Management MCP Servers

**Tags:** asana, project-management, mcp, integration

---

## Features

- **Workspace Management**
  - List all available workspaces
  - Retrieve workspace details (name, ID, organization status, email domains)
- **Project Management**
  - Search projects by name pattern within a workspace
  - Retrieve detailed information about a specific project
  - Get task counts, sections, and statuses for projects
  - Create and delete project status updates
- **Task Management**
  - Search for tasks with advanced filtering (by text, subtype, completion, assignments, attachments, dependencies, custom fields, etc.)
  - Retrieve detailed information for a specific task or multiple tasks (up to 25 at once)
  - Create new tasks with various details (notes, HTML notes, due date, assignee, followers, parent, projects, custom fields)
  - Update task details (name, description, due date, assignee, completion, custom fields)
  - Manage task dependencies and dependents
  - Create subtasks and set parent relationships
  - Get tasks by tag
- **Comment/Story Management**
  - Retrieve comments and stories for a task
  - Add new comments/stories to tasks
- **Tag Management**
  - Get tags in a workspace
  - Retrieve tasks by tag
- **Prompts for AI/LLM Clients**
  - Generate task summaries and status updates
  - Analyze task completeness
  - Instructions for AI to create new tasks
- **Resource Representation**
  - Workspaces and projects are exposed as resources accessible via custom URIs (asana://workspace/{workspace_gid}, asana://project/{project_gid})
- **Integration**
  - Designed for use with AI tools (such as Claude Desktop) via MCP
  - Supports configuration via environment variables and JSON config
- **Advanced Filtering and Sorting**
  - Tasks and projects can be filtered and sorted by multiple fields and criteria
- **Open Source**
  - Licensed under the MIT License

## Setup

- Requires an Asana account and a personal access token (from Asana developer console)
- Configure the MCP client (e.g., Claude Desktop) to use the server and provide the Asana access token
- Beta versions can be installed from npm with the `@beta` tag

## Licensing

- Licensed under the MIT License

## Pricing

- **Open Source:** No pricing information; free to use under the MIT License.

---

For full usage and API details, see the [GitHub repository](https://github.com/roychri/mcp-server-asana).