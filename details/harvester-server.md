# Harvester Server

**Category:** Cloud DevOps MCP Servers  
**Tags:** mcp, cloud, devops, kubernetes, open-source

## Description
Harvester Server is a Go-based MCP (Model Context Protocol) server designed to manage Harvester HCI clusters and Kubernetes resources. It acts as a bridge between AI assistants (like Claude Desktop and Cursor) and Harvester/Kubernetes clusters, enabling natural language interactions for cluster management. The server provides tools for handling both standard Kubernetes and Harvester-specific resources, with human-readable output formatting.

## Features
- **Go-based MCP Server:** Written in Go, enabling efficient performance and ease of deployment.
- **Cluster Management:** Manage both Harvester HCI clusters and standard Kubernetes resources.
- **Human-readable Output:** Provides clear, formatted output for easier understanding.
- **AI Integration:** Enables AI assistants such as Claude Desktop and Cursor to interact with clusters via natural language queries.
- **Resource Management:**
  - **Kubernetes Core Resources:**
    - Pods: List, Get, Delete
    - Deployments: List, Get
    - Services: List, Get
    - Namespaces: List, Get
    - Nodes: List, Get
    - Custom Resource Definitions (CRDs): List
  - **Harvester-Specific Resources:**
    - Virtual Machines: List, Get
    - Images: List
    - Volumes: List
    - Networks: List
- **Flexible Configuration:**
  - Supports in-cluster config, kubeconfig flag, KUBECONFIG env variable, or default kube config path.
- **Command-Line Flags:**
  - `--kubeconfig`: Specify kubeconfig file path
  - `--log-level`: Set logging verbosity (debug, info, warn, error, fatal, panic)
- **Installation Options:**
  - From source (build and run)
  - Go install
- **Integration Examples:**
  - Detailed instructions for connecting with Claude Desktop and Cursor, both globally and per-project.

## Pricing
No pricing information provided; the project is open-source.

## Source & More Information
[View on Playbooks.com](https://playbooks.com/mcp/starbops-harvester-hci)
[View on GitHub](https://github.com/starbops/harvester-mcp-server)