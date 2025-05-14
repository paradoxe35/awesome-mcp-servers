# Awsome Kali MCP Servers

[GitHub Repository](https://github.com/ccq1/awsome-kali-mcpservers)

## Description
Awsome Kali MCP Servers is a collection of Model Context Protocol (MCP) servers tailored for Kali Linux environments. It is designed to empower AI agents and users in reverse engineering, security testing, network analysis, and automation. The servers provide a secure, sandboxed environment for executing Kali Linux security tools and scripts.

## Features
- **Network Analysis**: Includes tools for network scanning (Nmap), sniffing, and traffic analysis (Wireshark/tshark).
- **Binary Understanding**: Supports reverse engineering and function analysis with tools such as nm, objdump, and strings.
- **Automation**: Provides scripts and servers to simplify and automate repetitive security and analysis tasks.
- **Sandboxed Execution**: Runs commands in isolated Docker containers (default image: ubuntu-systemd:22.04) for secure execution.
    - Configurable memory limit (default: 2GB)
    - Configurable CPU limit (default: 1 core)
    - Configurable network mode and timeout duration
    - Bidirectional file copying between host and container
    - Automatic cleanup of container resources
- **AI Agent Integration**: Designed to integrate with and support AI-driven workflows in security and reverse engineering.
- **Extensible via FastMCP Framework**: Built on the FastMCP framework for flexible tool integration.

## Category
code-execution-automation-mcp-servers

## Tags
security, sandbox, kali-linux, code-execution, mcp

## Pricing
No pricing information provided; this appears to be an open-source project in early development.

## Status
The project is currently in early stages of development. More features, tool integrations, and documentation are planned for future updates.