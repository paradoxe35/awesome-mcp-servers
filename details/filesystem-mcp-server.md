# FileSystem MCP Server

A secure Model Context Protocol (MCP) server that enables AI assistants (such as Claude) to perform file operations on the local filesystem within a specified project directory. It is designed for safe, controlled AI integration with robust security controls and path validation.

- **Source:** [GitHub - MarcusJellinghaus/mcp_server_filesystem](https://github.com/MarcusJellinghaus/mcp_server_filesystem)
- **Category:** file-management-mcp-servers
- **Tags:** filesystem, file-management, ai-integration, security
- **License:** MIT

---

## Features

- **Project Directory Restriction:** All operations are limited to a user-specified project directory; attempts to access files outside this directory are blocked.
- **List Directory:** List all files and directories within the project directory (filtered by .gitignore and excludes .git folders).
- **Read File:** Read contents of a file (relative to the project directory).
- **Save File:** Write content atomically to a file, creating or overwriting as needed.
- **Append File:** Append content to the end of an existing file.
- **Delete File:** Permanently remove a file from the filesystem (irreversible, restricted to project directory).
- **Edit File:** Selectively edit files using advanced pattern matching, with features such as:
  - Line-based and multi-line content matching
  - Whitespace normalization
  - Indentation preservation
  - Fuzzy matching with confidence scoring
  - Multiple simultaneous edits
  - Git-style diff output
- **Structured Logging:**
  - Human-readable logs to console
  - Optional structured JSON logs to file
  - Function call tracking with parameters, timing, and results
  - Automatic error context capture
  - Configurable log levels (DEBUG, INFO, WARNING, ERROR, CRITICAL)
- **Security:**
  - Path normalization and validation to prevent path traversal attacks
  - Atomic file writes to prevent corruption
  - Delete operations restricted for safety
- **Integration:**
  - Compatible with Claude Desktop and other MCP-compatible assistants
  - Can be used with MCP Inspector for debugging and development

## Installation & Usage

- Clone the repository and install with Python (see details in the [README](https://github.com/MarcusJellinghaus/mcp_server_filesystem#installation)).
- Run the server specifying the project directory and optional logging parameters.
- Integrate with Claude Desktop or test/debug with MCP Inspector.

## Pricing

- **Open Source / Free** under the MIT License. No paid plans.

## Links
- [Repository](https://github.com/MarcusJellinghaus/mcp_server_filesystem)
- [MCP Python SDK](https://github.com/MarcusJellinghaus/mcp_python_sdk)
- [MCP Python Code Checker](https://github.com/MarcusJellinghaus/mcp_python_code_checker)
