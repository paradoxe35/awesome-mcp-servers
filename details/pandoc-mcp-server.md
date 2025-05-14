# Pandoc MCP Server

A Model Context Protocol (MCP) server for document format conversion using Pandoc. It provides tools to transform content between various document formats while preserving formatting and structure.

[View Source](https://mcpservers.org/servers/vivekVells/mcp-pandoc)

## Features
- Converts documents between multiple formats using Pandoc.
- Supported input/output formats:
  - Basic: Markdown (.md), HTML (.html), Plain text (.txt)
  - Advanced: PDF (.pdf, requires TeX Live), DOCX (.docx), RST (.rst), LaTeX (.tex), EPUB (.epub)
- `convert-contents` tool:
  - Inputs: `contents` (string), `input_file` (path), `input_format`, `output_format`, `output_file` (required for advanced formats)
  - Can transform content between any supported formats.
- For basic formats, converted content can be displayed directly in chat; for advanced formats, file path and extension must be specified.
- PDF conversion requires TeX Live installation (Ubuntu/Debian: `sudo apt-get install texlive-xetex`, macOS: `brew install texlive`, Windows: MiKTeX or TeX Live).
- Open source and officially part of the Model Context Protocol servers project.
- Installation options:
  - Manual configuration via `claude_desktop_config.json`
  - Automatic installation via Smithery CLI
- Development and publishing tools for package management and PyPI publishing.
- Debugging support via MCP Inspector.
- Contributions are welcome via GitHub issues and pull requests.

## Critical Requirements
- For advanced format conversion (PDF, DOCX, RST, LaTeX, EPUB), a complete file path including filename and extension must be provided.
- PDF conversion requires TeX Live to be installed.

## Pricing
- No pricing information provided; the server is open-source.

## Tags
pandoc, document-conversion, automation, open-source