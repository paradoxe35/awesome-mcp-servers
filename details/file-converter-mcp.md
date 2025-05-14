# File Converter Mcp

[GitHub Repository](https://github.com/wowyuarm/file-converter-mcp)

## Description
File Converter Mcp is an MCP (Model Context Protocol) server that provides a suite of file conversion tools for AI agents. It supports conversion between various document and image formats and is designed for integration into AI workflows.

## Features
- **Multiple File Conversion Tools**: Supports converting between document formats (e.g., DOCX to PDF, PDF to DOCX, Excel to CSV, HTML to PDF) and image formats.
- **Generic Conversion**: Includes generic file and content converters for flexible use cases.
- **Dual-Mode Input**:
  - Path-Based Conversion: Traditional method using file paths.
  - Content-Based Conversion: Allows direct content input, useful when file paths are not accessible.
- **Backward Compatibility**: Legacy content-based conversion tools are maintained for compatibility, though all main tools now support content-based input.
- **Robust File Handling**: Handles file path resolution and fallback to content-based conversion, especially tailored for integration with Claude and similar systems.
- **API/Commands**:
  - `docx2pdf`
  - `pdf2docx`
  - `convert_image`
  - `excel2csv`
  - `html2pdf`
  - `convert_file` (generic)
  - `convert_content` (legacy)
  - `docx2pdf_content` (legacy)
  - `pdf2docx_content` (legacy)
  - `markdown2pdf_content` (legacy)
- **Error Handling**: Provides mechanisms to handle file lookup failures and fallback strategies.
- **Open Source**: Licensed under the MIT License.

## Technologies
- Built using Python
- Follows Model Context Protocol (MCP) standards

## Installation & Usage
- Clone the repository and install dependencies using pip or uv.
- Optionally, install on Claude Desktop.
- Run the server in development mode for testing.

## Pricing
This project is open source and free to use under the MIT License.

## Tags
mcp, document-conversion, file-management, ai-integration