# Kubernetes MCP Server

**Category:** Cloud DevOps MCP Servers  
**Tags:** kubernetes, cloud-native, devops, monitoring

## Description
Kubernetes MCP Server is a solution that enables LLMs to manage, monitor, and interact with Kubernetes clusters, supporting AI-assisted cloud infrastructure management. It connects to a Kubernetes cluster and allows command execution via CLI or integration with tools like Claude Desktop and mcp-chat.

## Features
- Connect to a Kubernetes cluster using the current kubectl context
- List all pods, services, deployments, nodes, and namespaces in the cluster
- Create, delete, and describe pods
- Retrieve logs from pods (supports deployments, jobs, and label selectors)
- Support for Helm v3:
  - Install Helm charts with custom values
  - Uninstall releases
  - Upgrade existing releases
  - Namespace and version specification support
  - Support for custom repositories
- `kubectl explain` and `kubectl api-resources` command support
- Fetch Kubernetes events from the cluster
- Port forwarding to pods
- Choose namespace for subsequent commands (command memory)
- CLI integration via mcp-chat or Claude Desktop
- Local development support with hot reload, unit tests, and build scripts
- SSE transport for advanced integrations

## Architecture
- Uses a request/response flow between client, transport layer, server, handler, Kubernetes manager, and the Kubernetes API
- Supports both tool operations (like pod management) and resource queries via a modular handler design

## Requirements
- kubectl installed and configured with access to a Kubernetes cluster
- Valid kubeconfig file with contexts
- Helm v3 installed (optional if not using Helm features)

## License
MIT

## Pricing
No pricing information provided. The project is open source and available under the MIT license.

## Source
[GitHub Repository](https://github.com/Flux159/mcp-server-kubernetes)
[Package on npm](https://www.npmjs.com/package/mcp-server-kubernetes)