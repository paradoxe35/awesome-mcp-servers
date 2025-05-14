# File System Server

A secure Model Context Protocol (MCP) server for performing file system operations. It enables AI assistants like Claude and other MCP-compatible systems to safely interact with local files and directories within a specified project directory, with robust path validation and security controls.

**Source:** [GitHub Repository](https://github.com/MarcusJellinghaus/mcp_server_filesystem)

## Features

- **List Directory (`list_directory`)**: Lists all files and directories in the project directory, filtering out .gitignore patterns and .git folders.
- **Read File (`read_file`)**: Reads the contents of a specified file (relative to the project directory).
- **Save File (`save_file`)**: Atomically writes content to a file (relative to the project directory).
- **Append File (`append_file`)**: Appends content to an existing file.
- **Delete File (`delete_this_file`)**: Deletes a specified file from the filesystem (operation is irreversible and restricted to the project directory).
- **Edit File (`edit_file`)**: Makes selective edits to files using advanced pattern matching and formatting. Supports:
  - Line-based and multi-line content matching
  - Whitespace normalization with indentation preservation
  - Fuzzy matching with confidence scoring
  - Multiple simultaneous edits
  - Indentation style detection and preservation
  - Git-style diff output with context
- **Structured Logging**: Comprehensive logging system supporting both human-readable and JSON formats, with function call tracking, error context capture, and configurable log levels (DEBUG, INFO, WARNING, ERROR, CRITICAL).
- **Security**:
  - All file operations are restricted to the specified project directory
  - Prevents path traversal attacks
  - Atomic file writing to prevent data corruption
  - Delete operations are limited for safety

## Usage

- Exposes a clean API for file operations via the MCP protocol.
- Can be integrated with Claude Desktop or other MCP-compatible AI assistants.
- Flexible logging and debugging options.

## Development

- Written in Python.
- MIT License.
- Supports development and testing tools, including MCP Inspector.

## Pricing

- Open source and free to use under the MIT License.