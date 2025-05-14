# Excel MCP Server

[Excel MCP Server](https://pypi.org/project/excel-mcp-server/) is a Model Context Protocol (MCP) server that enables comprehensive Excel file manipulation without requiring Microsoft Excel to be installed. It leverages OpenPyXL to provide a wide range of Excel-related features and can be integrated with MCP clients for automated data workflows.

## Features
- **No Excel Required:** Manipulate Excel files without installing Microsoft Excel.
- **Workbook Management:** Create and modify Excel workbooks.
- **Worksheet and Range Management:** Add, remove, and manage worksheets and cell ranges.
- **Data Manipulation:** Read, write, and transform data within workbooks.
- **Formatting and Styling:** Apply formatting and styles to cells, rows, columns, and ranges.
- **Charts and Visualizations:** Create and manage charts within Excel files.
- **Pivot Tables and Data Analysis:** Generate and manipulate pivot tables for data analysis.
- **Comprehensive Error Handling:** Provides clear error messages for troubleshooting.
- **Live Data Feeds & Auto-Updates:** Supports automated reporting by enabling live data feeds and synchronization (as described in the summary).
- **Environment Configuration:** Customizable storage directory for Excel files via environment variables.
- **SSE Mode:** Runs as a server in Server-Sent Events mode for real-time client communication.

## Requirements
- Python >= 3.10
- MCP SDK >= 1.2.0
- OpenPyXL >= 3.1.2

## Usage
- Configure the `EXCEL_FILES_PATH` environment variable to set the storage directory for Excel files.
- Start the server with `uv run excel-mcp-server`.
- Connect MCP clients (such as Cursor IDE) to the server for Excel file operations.

## License
MIT License

## Pricing
No pricing information is provided; the project is open source and available on PyPI.