# omniparser-autogui-mcp

**Category:** Code Execution Automation MCP Servers  
**Tags:** automation, gui, ai-integration, mcp, open-source

## Description
omniparser-autogui-mcp is an open-source MCP server that enables automatic operation of on-screen GUI elements. It uses OmniParser to analyze the screen and allows AI models to control GUI elements programmatically via the MCP interface. It is primarily confirmed to work on Windows.

## Features
- **Automatic GUI Control:** Allows for the automation of on-screen GUI operations, making it possible for AI models to interact with GUI elements.
- **OmniParser Integration:** Utilizes OmniParser for screen analysis, which can be configured with various backends and models.
- **AI Integration:** Designed to integrate with AI models that require control over GUI elements through MCP.
- **Configurable Environments:** Supports configuration via environment variables for backend loading, target window selection, remote OmniParser server, and more.
  - `OMNI_PARSER_BACKEND_LOAD`: Specify for compatibility with certain clients.
  - `TARGET_WINDOW_NAME`: Target specific window for GUI operations.
  - `OMNI_PARSER_SERVER`: Offload OmniParser processing to another device.
  - `SSE_HOST`, `SSE_PORT`: Enable communication via SSE instead of stdio.
  - `SOM_MODEL_PATH`, `CAPTION_MODEL_NAME`, `CAPTION_MODEL_PATH`, `OMNI_PARSER_DEVICE`, `BOX_TRESHOLD`: Advanced OmniParser configuration.
- **Langchain Example:** Includes example for integrating with Langchain.
- **Open Source:** Released under the MIT license (with some dependencies under other licenses).
- **Windows Support:** Confirmed to work on Windows platforms.

## Installation
- Clone repository with submodules: `git clone --recursive https://github.com/NON906/omniparser-autogui-mcp.git`
- Use Python environment manager `uv` for syncing dependencies.
- Run model download script and configure OCR language.
- Additional setup for integration with Claude Desktop or other MCP clients.

## Usage
- Can be configured to operate on the entire screen or specific windows.
- Can communicate via standard input/output or SSE.
- Example configurations provided for integration with other tools and servers.

## Source
[GitHub Repository](https://github.com/NON906/omniparser-autogui-mcp)

## Pricing
- **Free and Open Source** (MIT License; some submodules may have different licenses)
