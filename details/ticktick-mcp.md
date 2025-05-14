# ticktick-mcp

[GitHub Repository](https://github.com/ekkyarmandi/ticktick-mcp)

TickTick MCP is an open-source Model Context Protocol (MCP) server that integrates with TickTick's API, allowing AI assistants and applications to manage personal to-do projects and tasks through standardized MCP tools.

---

## Features

- **Integration with TickTick:** Connects to TickTick's task management platform using its OpenAPI and OAuth2 authentication.
- **MCP Protocol Support:** Implements a Model Context Protocol (MCP) server for AI-driven task management.
- **Task and Project Operations:**
  - Retrieve all projects (`get_projects`)
  - Get details of a specific project (`project_details`)
  - Get details of a specific task (`get_task_details`)
  - Create new projects (`create_project`)
  - Create new tasks in a project (`create_task`)
  - Update existing tasks (`update_task`)
  - Mark tasks as complete (`complete_task`)
  - Delete tasks (`delete_task`)
- **Natural Language Support:** Enables AI systems to manage tasks using natural language commands.
- **MCP Client Compatibility:** Can be used with any MCP-compatible client (e.g., Claude Desktop, Cursor IDE, or custom MCP SDK-based applications).
- **Python-based Implementation:** Built with Python 3.8+ and uses the MCP SDK.
- **Open Source:** Licensed under the MIT License.

## Requirements

- Python 3.8+
- TickTick account
- TickTick API key obtained via OAuth2 (instructions provided in the repository)

## Installation & Usage

1. Clone the repository and install dependencies with `pip install -r requirements.txt`.
2. Register an application in the TickTick Developer Portal to obtain API credentials.
3. Use the `ticktick-py` library to authorize and obtain an access token.
4. Create a `.env` file with your TickTick API key.
5. Start the MCP server with `python main.py`.

## Pricing

- **Free and open-source** (MIT license)

## Tags

`mcp` `task-management` `api-integration` `open-source`

---