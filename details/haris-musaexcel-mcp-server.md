# haris-musa/excel-mcp-server

- **Repository:** [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server)
- **Category:** Data Analysis & Exploration MCP Servers
- **License:** MIT
- **Tags:** mcp, excel, data-analysis, reporting, open-source

## Description
Excel MCP Server is a Model Context Protocol (MCP) server for manipulating Excel files programmatically. It allows creation, reading, modification, and advanced operations on Excel workbooks without requiring Microsoft Excel to be installed. It is designed for integration with AI agents and automation tools.

## Features
- Create and modify Excel workbooks
- Read and write data to Excel files
- Apply formatting and styles to cells and ranges
- Create charts and visualizations
- Generate pivot tables
- Manage worksheets and named ranges
- Batch read and write operations (data as list of lists)
- Environment variable configuration for file storage and server port
- Server-Sent Events (SSE) protocol support for transport
- Integration with AI tools like Cursor IDE and Claude Desktop
- Toolset for comprehensive Excel manipulation (see [TOOLS.md](https://github.com/haris-musa/excel-mcp-server/blob/main/TOOLS.md) for full documentation)

## Requirements
- Python 3.10 or higher

## Installation & Usage
- Install via `uv pip install -e .`
- Run server with `uv run excel-mcp-server` (default port 8000; configurable via `FASTMCP_PORT`)
- Configure Excel file directory with `EXCEL_FILES_PATH`
- Integrate with AI agents or use as a standalone service

## Pricing
- **Open Source:** Free (MIT License)

## Resources
- [Source Code](https://github.com/haris-musa/excel-mcp-server)
- [Documentation (TOOLS.md)](https://github.com/haris-musa/excel-mcp-server/blob/main/TOOLS.md)

## Release
- Latest: v0.1.1 (Apr 4, 2025)
