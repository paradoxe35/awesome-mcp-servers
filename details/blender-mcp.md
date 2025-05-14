# blender-mcp

**Category:** AI Integration MCP Servers  
**Tags:** mcp, blender, 3d-modeling, ai-integration

## Description
BlenderMCP is a server that connects Blender to Claude AI via the Model Context Protocol (MCP), enabling Claude to directly interact with and control Blender. This integration allows for prompt-based 3D modeling, scene creation, and manipulation using natural language prompts.

## Features
- **MCP Integration:** Connects Blender to Claude AI through the Model Context Protocol for seamless communication.
- **Prompt-Based 3D Modeling:** Enables 3D modeling, scene creation, and manipulation in Blender using natural language prompts to Claude.
- **Direct AI Control:** Allows Claude AI to directly interact with and control Blender operations.
- **Two Main Components:** The system consists of a server component and a Blender add-on.
- **Cross-Platform Setup:** Installation instructions available for Mac and Windows, including integration with uv and Cursor.
- **Support for Claude Desktop and Cursor:** Works with Claude Desktop and Cursor for different workflows.
- **Example Command Support:** Users can ask Claude to perform various 3D tasks via natural language.
- **Hyper3D Integration:** Allows use of Hyper3D for model generation (with daily free trial key limits).
- **JSON-based Protocol:** Uses a simple JSON protocol over TCP sockets for communication.

## Installation
- Requires installation of `uv` (Python environment manager).
- Supports both Mac and Windows platforms.
- Blender add-on installation required.
- Detailed setup instructions provided for integration with Claude Desktop and Cursor.

## Limitations & Security
- Only one instance of the MCP server should be run at a time (either on Cursor or Claude Desktop).
- Subject to daily limits if using free Hyper3D trial keys.
- Third-party integration not made by Blender.

## Pricing
No pricing information provided; open-source project.

## Source
[GitHub Repository](https://github.com/skyiron/blender-mcp-claude)