# manusa/Kubernetes MCP Server

A powerful and flexible Model Context Protocol (MCP) server for Kubernetes and OpenShift, supporting CRUD operations for any Kubernetes resource and specialized cluster interaction tools.

**Source:** [https://github.com/manusa/kubernetes-mcp-server](https://github.com/manusa/kubernetes-mcp-server)

## Features

- **Configuration Management:**
  - Automatically detects changes in Kubernetes configuration and updates the MCP server.
  - Supports viewing and managing current Kubernetes `.kube/config` or in-cluster configuration.

- **Generic Kubernetes Resource Operations:**
  - Perform CRUD operations (Create/Update, Get, List, Delete) on any Kubernetes or OpenShift resource.
  - No external dependencies (like kubectl or helm) are required; works with native binaries.

- **Pod-Specific Operations:**
  - List pods across all or specific namespaces.
  - Get, delete, and show logs for a pod by name and namespace.
  - Exec into a pod and run commands; specify container if needed.
  - Run a container image in a pod with optional port exposure.

- **Namespace and Event Management:**
  - List all Kubernetes namespaces.
  - View Kubernetes events across all or specific namespaces.

- **OpenShift Project Support:**
  - List OpenShift projects.

- **Resource Management Tools:**
  - Create or update any resource via YAML or JSON (supports v1 Pod, Service, Node, apps/v1 Deployment, networking.k8s.io/v1 Ingress, etc.).
  - Delete resources by apiVersion, kind, name, and (optionally) namespace.
  - Get single resources or list multiple resources by type and namespace.

- **Configuration Options:**
  - `--sse-port`: Run server in Server-Sent Events (SSE) mode on specified port.
  - `--log-level`: Set logging level (0-9).
  - `--kubeconfig`: Specify path to Kubernetes config file.

- **Available as:**
  - npx/Node.js package.
  - Python/uvx executable.
  - Standalone binary release.

## Tools (API/CLI operations)

- `configuration_view`: Retrieve kubeconfig YAML (minified or full).
- `events_list`: List Kubernetes events (optionally by namespace).
- `namespaces_list`: List all namespaces.
- `pods_delete`: Delete pod by name and namespace.
- `pods_exec`: Exec command in pod/container.
- `pods_get`: Get pod by name and namespace.
- `pods_list`: List all pods.
- `pods_list_in_namespace`: List pods in a specific namespace.
- `pods_log`: Get pod logs (optionally by container).
- `pods_run`: Run a pod with specified image and options.
- `projects_list`: List OpenShift projects.
- `resources_create_or_update`: Create/update a resource from YAML/JSON.
- `resources_delete`: Delete a resource by apiVersion, kind, name, and namespace.
- `resources_get`: Get a resource by apiVersion, kind, name, and namespace.
- `resources_list`: List resources by apiVersion, kind, and (optionally) namespace.

## Pricing

No pricing information provided. The project is open-source and licensed under Apache-2.0.

## Tags

`mcp`, `kubernetes`, `cloud-native`, `devops`