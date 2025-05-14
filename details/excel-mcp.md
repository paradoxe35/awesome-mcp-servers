# Excel-MCP

[Excel-MCP](https://pypi.org/project/excel-mcp-server/) is an MCP (Model Context Protocol) server that enables programmatic manipulation of Excel files without requiring Microsoft Excel. It is designed to provide LLMs and other systems with the ability to read, write, and analyze data in Excel spreadsheets, supporting integration and automation workflows.

## Features
- **Excel File Manipulation Without Excel Installation:** Operates independently of Microsoft Excel using OpenPyXL.
- **Workbook Creation and Modification:** Create new workbooks, open existing ones, and save changes.
- **Worksheet and Range Management:** Add, delete, and manage worksheets; handle cell ranges.
- **Data Reading and Writing:** Read and write data to cells, ranges, and tables within Excel files.
- **Formatting and Styling:** Apply and modify cell formatting, styles, and number formats.
- **Charts and Visualizations:** Create and manage charts within Excel workbooks.
- **Pivot Tables:** Support for creating and manipulating pivot tables for data analysis.
- **Comprehensive Error Handling:** Provides clear error messages for troubleshooting and debugging.
- **Environment Configuration:** Flexible configuration of storage paths for Excel files using environment variables.
- **SSE Mode and MCP Integration:** Runs in server mode and communicates via Server-Sent Events (SSE) for integration with MCP clients and IDEs like Cursor.

## Requirements
- Python >= 3.10
- MCP SDK >= 1.2.0
- OpenPyXL >= 3.1.2

## License
MIT License

## Source
- [PyPI: excel-mcp-server](https://pypi.org/project/excel-mcp-server/)
- [GitHub Repository](https://github.com/haris-musa/excel-mcp-server)

## Pricing
No pricing information is provided; the project is open source under the MIT License.