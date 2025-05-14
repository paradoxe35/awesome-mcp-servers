# notion_mcp

**Category:** Project Management MCP Servers  
**Tags:** mcp, notion, project-management, integration

[Source Code on GitHub](https://github.com/danhilse/notion_mcp)

---

## Description
`notion_mcp` is a Model Context Protocol (MCP) server that integrates with Notion's API to allow management of a personal todo list from MCP-compatible clients, such as Claude Desktop. It is designed for a minimalist Notion todo list setup and is intended primarily as a starting point for personal projects or further customization.

---

## Features
- Add new todo items to a Notion database
- View all todo items
- View only today's tasks
- Mark tasks as complete (check off a task)

---

## Requirements
- Python 3.10 or higher
- Notion account
- Notion API integration (API key)
- A Notion database that matches the structure:
  - Task (title)
  - When (select: "today" or "later")
  - Checkbox (completed status)

---

## Limitations
- Only works with a specific Notion database structure
- No support for complex schemas, additional properties, or custom fields
- Limited to "today" or "later" task scheduling
- Basic error handling
- No advanced features (e.g., recurring tasks, priorities, tags)

---

## Customization
- To use with a different Notion database structure, modification of the code (especially `server.py`) is necessary:
  - Adjust `create_todo()` for your properties
  - Change todo formatting in `call_tool()`
  - Update input schema in `list_tools()` for different options

---

## Setup & Usage
1. Clone the repository and set up a Python virtual environment.
2. Install dependencies.
3. Create a Notion integration and share your database with it.
4. Configure the `.env` file with your Notion API key and database ID.
5. Optionally, configure Claude Desktop to use the MCP server automatically.
6. Run the server directly or through Claude Desktop.

### Example Commands (via Claude):
- "Show all my todos"
- "What's on my list for today?"
- "Add a todo for today: check emails"
- "Add a task for later: review project"

---

## License
MIT License

---

## Pricing
This is an open source project and is free to use.
