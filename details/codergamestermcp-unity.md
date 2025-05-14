# MCP Unity (CoderGamester/mcp-unity)

**Category:** Development Tools / MCP Servers  
**Tags:** unity3d, game-development, ai-integration, open-source  
**Source:** [GitHub Repository](https://github.com/CoderGamester/mcp-unity)

## Description
MCP Unity is an implementation of the Model Context Protocol (MCP) server designed to integrate the Unity Editor game engine with various AI model clients such as Claude Desktop, Windsurf, and Cursor. It provides a bridge between Unity and a Node.js server implementing the MCP protocol, enabling AI-assisted development and tooling within Unity projects.

## Features
- **AI Integration Tools for Unity:**
  - `execute_menu_item`: Executes Unity menu items (functions tagged with the MenuItem attribute).
  - `select_object`: Selects game objects in the Unity hierarchy.
  - `package_manager`: Installs, removes, and updates packages via the Unity Package Manager.
  - `run_tests`: Runs tests using Unity Test Runner.
  - `notify_message`: Displays messages in the Unity Editor.

- **Resource Retrieval:**
  - `get_menu_items`: Lists all available Unity Editor menu items.
  - `get_hierarchy`: Lists all game objects in the Unity hierarchy.
  - `get_console_logs`: Retrieves logs from the Unity console.
  - `get_packages`: Information about installed and available packages in the Unity Package Manager.
  - `get_assets`: Information about assets in the Unity Asset Database.
  - `get_tests`: Information about tests in the Unity Test Runner.

- **Configuration & Customization:**
  - Configurable WebSocket server port (default 8080; can be changed via Unity Editor or environment variable).
  - Supports integration with multiple AI clients (Claude Desktop, Windsurf IDE, Cursor IDE) via configuration files.

- **Platform Requirements:**
  - Unity 2022.3 or later.
  - Node.js 18 or later.
  - npm 9 or later.

- **Installation:**
  - Via Unity Package Manager (add package from Git URL).
  - Node.js server setup with dependency installation and build steps.

- **Debugging & Logging:**
  - Integration with @modelcontextprotocol/inspector for debugging.
  - Customizable logging (console and file output).

- **Open Source:**
  - Licensed under the MIT license.
  - Contributions welcome via pull requests and issues.

## Pricing
- MCP Unity is open-source software licensed under the MIT license. There are no paid plans or pricing tiers.

## License
- MIT License

## Contributors
- CoderGamester Miguel Tomas
- smithery-ai[bot]
- punkpeye Frank Fiegel