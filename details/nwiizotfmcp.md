# nwiizo/tfmcp

A command-line tool (CLI) and Model Context Protocol (MCP) server that enables AI assistants to manage and operate Terraform environments.

**Source:** [https://github.com/nwiizo/tfmcp](https://github.com/nwiizo/tfmcp)

---

## Features

- **Terraform Integration**: Deep integration with the Terraform CLI for analyzing and executing operations.
- **MCP Server Capabilities**: Runs as a Model Context Protocol server, allowing AI assistants (such as Claude Desktop) to access and manage Terraform projects.
- **Reads Terraform Configurations**: Can read and interpret Terraform configuration files.
- **Analyzes Plans**: Analyzes Terraform plan outputs to provide insight into infrastructure changes.
- **Applies Configurations**: Executes Terraform apply commands to provision or update infrastructure.
- **Manages State**: Manages Terraform state files.
- **Automatic Setup**: Automatically creates sample Terraform projects if none exist, for a smoother initial experience.
- **Claude Desktop Integration**: Seamless integration with Claude Desktop as an AI assistant.
- **Core MCP Methods**: Implements essential MCP methods, including resources/list and prompts/list.
- **Dynamic Project Directory Switching**: Ability to change the active Terraform project directory without restarting the service.
- **Logging and Troubleshooting**: Logs available for diagnostics, with support for different log levels via environment variables.
- **Demo Mode**: Special mode with extra safety features for demonstrations.
- **Performance**: High-speed processing powered by Rust.
- **Security Considerations**: Executes Terraform commands on behalf of the user; recommends proper IAM and reviewing plans before applying.

### Roadmap / Upcoming Features
- Enhanced parsing and analysis of Terraform configs, plans, and state
- Multi-environment and workspace support
- Security enhancements (authentication, authorization)
- Expanded MCP protocol support
- Interactive terminal UI
- Cloud cost estimation
- Performance optimizations
- Support for additional AI assistants
- Plugin system
- Comprehensive testing framework

---

## Requirements
- Rust (edition 2021)
- Terraform CLI installed and in `PATH`
- (For AI integration) Claude Desktop

---

## Installation
- Via Cargo: `cargo install tfmcp`
- Or clone and build from source

---

## License
MIT License

---

## Pricing
No pricing information provided; open source and free to use as per the MIT license.

---

## Tags
mcp, terraform, devops, automation