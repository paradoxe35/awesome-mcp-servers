# Excel Reader Server

A Model Context Protocol (MCP) server for reading Excel (xlsx) files, allowing extraction of data from workbooks or sheets and returning structured JSON results.

[View Source](https://www.mcpserverfinder.com/servers/softgridinc-pte-ltd/mcp-excel-reader-server)

## Features
- Read content from all sheets in an Excel file
- Read content from a specific sheet by name
- Read content from a specific sheet by index
- Returns data in a structured JSON format:
  - Each sheet is a key in the JSON object
  - Sheet data is an array of arrays (rows)
  - All values are converted to strings
  - Empty cells are represented as empty strings
- Handles empty cells and data type conversions
- Provides clear error messages for:
  - File not found
  - Invalid sheet name
  - Index out of range
  - General Excel file reading errors
- Built with Python (requires Python 3.10+)
- MIT License

## Installation
- Requires Python 3.10 or higher
- Install via pip: `pip install excel-reader-server`
- Or via uv: `uv pip install excel-reader-server`
- Dependencies: mcp >= 1.2.1, openpyxl >= 3.1.5

## Usage
- `read_excel`: Reads content from all sheets
- `read_excel_by_sheet_name`: Reads content from a specific sheet by name (default: first sheet)
- `read_excel_by_sheet_index`: Reads content from a specific sheet by index (default: index 0)

## Pricing
- Open source (MIT License)

## Tags
mcp, excel, spreadsheet, data-extraction

## Category
Data Access & Integration MCP Servers