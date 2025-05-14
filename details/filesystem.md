# Filesystem

[Source code on GitHub](https://github.com/MarcusJellinghaus/mcp_server_filesystem)

A secure Model Context Protocol (MCP) server for file system operations, designed to allow AI assistants (such as Claude) to safely perform file and directory operations within a specified project directory. The server prioritizes security by restricting access and operations to the configured directory and provides robust path validation and access controls.

## Features

- **Project Directory Restriction:** All operations are limited to a specified project directory; attempts to access files outside this directory are blocked.
- **File Operations:**
  - **List Directory:** List all files and directories, filtered according to `.gitignore` and excluding `.git` folders.
  - **Read File:** Read contents of a file (relative to project directory).
  - **Save File:** Atomically write content to a file.
  - **Append File:** Append content to the end of an existing file.
  - **Delete File:** Permanently delete a file (within allowed directories only).
  - **Edit File:** Selective, pattern-based edits with advanced options:
    - Line and multi-line matching
    - Fuzzy matching with confidence scoring
    - Indentation and whitespace normalization
    - Dry-run and configurable formatting
    - Git-style diff output
- **Security Controls:**
  - All file paths normalized and validated to prevent path traversal
  - Delete and write operations restricted to project directory
  - Atomic file writes to prevent data corruption
- **Structured Logging:**
  - Human-readable and JSON log formats
  - Configurable log levels (DEBUG, INFO, etc.)
  - Optional log file output
  - Function call tracking and error context
- **Integration:**
  - Designed for use with Claude Desktop and other MCP-compatible AI assistants
  - Provides a clean API for integration
- **Development Tools:**
  - Compatible with MCP Inspector for debugging and testing
  - Python-based, with easy setup via virtual environment
- **Open Source:**
  - Licensed under MIT License

## Pricing

- **Open Source / Free:** Licensed under the MIT License; no cost to use or modify.

## Category

- file-management-mcp-servers

## Tags

mcp, filesystem, file-management, security