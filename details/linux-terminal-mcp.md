# linux-terminal-mcp

An experimental MCP (Model Context Protocol) Server for the Linux terminal, supporting sandboxed execution and MCP-based automation of command-line scripts.

- **Source:** [GitHub Repository](https://github.com/weidwonder/terminal-mcp-server)
- **Category:** Code Execution Automation MCP Servers
- **Tags:** linux, terminal, sandbox, automation, mcp

---

## Features

- **MCP Server:** Provides a server that allows execution of system commands through the Model Context Protocol interface.
- **Local and Remote Execution:** Supports executing commands both locally and on remote hosts via SSH.
- **SSE Mode:** Offers Server-Sent Events (SSE) mode for remote HTTP connections, allowing remote execution and monitoring.
- **Customizable Server:** Command-line options to customize port, endpoint path, and host for the SSE server.
- **Session Management:** Supports sessions; a session name can be specified to reuse the same terminal environment for up to 20 minutes.
- **Environment Variables:** Allows specifying custom environment variables for command execution.
- **Sandboxed Execution:** Executes commands in a controlled environment.
- **AI Integration:** Designed to be integrated with AI assistants and tools (e.g., Claude Desktop, Roo Code, Cline), enabling automated command execution from AI models.
- **Flexible Configuration:** Can be configured for both local (stdio) and remote (SSE) connections.

## Usage

- Start the server in local or SSE mode with customizable options.
- Use the `execute_command` tool to run commands, specifying the command, host (optional), username (if connecting via SSH), session name (optional), and environment variables (optional).
- Integrate with AI assistants for automated workflows.

## Pricing

No pricing information provided; appears to be an open-source project.
