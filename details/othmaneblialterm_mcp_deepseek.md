# OthmaneBlial/term_mcp_deepseek

A prototype implementation of an MCP-like server for terminal environments, using the DeepSeek API. It demonstrates Model Context Protocol (MCP) concepts by enabling AI-driven shell command execution and tool invocation via a web interface.

**Source:** [GitHub Repository](https://github.com/OthmaneBlial/term_mcp_deepseek)

## Features

- **Chat Interface:**
  - Web-based chat client (built with Flask and Tailwind CSS) for interacting with the server.
- **AI Integration:**
  - Integrates with the DeepSeek API to generate responses.
  - AI can include special instructions (lines beginning with `CMD:`) to trigger shell command execution.
- **Terminal Command Execution:**
  - Executes shell commands in a persistent Bash session via `pexpect`.
  - Returns command output to the client.
- **MCP Endpoints:**
  - `/mcp/list_tools`: Lists available tools (e.g., `write_to_terminal`, `read_terminal_output`, `send_control_character`).
  - `/mcp/call_tool`: Invokes specific tool commands on the server.
- **API Endpoints:**
  - `/chat`: Accepts POST requests with a message, processes it via DeepSeek, executes commands, and returns responses.
- **Open Source:**
  - Licensed under the MIT License.
- **Proof-of-Concept:**
  - Not fully compliant with the official MCP standard (e.g., lacks JSON-RPC support, session management, and some security features).
- **Future Improvements (Planned):**
  - JSON-RPC protocol support.
  - Real-time output streaming (SSE or WebSockets).
  - User sessions, authentication, and enhanced security.
  - Modularization of code for better maintainability.

## Requirements
- Python 3.8+
- pip
- Valid DeepSeek API key

## Category
- Code Execution Automation / MCP Servers

## Tags
- mcp
- terminal
- shell
- reference-implementation

## Pricing
- The project is open-source and free to use under the MIT License.
