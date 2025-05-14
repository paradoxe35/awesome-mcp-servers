# Unity MCP

**Category:** Development Tools / MCP Servers  
**Source:** [GitHub - IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP)

## Description
Unity MCP is an MCP server implementation and plugin for the Unity Editor and Unity-based games. It enables integration between AI agents (such as LLM clients like Claude Desktop or Cursor) and Unity projects via the Model Context Protocol (MCP). The tool is aimed at developers seeking to connect AI assistants or automation tools to Unity environments, with extensibility to add custom tools.

## Features
- **MCP Server and Unity Plugin**: Provides an MCP server and a Unity plugin to bridge LLMs and Unity, exposing Unity's tools and APIs to AI clients.
- **AI Connector**: Integrated AI Connector window in Unity Editor for managing connections to MCP clients.
- **Extensible Tooling**: Developers can define and expose custom tools directly in Unity project codebase for use by AI or automation clients.
- **Supported Unity Versions**: Compatible with Unity 2022.3.61f1, 2023.2.20f1, and 6000.0.46f1.
- **Implemented AI Tools**:
    - **GameObject Management**: Create, destroy, find, set parent, duplicate, modify properties (tag, layer, name, static).
    - **Component Management**: Add, get, modify, set field/property values, set reference links, destroy components.
    - **Editor State**: Get and set playmode state, get/set selection.
    - **Prefabs**: Instantiate, open, modify, save, close.
    - **Assets**: Create, find, refresh, read, modify, rename, delete, move, create folders.
    - **Scenes**: Create, save, load, unload, get loaded scenes, get hierarchy.
    - **Materials**: Create, modify, read, assign to components.
    - **Shaders**: List all shaders.
    - **Scripts**: Read, update/create, delete.
- **Planned/Upcoming Features**:
    - Modify GameObject
    - Remove missing components
    - Get/Set Editor windows, layers, tags
    - Execute MenuItem, run tests
    - Asset import
    - Scene search, raycast
    - ScriptableObject support
    - Debug log reading
    - Package management (install, remove, update)
    - Custom in-game tool support
- **Custom Tool Development**: Developers can add custom tools by defining classes and methods with specific attributes, making new functionality accessible to AI clients.
- **Open Source**: Licensed under Apache-2.0.

## Installation
- Requires .NET 9.0 and OpenUPM-CLI.
- Install via OpenUPM with:  
  `openupm add com.ivanmurzak.unity.mcp`

## Usage
- Accessible via `Window/AI Connector (Unity-MCP)` in Unity Editor.
- Connect to supported MCP clients (Claude Desktop, Cursor, or custom clients).
- Custom tool development is supported for Unity Editor (in-game support planned).

## Pricing
- **Open Source**: Free to use under the Apache-2.0 license.

## Tags
unity3d, game-development, ai-integration, mcp
