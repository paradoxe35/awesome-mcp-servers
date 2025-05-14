# Desktop Commander MCP

[GitHub Repository](https://github.com/wonderwhy-er/DesktopCommanderMCP)  
[Official Website](https://desktopcommander.app/)

A feature-rich MCP (Model Context Protocol) server that enables Claude Desktop to execute terminal commands, manage processes, and perform advanced file system and code editing operations across desktop platforms. Implementation by wonderwhy-er.

## Features

### Terminal & Process Management
- Execute terminal commands with output streaming
- Configurable command timeouts and background execution
- List and kill system processes
- Manage long-running command sessions (start, list, terminate)
- Blacklist and unblock specific commands

### Filesystem Operations
- Read and write files (including direct image viewing for PNG, JPEG, GIF, WebP)
- Create and list directories
- Move and rename files or directories
- Search files with pattern matching
- Retrieve file metadata

### Code Editing Capabilities
- Surgical text replacements (for small changes)
- Full file rewrites (for large or complex changes)
- Multi-file editing support
- Pattern-based search & replace
- Recursive code/text search in folders using vscode-ripgrep
- Block-based search/replace format for precise edits

### Integration & Automation
- Seamless integration with Claude Desktop via MCP
- Built on top of MCP Filesystem Server, extends with terminal and advanced editing
- Automatic updates when installed via npx or Smithery
- CLI and config-file based installation options

### Platform Support
- Cross-platform (Windows, macOS, Linux)
- Ongoing improvements for Windows, Linux, WSL (Windows Subsystem for Linux), and SSH support (in progress)

### Debugging & Development
- Debug mode with Node.js inspector protocol
- Setup for local development and contribution

### Data Collection
- Collects anonymous usage data for improvement (OS info, Node/NPM versions, install method, errors)
- No personal data collected; opt-out by blocking PostHog endpoint

### Work in Progress/Upcoming
- Better configuration options (allowed paths, commands, shell env)
- Improved Windows and Linux support
- Installation troubleshooting guide
- WSL & SSH integration

## Pricing
- Open Source (MIT License)
- No extra fees; works with Claude Desktop's Pro subscription ($20/month), not API credits

## Tags
`mcp` `desktop` `code-execution` `automation` `file-management`

## Category
code-execution-automation-mcp-servers