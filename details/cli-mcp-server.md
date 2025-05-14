# cli-mcp-server

**Source:** [GitHub - MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server)

A secure Model Context Protocol (MCP) server for executing controlled command-line operations, with comprehensive security features for CLI environments.

---

## Features
- **Secure Command Execution**: Executes commands with strict validation.
- **Command and Flag Whitelisting**: Supports configurable whitelists for commands and flags, with an 'all' option to allow any.
- **Path Traversal Prevention**: Validates and normalizes paths to prevent unauthorized access.
- **Shell Operator Protection**: Blocks shell operators (e.g., `&&`, `|`, `>`, `>>`).
- **Execution Timeouts and Length Limits**: Enforces maximum command string length and execution timeouts.
- **Detailed Error Reporting**: Provides comprehensive error messages for security violations and failures.
- **Async Operation Support**: Supports asynchronous command execution.
- **Working Directory Restriction**: Restricts execution to a specified directory, including symlink validation.
- **Environment-based Configuration**:
    - `ALLOWED_DIR`: Required base directory for execution.
    - `ALLOWED_COMMANDS`: Comma-separated allowed commands or 'all'.
    - `ALLOWED_FLAGS`: Comma-separated allowed flags or 'all'.
    - `MAX_COMMAND_LENGTH`: Maximum command length (default 1024).
    - `COMMAND_TIMEOUT`: Timeout in seconds (default 30).
- **Available Tools**:
    - `run_command`: Executes whitelisted commands within allowed directories.
    - `show_security_rules`: Displays current security settings and restrictions.
- **Error Handling**:
    - Detailed errors for security violations, timeouts, invalid formats, path issues, and execution failures.
- **Development Features**:
    - Python 3.10+ support.
    - Easy build and publish commands.
    - Integrated debugging with MCP Inspector.
- **MIT License**

---

## Pricing
- No pricing information provided. The project is open-source and available under the MIT license.

---

## Tags
`mcp` `cli` `code-execution` `security`