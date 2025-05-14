# Blender Open MCP

[GitHub Repository](https://github.com/dhakalnirajan/blender-open-mcp)

## Summary
Blender Open MCP is an open source tool that integrates Blender with local AI models (via Ollama) using the Model Context Protocol (MCP). It enables users to control and automate 3D modeling tasks in Blender using natural language prompts, leveraging local AI models for enhanced workflow.

## Features
- **Natural Language Control:** Interact with Blender using natural language prompts sent to a locally running AI model (Ollama).
- **Model Context Protocol (MCP):** Structured communication between Blender and AI models for reliable automation.
- **Ollama Integration:** Supports Ollama for local model management and inference.
- **Blender Add-on:** Includes a user interface within Blender for managing the connection and communication with the MCP server.
- **PolyHaven Integration (Optional):** Search, download, and use HDRIs, textures, and models from PolyHaven directly from Blender via AI prompts.
- **Basic 3D Operations:**
  - Retrieve scene and object information
  - Create primitives (e.g., cubes)
  - Modify or delete objects
  - Apply materials
- **Rendering Support:** Trigger renders and retrieve rendered images through prompts.
- **Command-line Tool:** Interact with the server via the `mcp` command-line tool.
- **Available Tools:**
  - `get_scene_info`: Retrieve scene details
  - `get_object_info`: Get object-specific details
  - `create_object`: Create 3D objects with specific parameters
  - `modify_object`: Change properties of existing objects
  - `delete_object`: Remove objects from the scene
  - `set_material`: Assign materials and colors
  - `render_image`: Render images to files
  - `execute_blender_code`: Run arbitrary Blender Python code
  - `get_polyhaven_categories`: List PolyHaven asset categories
  - `search_polyhaven_assets`: Search assets from PolyHaven
  - `download_polyhaven_asset`: Download assets from PolyHaven
  - `set_texture`: Assign downloaded textures to objects
  - `set_ollama_model`: Choose which Ollama model to use
  - `set_ollama_url`: Configure the Ollama server address
  - `get_ollama_models`: List available models in Ollama

## Installation Requirements
- Blender 3.0 or later
- Ollama (local AI model management)
- Python 3.10 or later
- `uv` (Python package manager)
- Git

## Usage Overview
- Clone the repository and set up a Python virtual environment.
- Install dependencies and the Blender add-on.
- Ensure Ollama is running with a compatible model.
- Start the MCP server and connect via the Blender add-on or command-line tool.
- Use natural language or tool commands to interact with Blender.

## Pricing
Blender Open MCP is open source and free to use.

## Tags
`blender`, `3d-modeling`, `ai-integration`, `natural-language`