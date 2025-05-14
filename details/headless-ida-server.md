# Headless Ida Server

**Category:** Code Execution Automation MCP Servers  
**Tags:** reverse-engineering, disassembly, automation, mcp, headless

## Description
Headless Ida Server is an MCP server that enables headless operation of IDA Pro for reverse engineering tasks. It allows users to perform binary analysis, disassembly, decompilation, function and variable management, and code annotation via the Model Context Protocol (MCP), all without requiring the IDA Pro GUI. The server provides a standardized API for interacting with IDA Pro's analysis capabilities, making it suitable for automation and integration into security research workflows.

## Features
- **Headless Operation**: Utilizes IDA Pro's headless mode (idat) for analysis without a GUI.
- **MCP Protocol Support**: Exposes IDA Pro's analysis capabilities via the Model Context Protocol for automation and integration.
- **Binary Analysis**: Supports reverse engineering of binary files with tools for function analysis, disassembly, and decompilation.
- **Code Annotation**: Enables annotation of code and management of functions and variables through the MCP interface.
- **Standardized API**: Provides a consistent API for programmatic interaction with IDA Pro.
- **Integration**: Can be integrated with tools like Cursor via configuration files for project-level or global use.
- **Configurable**: Server settings such as IDA path, port, host, and transport mode (sse or stdio) are customizable via environment variables.
- **Python-based**: Implemented in Python (requires Python 3.12+).
- **Open Source**: Repository available on GitHub.

## Installation
- **Prerequisites**: Python 3.12+, IDA Pro with headless support (idat)
- **Setup**:
    - Clone the repository: `git clone https://github.com/cnitlrt/headless-ida-mcp-server.git`
    - Install dependencies and set up a virtual environment using `uv`
    - Configure the `.env` file with IDA path and server settings
- **Running the Server**: Start the server with `uv run headless_ida_mcp_server`
- **Client Connections**: Connect via MCP Inspector or by configuring in your application.

## Source
[https://playbooks.com/mcp/headless-ida](https://playbooks.com/mcp/headless-ida)

## Pricing
No pricing information provided.
