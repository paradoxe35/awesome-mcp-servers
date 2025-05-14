# jupyter-notebook-mcp

Connects Jupyter Notebook to Claude AI via the Model Context Protocol (MCP), enabling direct AI interaction and notebook control.

**Source:** [GitHub Repository](https://github.com/jjsantos01/jupyter-notebook-mcp)

**Category:** code-execution-automation-mcp-servers

**Tags:** jupyter, notebooks, ai-integration, mcp

---

## Features

- **Two-way AI Integration:** Connects Claude AI to Jupyter Notebook using a WebSocket-based server for real-time communication.
- **Cell Manipulation:** Insert, execute, edit, and manage notebook cells programmatically.
- **Notebook Management:** Save notebooks and retrieve notebook and cell information.
- **Cell Execution:** Run specific cells or all cells in the notebook from Claude or external clients.
- **Output Retrieval:** Get output content (text or images) from executed cells, with options to limit text length.
- **Slideshow Support:** Set slide show types for notebook cells to facilitate presentations.
- **External Client Testing:** Includes a Python-based external client for interactive or batch testing of all available functions.
- **Compatibility:** Supports only Jupyter Notebook 6.x (not compatible with Jupyter Lab, v7.x, VS Code, or Google Colab).
- **Reconnection and Port Management:** Automatic reconnection and dynamic port allocation if default port is in use.
- **Security:** Runs arbitrary code—use with caution and ensure data backup.

### Available Tools via Claude AI
- `ping`: Check server connectivity
- `insert_and_execute_cell`: Insert and run a cell at a specific position
- `save_notebook`: Save current notebook
- `get_cells_info`: Retrieve info about all cells
- `get_notebook_info`: Retrieve notebook metadata
- `run_cell`: Execute a specific cell
- `run_all_cells`: Execute all cells
- `get_cell_text_output`: Retrieve text output of a cell
- `get_image_output`: Retrieve image output from a cell
- `edit_cell_content`: Edit an existing cell's content
- `set_slideshow_type`: Adjust the slide type for a cell

### Limitations
- Works only with Jupyter Notebook 6.x
- Text output from cells is limited to 1500 characters by default
- Does not support advanced Jupyter widget interactions
- Connection may timeout after inactivity

## Installation & Usage
- Requires Python 3.12+, `uv` package manager, and Claude AI desktop app
- Install and configure as described in the repository's README
- Includes instructions for setting up the MCP server, WebSocket server, and kernel integration

## License
MIT

## Pricing
No pricing information provided. This is an open-source project.
