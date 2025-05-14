# weibaohui/kom

**Source:** [https://github.com/weibaohui/kom](https://github.com/weibaohui/kom)

**Category:** cloud-devops-mcp-servers

**Tags:** mcp, kubernetes, devops, multi-cluster, sdk

---

## Description

`kom` is a multi-cluster Kubernetes management and operations server and SDK. It provides an SDK-level abstraction of `kubectl` and `client-go`, allowing comprehensive management of both standard and custom (CRD) Kubernetes resources. It includes over 50 built-in tools for DevOps tasks and supports SQL-like queries for Kubernetes resources.

---

## Features

- **Multi-Cluster Management:** Easily register and manage multiple Kubernetes clusters, set default clusters, and switch between them.
- **MCP Server Support:** Can run as a multi-cluster MCP management server, with support for both stdio and SSE modes, suitable for integration with tools like Cursor, Claude Desktop, Windsurf, and Cherry Studio.
- **SDK-Level Abstraction:** Encapsulates `kubectl` and `client-go` usage, simplifying common operations in code.
- **Comprehensive Resource Management:** Supports creation, update, deletion, and retrieval of all standard and CRD resources.
- **SQL Query Support:** Query Kubernetes resources using SQL-like syntax (e.g., `select * from pod where ...`).
- **Cross-Namespace Operations:** List and manage resources across multiple namespaces in a single operation.
- **Chainable Call Syntax:** Fluent, chainable API for resource operations.
- **Callback Mechanism:** Register custom callbacks for various operations (get, list, create, update, patch, delete, exec, stream-exec, logs, watch) with ordering and replacement support.
- **Pod Operations:**
  - File management inside pods (upload, download, delete, list files)
  - Execute commands and stream output inside pods
  - Get pod logs
  - Port forwarding
- **Deployment Management:**
  - Scale, restart, stop, restore deployments
  - Update image tags
  - Rollout history, undo, pause, resume, and status
  - HPA listing
  - List pods managed by deployments
- **Node Management:**
  - Taint/untaint nodes
  - Cordon/uncordon/drain nodes
  - Query node resource and IP usage, pod count
  - Retrieve all node labels
- **Storage Management:**
  - Set default StorageClass
  - Get PVC/PV counts by StorageClass
- **Ingress Management:**
  - Set default IngressClass
- **YAML Operations:** Apply and delete resources via YAML definitions.
- **CRD Management:** Full CRUD and watch support for custom resources, including via unstructured objects.
- **Resource Label and Annotation:** Add/remove labels and annotations to/from resources.
- **Resource Usage Statistics:** Retrieve and display resource usage for pods and nodes (CPU, memory, etc.).
- **SQL Query Enhancements:** Supports select, where, in, not in, like, and, or, between, and ordering for resource queries.
- **Caching:** Configurable caching for high-frequency and batch queries to improve performance.
- **Integration:** Suitable for integration with third-party tools via stdio/SSE, with sample configurations provided.
- **Kubernetes Version Compatibility:** Tested with Kubernetes versions from v1.22.2 to v1.31.3.
- **MIT License:** Open source and free to use.

---

## Pricing

- **Open Source:** Licensed under MIT. No pricing; free to use.

---

## Links

- [GitHub Repository](https://github.com/weibaohui/kom)