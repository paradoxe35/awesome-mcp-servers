# docker-mcp

A Model Context Protocol (MCP) server for Docker, enabling seamless container and compose stack management through Claude AI.

- **Source:** [https://github.com/QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp)
- **Category:** cloud-devops-mcp-servers
- **Tags:** mcp, docker, container-management, cloud, ai-integration
- **License:** MIT

## Features
- **Container creation and instantiation**: Supports creating standalone Docker containers with configurable image, name, ports, and environment variables.
- **Docker Compose stack deployment**: Deploys Docker Compose projects by providing YAML definitions and project names.
- **Container logs retrieval**: Fetches logs from specific containers for monitoring and debugging.
- **Container listing and status monitoring**: Lists all Docker containers and their statuses.
- **Integration with Claude AI**: Designed to work with Claude Desktop via MCP for AI-driven workflows.
- **Development and Production configurations**: Provides configuration templates for both local development and production deployments.
- **Debugging support**: Includes MCP Inspector integration for debugging and inspection.
- **Tooling**: Offers CLI tools for create-container, deploy-compose, get-logs, and list-containers operations.

## Limitations
- No built-in environment variable support for containers (must be specified manually per container).
- No volume management.
- No network management.
- No container health checks.
- No container restart policies.
- No container resource limits.

## Installation & Requirements
- **Prerequisites:**
  - UV (package manager)
  - Python 3.12+
  - Docker Desktop or Docker Engine
  - Claude Desktop
- **Installation:**
  - Via Smithery CLI: `npx @smithery/cli install docker-mcp --client claude`
  - Manual setup: Clone the repo, set up a Python virtual environment, install dependencies with `uv sync`.

## Usage
- Add server configuration to Claude Desktop config files for integration.
- Provides JSON-based configuration for both development and production environments.

## License
MIT License

## Authors
- Alex Andru (@QuantGeekDev) - Initial work, Core contributor
- Ali Sadykov (@md-archive) - Initial work, Core contributor

## Pricing
- **Free and open source** (MIT License)