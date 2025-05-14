# jupyter-mcp-server

**Description:**
Jupyter MCP Server is an implementation of the Model Context Protocol (MCP) server for Jupyter, enabling seamless integration of the MCP with Jupyter environments. It allows interaction with Jupyter notebooks running locally or in JupyterLab, and can be used with tools like Claude Desktop.

**Source:** [https://github.com/datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server)

**Category:** Development Tools / MCP Servers

**Tags:** jupyter, notebooks, mcp, integration

---

## Features

- **MCP Server Implementation for Jupyter**: Enables Model Context Protocol integration with Jupyter notebooks and JupyterLab environments.
- **Jupyter Real Time Collaboration Support**: Works with Jupyter's real-time collaboration features, allowing live notebook modifications.
- **Docker Support**: Can be run in a Docker container for easy deployment and integration.
- **Claude Desktop Integration**: Provides configuration examples for using the server with Claude Desktop on macOS, Windows, and Linux.
- **Tooling Provided:**
  - **add_execute_code_cell**: Adds and executes a code cell in a Jupyter notebook, returning the cell's output.
  - **add_markdown_cell**: Adds a markdown cell in a Jupyter notebook, returning a success message.
  - **download_earth_data_granules**: Adds a code cell to download Earth data from NASA Earth Data (planned to be migrated to a separate repository; specific for geospatial analysis). Supports specifying folder, dataset, number of granules, temporal range, and bounding box.
- **Installation Options**:
  - Install via pip for JupyterLab and required dependencies.
  - Build and run via Docker.
  - Install automatically for Claude Desktop using Smithery (`npx -y @smithery/cli install @datalayer/jupyter-mcp-server --client claude`).
- **Configuration Guidance**: Provides detailed steps and configuration examples for connecting to JupyterLab and integrating with Claude Desktop.

---

## Pricing
No pricing information is provided; the project appears to be open-source.

---

## License
Open source (see [repository license](https://github.com/datalayer/jupyter-mcp-server/blob/main/LICENSE)).