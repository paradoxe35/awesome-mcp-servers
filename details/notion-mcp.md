# notion-mcp

A Model Context Protocol (MCP) server that integrates with Notion's API to help manage personal todo lists efficiently.

**Source:** [https://github.com/Badhansen/notion-mcp](https://github.com/Badhansen/notion-mcp)

## Features
- **MCP Server for Notion**: Acts as a Model Context Protocol server which communicates with Notion's API.
- **Personal Todo List Management**: Specifically designed to manage your personal todo list within Notion.
- **Show Tasks**: Retrieve and display all tasks from your Notion workspace using the `show_all_todos` function.
- **Add Task**: Add new tasks to your Notion workspace with the `add_todo` function.
- **Update Task**: Mark tasks as complete or update them using the `complete_todo` function.
- **Integration with Claude Desktop**: Can be set up to work with Claude Desktop through configuration.
- **Python-based**: Requires Python 3.11+ to run.
- **Docker Support**: Dockerfile included for containerized deployment.
- **Smithery Installation**: Can be installed via Smithery CLI for easy integration.
- **Customizable Configuration**: Uses `.env` file for credentials and configuration.
- **MIT Licensed**: Open source under the MIT License.

## Prerequisites
- Python 3.11+
- Notion account with API access
- Notion integration token
- Notion workspace page or database

## Pricing
- **Free and Open Source** (MIT License)

## Tags
`mcp`, `notion`, `project-management`, `api-integration`