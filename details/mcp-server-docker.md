# mcp-server-docker

Integrates Docker with MCP to manage containers, images, volumes, and networks, showcasing how MCP Servers can control containerized environments.

- **Source:** [GitHub Repository](https://github.com/ckreiling/mcp-server-docker)
- **Category:** cloud-devops-mcp-servers
- **Tags:** docker, container-management, devops, mcp

## Features

- **Natural Language Container Management:**
  - Compose Docker containers using natural language prompts.
  - The LLM (Large Language Model) interprets instructions, generates plans, and applies them interactively.
- **Remote Docker Engine Support:**
  - Connects to remote Docker engines for administration (e.g., managing public-facing websites).
- **Local Container Management:**
  - Allows local users to spin up and manage containers without direct command-line interaction.
- **Project-based Management:**
  - Keeps track of containers, volumes, and networks associated with a project name.
  - Supports resuming and cleaning up entire projects.
- **Container Introspection & Debugging:**
  - Introspect running containers.
  - View container stats (CPU, memory, etc.).
  - Fetch and tail logs from containers.
- **Volume Management:**
  - Manage persistent data using Docker volumes (list, create, remove).
- **Image Management:**
  - List, pull, push, build, and remove Docker images.
- **Network Management:**
  - List, create, and remove Docker networks.
- **Container Lifecycle Operations:**
  - List, create, run, recreate, start, stop, and remove containers.
  - Fetch container logs.
- **Safety Features:**
  - Does not support sensitive Docker options such as `--privileged` or `--cap-add/--cap-drop` for security reasons.
- **Configuration:**
  - Uses Python Docker SDK's `from_env` for flexible configuration.
- **Development Environment:**
  - Devbox support for development and reproducible environments.

## Disclaimers

- **Sensitive Data:** Do not use the tool to configure containers with sensitive information (e.g., API keys, passwords) unless the LLM is running locally.
- **Security:** Review containers created via the LLM, as Docker is not a secure sandbox and actions may impact the host.

## Pricing

No pricing information is provided; the project is open source under the GPL-3.0 license.