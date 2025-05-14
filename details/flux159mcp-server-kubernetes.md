# flux159/mcp-server-kubernetes

**Category:** cloud-devops-mcp-servers  
**Tags:** mcp, kubernetes, cloud-native, typescript  
**Source:** [GitHub Repository](https://github.com/Flux159/mcp-server-kubernetes)

## Description
`flux159/mcp-server-kubernetes` is a TypeScript implementation of an MCP (Model Context Protocol) server designed to connect to and manage Kubernetes clusters. It enables automation and direct management of Kubernetes resources such as pods, deployments, services, and more, via a command interface or integration with chat clients like mcp-chat or Claude Desktop.

## Features
- Connects to any Kubernetes cluster using the current `kubectl` context
- Lists and manages Kubernetes resources:
  - List all pods, services, deployments, nodes, and namespaces
  - Create, delete, and describe pods
  - Get logs from pods (supports deployments, jobs, label selectors)
  - Get Kubernetes events from the cluster
  - Port-forward to a pod
  - Choose namespace for subsequent commands
- Helm v3 support (no Tiller required):
  - Install Helm charts (with custom values and repository support)
  - Uninstall releases
  - Upgrade existing releases
  - Namespace and version specification
- Supports `kubectl explain` and `kubectl api-resources`
- Can be used with MCP chat clients (e.g., `mcp-chat`, Claude Desktop)
- Local development and testing workflow with hot-reload and unit testing
- Advanced features and transport options (see `ADVANCED_README.md` for SSE transport)
- MIT Licensed and open source

## Requirements
- `kubectl` installed and configured with access to a Kubernetes cluster
- Valid kubeconfig file and context
- (Optional) Helm v3 installed for Helm chart management

## Pricing
This project is open source and released under the MIT license. No pricing or paid plans are associated; it is free to use.

## Resources
- [npm Package](https://www.npmjs.com/package/mcp-server-kubernetes)
- [Documentation & Advanced Usage](https://github.com/Flux159/mcp-server-kubernetes#readme)
