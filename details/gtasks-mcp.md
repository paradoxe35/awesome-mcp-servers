# gtasks-mcp

**Description:**  
gtasks-mcp is a Model Context Protocol (MCP) server that integrates with Google Tasks, enabling management of tasks via an MCP server interface. It allows applications (such as Claude) to interact with Google Tasks for comprehensive task management.

**Source:** [https://github.com/zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp)

**Category:** project-management-mcp-servers

**Tags:** mcp, google-tasks, task-automation, integration

---

## Features

- **Google Tasks Integration:** Connects directly to Google Tasks, allowing management of tasks from external applications.
- **Task Operations:**
  - **List:** Retrieve all tasks from Google Tasks, with optional pagination.
  - **Search:** Search for tasks using a query string.
  - **Create:** Add new tasks with title, notes, due date, and optional task list selection.
  - **Update:** Modify existing tasks, including title, notes, status (needsAction/completed), due date, and more.
  - **Delete:** Remove tasks by specifying task and task list IDs.
  - **Clear:** Remove all completed tasks from a specified task list.
- **Resource Model:**
  - Access and manipulate individual tasks via a resource URI (gtasks:///<task_id>).
  - Read task details such as title, status, due date, notes, and metadata.
- **Authentication:**
  - Uses OAuth 2.0 to securely access Google Tasks API.
  - Supports saving credentials for repeat access.
- **Deployment:**
  - Can be installed via Smithery CLI for integration with Claude Desktop and other compatible clients.
  - Built with TypeScript and JavaScript, with Dockerfile included for containerized deployment.

## Getting Started

- Requires setting up a Google Cloud project, enabling the Google Tasks API, and configuring OAuth credentials.
- Authentication is performed via a browser-based OAuth flow, with credentials stored locally for the server.

## Pricing

- **Open Source:** Free to use under the MIT license.

---

**Contributors:**
- Zach Caceres
- Henry Mao
