# Container MCP

[GitHub Repository](https://github.com/54rt1n/container-mcp)

## Overview
Container MCP is a secure, container-based implementation of the Model Context Protocol (MCP) designed to provide sandboxed environments for code execution, command running, file operations, and web interactions. It is intended to be used by large language models and other automation systems to safely execute potentially untrusted operations in an isolated manner.

## Features
- **Multi-layered Security**: Implements several layers of isolation to protect the host system from harmful operations.
- **MCP Protocol Implementation**: Exposes its capabilities as MCP protocol tools for easy integration with AI and automation systems.
- **Domain-Specific Managers**: Modular architecture with managers for system, file, and web operations, each following consistent security and design patterns.
- **Configurable Environment**: All managers and environments can be customized via environment variables.

### Available Tools
- **System Operations**
  - `system_run_command`: Execute bash commands in a secure sandbox.
  - `system_run_python`: Execute Python code in a secure sandbox.
  - `system_env_var`: Get environment variable values.
- **File Operations**
  - `file_read`: Safely read file contents.
  - `file_write`: Safely write contents to files.
  - `file_list`: List directory contents safely.
  - `file_delete`: Delete files safely.
  - `file_move`: Move or rename files safely.
- **Web Operations**
  - `web_search`: Use a search engine to find information on the web.
  - `web_scrape`: Scrape content from a specific URL.
  - `web_browse`: Interactively browse websites using Playwright.

### Execution Environments
- **Container Environment**: Runs inside Podman or Docker containers for core isolation.
- **Bash Execution Environment**: Isolated bash shell with restricted commands.
- **Python Execution Environment**: Secure environment for running Python code.
- **File System Environment**: Manages file access within the sandbox.
- **Web Environment**: Controls and restricts access to external web resources.

### Security Measures
- Multiple isolation layers (containerization, apparmor, resource constraints)
- Restricted access to host files and network
- Modular managers with strict boundaries

## Configuration
- Fully configurable via environment variables for each manager (server, bash, python, file, web)

## Installation
- Can be installed and run via provided scripts or manual setup using containers (Podman/Docker)
- Example usage and quick start scripts available in the repository

## License
- Apache License 2.0

## Pricing
No pricing information is provided; the project is open-source under the Apache License 2.0.