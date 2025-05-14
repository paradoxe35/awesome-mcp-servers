# mcp-k8s

**Source:** [GitHub - silenceper/mcp-k8s](https://github.com/silenceper/mcp-k8s)

**Category:** cloud-devops-mcp-servers

**Tags:** mcp, kubernetes, cloud-native, ai-integration

## Description

mcp-k8s is an AI-driven Kubernetes Model Control Protocol (MCP) server that enables natural language interaction with any Kubernetes resource, including Custom Resource Definitions (CRDs). It allows users to manage Kubernetes clusters and resources interactively through MCP-compatible tools and LLMs.

## Features

- **Kubernetes Resource Management:**
  - Supports querying all built-in and custom Kubernetes resource types.
  - Fine-grained control for resource operations: independently enable or disable create, update, and delete operations.
  - Read operations: get resource details, list resources with filtering options.
  - Supports all Kubernetes resources, including CRDs.
  - Connects to clusters using kubeconfig.
- **Helm Support:**
  - Manage Helm releases: list, get, install, upgrade, and uninstall releases.
  - Manage Helm repositories: list, add, remove repositories.
  - Each Helm operation can be independently enabled or disabled.
- **Interaction Modes:**
  - Stdio mode (default): communicates via standard I/O streams.
  - SSE mode: exposes an HTTP endpoint for server-sent events.
  - Docker deployment support for both modes.
- **LLM Integration:**
  - Natural language interaction for resource management, batch operations, and status queries.
  - Intelligent assistant for cluster management, problem diagnosis, configuration review, and error explanation.
  - Automatic configuration generation and validation based on natural language requirements.
- **Education and Training:**
  - Interactive learning tool for Kubernetes concepts and operations.
  - Provides best practice guidance and error correction suggestions.
- **Security and Configuration:**
  - Write operations (create, update, delete) are controlled via independent switches.
  - RBAC usage to limit permissions.
  - Input validation to prevent injection attacks.
  - Helm write operations are disabled by default for safety.
- **Command-line Arguments:**
  - Extensive CLI arguments to control which operations are enabled.
  - Transport configuration (stdio or SSE), host, port, and more.
- **Integration:**
  - Easily integrates with any MCP-compatible LLM client.

## Usage Examples

- **Stdio Mode:**
  - Run as a local process communicating via stdio.
- **SSE Mode:**
  - Run as a remote service exposing HTTP SSE endpoint.
- **Docker:**
  - Deploy and run using Docker images with appropriate kubeconfig volume and port mappings.

## Architecture

- Written in Go, using mcp-go SDK, Kubernetes client-go, and Helm v3 libraries.
- Implements MCP tools for various Kubernetes and Helm operations.

## Licensing

- Licensed under the Apache-2.0 license.

## Pricing

- mcp-k8s is open source software. No pricing plans are listed; it is free to use under the Apache-2.0 license.