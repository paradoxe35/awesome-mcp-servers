# g0t4/mcp-server-commands

[Source Code](https://github.com/g0t4/mcp-server-commands)

## Description
A general-purpose Model Context Protocol (MCP) server that can execute any command with `run_command` and `run_script` tools, demonstrating flexible server capabilities under the MCP standard. This server is designed for automation and integration with LLMs, such as via the Claude Desktop app.

## Features
- **run_command Tool:**
  - Execute arbitrary shell commands (e.g., `hostname`, `ls -al`, `echo "hello world"`).
  - Returns both STDOUT and STDERR as text.
- **run_script Tool:**
  - Run scripts in various interpreters (e.g., fish, bash, zsh, python).
  - The script is passed over STDIN, making it suitable for letting LLMs run generated code.
  - Supports creative uses (e.g., using `cat` as an interpreter to create files).
- **Prompts Integration:**
  - Prompts can be included in chat history for integration with tools like Zed's slash commands.
  - Can generate prompt messages with command outputs.
- **Installation & Usage:**
  - Available as an npm package (`mcp-server-commands`).
  - Can be configured for Claude Desktop app on macOS and Windows.
  - Supports both npm-based and local builds.
- **Logging:**
  - Logs are written to STDERR and can be made verbose with a flag.
  - Claude Desktop writes logs to a dedicated file.
- **Debugging:**
  - MCP Inspector tool available via `npm run inspector` to provide debugging tools in the browser.
- **Open Source:**
  - Licensed under the MIT license.
  - Written in JavaScript and TypeScript.

## Pricing
- Open source (MIT license); free to use.

## Tags
`command-execution`, `automation`, `mcp`, `open-source`