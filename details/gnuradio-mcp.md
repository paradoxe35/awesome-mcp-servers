# gnuradio-mcp

An MCP server for GNU Radio, enabling LLMs to autonomously create and modify RF flowcharts using the Model Context Protocol.

- **Source:** [GitHub Repository](https://github.com/yoelbassin/gnuradioMCP)
- **Category:** Code Execution Automation (MCP Servers)
- **Tags:** gnuradio, automation, llm, mcp

## Features

- **MCP API:** Provides a robust Machine Control Protocol (MCP) interface for GNU Radio.
- **Programmatic Flowgraph Creation:** Allows building, editing, and saving GNU Radio Companion (.grc) flowgraph files programmatically or via automation.
- **LLM & Automation Ready:** Designed for integration with Large Language Models (LLMs), bots, and various automation tools.
- **Extensible Architecture:** Modular design for easy extension and customization.
- **Example Flowgraphs:** Includes ready-to-use example .grc files in the `misc/` directory.
- **Validation:** Implements validation of GNU Radio elements and provides error handling.
- **Tested:** Comprehensive unit tests using pytest.
- **Development Tools:** Includes pre-commit hooks and support for development environments.

## Requirements

- Python >= 3.13
- GNU Radio (tested with GNU Radio Companion v3.10.12.0)
- UV (Python environment manager)

## Usage

- Clone the repository and set up the environment using UV.
- Integrate the MCP server into clients (e.g., Claude Desktop, Cursor) via configuration.

## Project Status

- Actively developed; core server functionality is available and the API/features are evolving.

## Pricing

- No pricing information provided; open source on GitHub.
