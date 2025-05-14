# Filesystem Server

A secure Model Context Protocol (MCP) server that provides file system operations for AI assistants. It enables assistants such as Claude to safely read, write, list, edit, append, and delete files within a designated project directory, with robust path validation and security controls.

**Source:** [GitHub Repository](https://github.com/MarcusJellinghaus/mcp_server_filesystem)

## Features

- **list_directory:** List all files and directories in the project directory (filters based on .gitignore and excludes .git folders).
- **read_file:** Read the contents of a file.
- **save_file:** Write content to a file atomically.
- **append_file:** Append content to the end of an existing file (file must already exist).
- **delete_this_file:** Delete a specified file from the filesystem (irreversible, restricted to project directory).
- **edit_file:** Make selective edits using advanced pattern matching and formatting, with support for:
  - Line-based and multi-line content matching
  - Whitespace normalization and indentation preservation
  - Fuzzy matching with confidence scoring
  - Multiple simultaneous edits
  - Git-style diff output with context
- **Structured Logging:**
  - Human-readable logs to console
  - Optional structured JSON logs to file
  - Function call tracking (parameters, timing, results)
  - Automatic error context capture
  - Configurable log levels (DEBUG, INFO, WARNING, ERROR, CRITICAL)
- **Security:**
  - All paths normalized and validated to stay within project directory
  - Path traversal attacks prevented
  - Atomic writes to prevent data corruption
  - Delete operations restricted for safety

## Usage

- Runs as a local server, serving a specified project directory.
- Integrates with Claude Desktop App and other MCP-compatible AI assistants.
- Can be debugged and tested using MCP Inspector.

## Installation & Development

- Clone the repository and install dependencies via pip.
- Supports structured logging and development tooling.
- Licensed under MIT License.

## Pricing

- **Open Source:** Free to use under the MIT License.

## Tags

filesystem, file-management, ai-assistant, mcp