# Filesystem Python

A Model Context Protocol (MCP) server providing secure, read-only access to files in a specified directory, with features for file searching, .gitignore compliance, and security.

## Features
- Secure, read-only access to local directory files
- Supports file search and analysis through the MCP protocol
- Respects .gitignore patterns (excludes ignored files)
- Path traversal protection for security
- Automatic MIME type detection for files
- Uses the `file://` URI scheme
- Designed for integration with Claude Desktop (AI application)
- Compatible with Cursor (can be added globally or per project)
- Simple installation and configuration for macOS, Linux, and Windows
- Exposes directory files to compatible AI applications

## Installation & Usage
- Install with: `uv add mcp-filesystem-python`
- Run server by specifying directory: `uv run src/filesystem/server.py /path/to/directory`
- Configure for Claude Desktop or Cursor as per platform instructions

## Category
file-management-mcp-servers

## Tags
python, read-only, filesystem, mcp

## Source
[Filesystem Python on playbooks.com](https://playbooks.com/mcp/punkpeye-filesystem-python)

## Pricing
No pricing information provided.