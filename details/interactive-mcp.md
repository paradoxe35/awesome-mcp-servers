# interactive-mcp

**Description:**  
interactive-mcp is a local, cross-platform MCP (Model Context Protocol) server implemented in Node.js/TypeScript. It enables interactive LLM workflows by providing tools for user prompts, chat functionality, and notifications directly within the MCP loop. This server is designed to run locally alongside MCP clients (such as Claude Desktop, VS Code), requiring access to the user's operating system for notifications and command-line prompts.

**Source:** [https://github.com/ttommyth/interactive-mcp](https://github.com/ttommyth/interactive-mcp)

**Category:** ai-integration-mcp-servers

**Tags:** interactive, chat, llm-integration, mcp, open-source

---

## Features

- **Interactive User Prompts:**
  - `request_user_input`: Asks the user a question and returns their answer. Supports predefined options.
  - Prompts can timeout (default 30 seconds, configurable).
- **OS Notifications:**
  - `message_complete_notification`: Sends simple notifications to the user's operating system.
- **Persistent Command-Line Chat:**
  - `start_intensive_chat`: Initiates a persistent command-line chat session.
  - `ask_intensive_chat`: Allows asking questions within an active chat session.
  - `stop_intensive_chat`: Closes an active chat session.
- **Customizable Tool Availability:**
  - Tools (user input, notifications, chat) can be selectively disabled via command-line options.
- **Cross-Platform Support:**
  - Designed to work with different MCP clients (e.g., Claude Desktop, Cursor, VS Code).
- **Configurable Timeout and Arguments:**
  - Timeout and disabled tools can be set via command-line or MCP client configuration.
- **Open Source & Extensible:**
  - MIT licensed, with development and contribution guidelines.
- **Developer-Friendly:**
  - Built with Node.js and TypeScript, uses pnpm for package management.
  - Includes build, lint, and format scripts for development.

## Usage Scenarios

- Interactive setup or configuration processes.
- Gathering feedback during code generation or modification.
- Clarifying instructions or confirming actions in pair programming.
- Any workflow requiring user input or confirmation during LLM operation.

## Client Integration

- Works with MCP clients such as Claude Desktop, Cursor, and VS Code.
- Configuration is done via client JSON settings, specifying the command and arguments to launch the server.
- Supports command-line options for customizing timeout and disabling tools.

## Command-Line Options

| Option              | Alias | Description                                                                 |
|---------------------|-------|-----------------------------------------------------------------------------|
| --timeout           | -t    | Sets the default timeout (in seconds) for user input prompts (default: 30s). |
| --disable-tools     | -d    | Disables specific tools/groups (comma-separated list).                       |

## License

MIT License

## Pricing

interactive-mcp is open source and free to use under the MIT License.
