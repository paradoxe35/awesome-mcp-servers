# mcp-vegalite-server

**Source:** [GitHub - isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server)

**Category:** Data Visualization

**Tags:** data-visualization, vegalite, charts, mcp

## Description
mcp-vegalite-server is a Model Context Protocol (MCP) server that provides an interface for generating data visualizations from fetched data using the Vega-Lite format and renderer. It is designed to allow large language models (LLMs) or other clients to interactively save data tables and create visualizations via Vega-Lite specifications.

## Features
- **MCP Server Implementation:** Provides an interface for LLMs to visualize data using Vega-Lite syntax.
- **Core Tools:**
  - `save_data`: Save a table of data aggregations to the server for later visualization.
    - Inputs: `name` (string), `data` (array of objects)
    - Returns: Success message
  - `visualize_data`: Visualize a saved data table using a Vega-Lite specification.
    - Inputs: `data_name` (string), `vegalite_specification` (JSON string)
    - Returns: 
      - If `--output_type` is set to `text`, returns a success message and the complete Vega-Lite specification with data.
      - If `--output_type` is set to `png`, returns a base64 encoded PNG image of the visualization.
- **Integration:** Can be added to other applications (e.g., Claude Desktop) by configuring the server command and arguments.
- **Written in Python.**

## Pricing
No pricing information is provided; the project is open source on GitHub.
