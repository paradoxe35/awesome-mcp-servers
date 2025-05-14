# mcp-server-taskwarrior

**Category:** Project Management MCP Servers  
**Tags:** mcp, task-management, automation, open-source

## Description
mcp-server-taskwarrior is a Node.js server implementing the Model Context Protocol (MCP) to enable integration with TaskWarrior. It allows local TaskWarrior task management operations via MCP, such as adding, updating, and removing tasks.

## Features
- Implements an MCP server for TaskWarrior task operations
- Supports adding tasks
- Supports updating tasks
- Supports removing tasks
- Provides a `get_next_tasks` API method
- Provides an `add_task` API method
- Provides a `mark_task_done` API method
- Runs the local `task` binary, requiring TaskWarrior to be installed and configured
- Can be integrated with other tools (e.g., Claude Desktop)
- Open-source and licensed under MIT

**Note:**
- Currently uses TaskWarrior task IDs, which are unstable (tasks may be renumbered); future improvements may use task UUIDs for more reliability.

## Installation
- Requires TaskWarrior to be installed and configured on your system

## Source Code
[https://github.com/awwaiid/mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior)

## Pricing
- Open-source (MIT License) — free to use