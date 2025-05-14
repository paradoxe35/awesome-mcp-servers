# k8s-mcp-server

**Source:** [GitHub - alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server)

**Category:** cloud-devops-mcp-servers

**Tags:** mcp, kubernetes, cloud-native, code-execution, security

---

## Overview

k8s-mcp-server is a Model Context Protocol (MCP) server designed to enable AI assistants (such as Claude) to securely execute Kubernetes CLI commands. It acts as a secure bridge between language models and Kubernetes CLI tools—including `kubectl`, `helm`, `istioctl`, and `argocd`—enabling AI-driven cluster management, troubleshooting, and deployments within a Dockerized environment.

---

## Features

- **Secure Execution Environment:** Runs Kubernetes CLI tools (`kubectl`, `helm`, `istioctl`, `argocd`) in a containerized and isolated environment.
- **Security Validation:** Implements strict command validation to prevent dangerous operations, with support for both strict and permissive security modes.
- **Extensible Tool Support:** Tool-specific handlers for each supported CLI tool, allowing for custom command preprocessing and response formatting.
- **Prompt Templates:** Pre-defined natural language templates for common Kubernetes tasks to facilitate interactions with AI assistants.
- **Configurable via Environment Variables:** Supports configuration for timeouts, output size, transport protocol, Kubernetes context, namespace, and security settings.
- **Custom Security Rules:** Allows the use of a YAML security configuration file to define custom validation rules and safe command patterns.
- **Comprehensive Testing:** Includes unit and integration tests, with support for lightweight test clusters using KWOK, Rancher Desktop, or other Kubernetes distributions.
- **Modular Architecture:** Separated components for server logic, CLI execution, security, configuration, logging, and error handling.
- **Integration with Claude Desktop:** Provides instructions and support for seamless integration with Claude Desktop for AI-driven Kubernetes management.
- **Continuous Integration:** GitHub Actions workflows for automated testing and validation.

---

## Configuration

- **Environment Variables:**
  - `K8S_MCP_TIMEOUT`: Command execution timeout (default: 300 seconds)
  - `K8S_MCP_MAX_OUTPUT`: Maximum output size (default: 100,000 characters)
  - `K8S_MCP_TRANSPORT`: Transport protocol (`stdio` or `sse`, default: `stdio`)
  - `K8S_CONTEXT`: Kubernetes context to use
  - `K8S_NAMESPACE`: Default namespace (default: `default`)
  - `K8S_MCP_SECURITY_MODE`: Security mode (`strict` or `permissive`, default: `strict`)
  - `K8S_MCP_SECURITY_CONFIG`: Path to YAML security configuration file

---

## Supported Tools and Commands

- **kubectl:** Manage Kubernetes resources
- **helm:** Manage Helm charts and releases
- **istioctl:** Manage Istio service mesh configuration
- **argocd:** Manage ArgoCD applications

---

## Security Features

- **Strict and Permissive Modes:** Choose between strict command validation or allowing all commands.
- **Customizable Security Rules:** Use a YAML config to fine-tune allowed commands and restrict potentially dangerous operations.
- **Regex-Based Validation:** Security rules can be expressed using regular expressions for granular control.

---

## Testing and Development

- **Integration Testing:** Supports testing with KWOK (Kubernetes Without Kubelet), Rancher Desktop, or any existing Kubernetes cluster.
- **Development Tools:** Includes MCP Inspector for local development, debugging, and protocol inspection.
- **Modular Codebase:** Components for server logic, CLI execution, security, configuration, and logging.

---

## License

MIT License

---

## Pricing

No pricing information provided; open-source under the MIT License.
