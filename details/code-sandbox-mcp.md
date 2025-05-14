# Code Sandbox MCP

A sandboxed MCP server enabling secure, multi-language code execution with resource limits and network restrictions. It provides AI applications with a safe, isolated environment for running code inside Docker containers.

## Features
- **Secure Code Execution**: Runs code within Docker containers to ensure isolation and security.
- **Multi-language Support**: Designed to execute code in multiple programming languages (based on chosen Docker images).
- **Resource Limits and Network Restrictions**: Enables fine-grained control over resources and network access for executed code.
- **Sandbox Initialization**: Tool to create new compute environments for code execution by launching containers with specified images.
- **File and Directory Management**: 
  - `copy_project`: Copy entire directories into the sandboxed file system.
  - `copy_file`: Copy single files into the sandboxed environment.
  - `write_file`: Write files directly into the sandbox.
- **Command Execution**: `sandbox_exec` allows running arbitrary commands inside the sandboxed container.
- **Graceful Container Teardown**: `sandbox_stop` stops and cleans up containers, including their volumes, with a timeout.
- **Access to Container Logs**: Provides a resource endpoint to retrieve all logs from a container as plain text.
- **Configurable for Various Platforms**: Supports configuration and installation on Linux, macOS, and Windows.
- **Integration with AI Applications**: Can be used as the code execution backend for AI tools supporting MCP servers.
- **Open Source**: Licensed under the MIT License.

## Pricing
No pricing information provided; the project is open source under the MIT License.

## Source
[https://github.com/Automata-Labs-Team/code-sandbox-mcp](https://github.com/Automata-Labs-Team/code-sandbox-mcp)

## Tags
mcp, code-execution, sandbox, multi-language