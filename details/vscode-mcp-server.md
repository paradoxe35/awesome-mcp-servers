# vscode-mcp-server

A Visual Studio Code extension that acts as a Model Context Protocol (MCP) server, exposing VS Code's editing and filesystem features to AI models and other MCP clients.

**Source:** [GitHub Repository](https://github.com/juehang/vscode-mcp-server)

## Features
- **MCP-Compliant Server**: Implements a server following the MCP protocol, enabling AI assistants (like Claude) and other tools to interact with your VS Code workspace.
- **File Tools**:
  - `list_files_code`: List files and directories in the workspace.
  - `read_file_code`: Read the contents of files.
- **Edit Tools**:
  - `create_file_code`: Create new files via VS Code's WorkspaceEdit API.
  - `replace_lines_code`: Replace specific lines in a file.
- **Diagnostics Tools**:
  - `get_diagnostics_code`: Check for warnings and errors in the workspace.
- **Symbol Tools**:
  - `search_symbols_code`: Search for symbols across the workspace.
  - `get_symbol_definition_code`: Get definition information for a symbol in a file.
- **Shell Tools**:
  - `execute_shell_command_code`: Execute shell commands in the VS Code integrated terminal with shell integration.
- **Security Note**: Can execute shell commands; use with caution and ensure the MCP client is trusted. No authentication is implemented yet.
- **Local-Only Operation**: Only works on local workspaces to avoid exposing your VS Code instance to the network.
- **Extension Settings**: Provides settings for enabling/disabling and configuring the server.
- **Integration**: Can be configured to work with Claude Desktop and other MCP clients.

## Caveats / Limitations
- Only one workspace is supported at a time.
- Authentication is not yet implemented; the MCP authentication spec is still evolving.

## License
MIT

## Pricing
No pricing information found; the extension is open source and available under the MIT License.