# unity3d-mcp

**Description:**  
MCP server for controlling and interacting with the Unity3d Game Engine, tailored for game development tasks. Implements the Model Context Protocol (MCP) for Unity Editor, allowing AI assistants to interact with Unity projects via a Node.js server.

**Source:** [unity3d-mcp on mcpservers.org](https://mcpservers.org/servers/CoderGamester/mcp-unity)

**Category:** Development Tools / MCP Servers

**Tags:** mcp, unity3d, game-development, api-integration

---

## Features
- **IDE Integration**: Automatic integration with VSCode-like IDEs (Visual Studio Code, Cursor, Windsurf), adding Unity Library/PackedCache folder to the workspace.
- **MCP Server Tools**:
  - `execute_menu_item`: Execute Unity Editor menu items (functions tagged with the MenuItem attribute).
  - `select_gameobject`: Select game objects in the Unity hierarchy by path or instance ID.
  - `update_component`: Update component fields or add components to GameObjects.
  - `add_package`: Install new packages via Unity Package Manager.
  - `run_tests`: Run tests using the Unity Test Runner.
  - `send_console_log`: Send logs to the Unity console.
  - `add_asset_to_scene`: Add assets from the AssetDatabase to the Unity scene.
- **MCP Server Resources**:
  - `unity://menu-items`: Retrieve all available Unity Editor menu items.
  - `unity://hierarchy`: Retrieve all game objects in the Unity hierarchy.
  - `unity://gameobject/{id}`: Get detailed info about a specific GameObject, including components and serialized fields.
  - `unity://logs`: Retrieve Unity Editor console logs.
  - `unity://packages`: Retrieve information about installed and available Unity packages.
  - `unity://assets`: Retrieve information about assets in the Asset Database.
  - `unity://tests/{testMode}`: Retrieve test information from Unity Test Runner.
- **AI Integration**: Enables AI agents (e.g., Claude, Windsurf, Cursor) to execute operations within Unity Editor.
- **WebSocket Server**: Default port 8090 (configurable), with adjustable timeout settings.
- **Node.js Backend**: Requires Node.js 18+; server built with TypeScript.
- **Debugging Support**: Includes instructions for building, running, and debugging the server.
- **MIT Licensed**

## Requirements
- Unity Editor
- Node.js 18 or later
- AI LLM Client (such as Claude Desktop, Cursor IDE, Windsurf IDE)

## Installation
1. Install the Unity MCP Server package via Unity Package Manager.
2. Install Node.js (version 18 or later).
3. Configure your AI LLM client with the MCP Unity server path.
4. Start the Unity Editor MCP Server.

## Pricing
No pricing information provided. (Open-source, MIT License)

## License
MIT License