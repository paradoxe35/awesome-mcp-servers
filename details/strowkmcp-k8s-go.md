# strowk/mcp-k8s-go

**Source:** [https://github.com/strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go)

**Category:** cloud-devops-mcp-servers  
**Tags:** mcp, kubernetes, automation, golang

---

## Description
MCP K8S Go is a Go-based MCP (Model Context Protocol) server that connects to Kubernetes clusters, enabling management and automation of Kubernetes operations via the MCP protocol.

---

## Features
- **Kubernetes Context Management**: Reads and manages K8S contexts from kubeconfig.
- **Resource Listing Tools**:
   - List Kubernetes contexts (`list-k8s-contexts`).
   - List namespaces within a context (`list-k8s-namespaces`).
   - List nodes within a context (`list-k8s-nodes`).
   - List resources (pods, services, deployments, etc.) in a context and namespace (`list-k8s-resources`).
   - Custom mappings for common K8s resources (pods, services, deployments).
- **Resource Access Tools**:
   - Retrieve specific resource details (`get-k8s-resource`).
   - List cluster events in a context and namespace (`list-k8s-events`).
   - Fetch logs for a specific pod (`get-k8s-pod-logs`).
- **Prompt Shortcuts**:
   - List namespaces and pods with conversational prompts.
- **Integration with Claude Desktop**: Allows attaching K8S contexts as resources in Claude Desktop, querying pods, events, and logs via conversational interface.
- **Flexible Installation Options**:
   - Install via Smithery, mcp-get, npm (prebuilt), GitHub releases (binary), or build from source (Go).
- **Environment Variables**:
   - Supports `KUBECONFIG` for specifying the path to your Kubernetes configuration file (defaults to `~/.kube/config`).

---

## Installation Options
- **Smithery**: `npx -y @smithery/cli install @strowk/mcp-k8s --client claude`
- **mcp-get**: `npx @michaellatman/mcp-get@latest install @strowk/mcp-k8s`
- **NPM (prebuilt)**: `npm install -g @strowk/mcp-k8s`
- **GitHub Releases**: Download prebuilt binaries from [GitHub releases](https://github.com/strowk/mcp-k8s-go/releases)
- **Source Build**: `go get github.com/strowk/mcp-k8s-go && go install github.com/strowk/mcp-k8s-go`

---

## Licensing
- MIT License

---

## Pricing
- Open source, no pricing information; free to use under the MIT License.
