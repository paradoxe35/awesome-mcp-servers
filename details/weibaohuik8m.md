# weibaohui/k8m

**Mini Kubernetes AI Dashboard with Multi-Cluster Management and AI/LLM Integration**

- **Website:** [https://github.com/weibaohui/k8m](https://github.com/weibaohui/k8m)
- **Category:** Cloud DevOps MCP Servers
- **Tags:** mcp, kubernetes, devops, multi-cluster, gui

---

## Description

k8m is a lightweight, cross-platform Mini Kubernetes AI Dashboard designed to simplify cluster management. It integrates multi-cluster management, AI-powered features, a user-friendly GUI, and supports both standard and CRD Kubernetes resources. It can be deployed as a single executable file and supports various architectures (Linux, macOS, Windows, x86, ARM).

---

## Features

- **Mini and Portable:** All features in a single executable, easy to deploy and use.
- **User-Friendly GUI:** Built with Baidu AMIS for an intuitive management experience.
- **High Performance:** Backend in Golang, efficient resource usage and fast response.
- **AI-Driven:**
  - Built-in LLMs (e.g., Qwen2.5-Coder-7B, DeepSeek-R1-Distill-Qwen-7B) for code explanation, YAML translation, resource guidance, command suggestions, and log diagnosis.
  - Integrates with ChatGPT-like models, supports custom/private models (including Ollama).
  - k8s-gpt functionality for intelligent Kubernetes management in Chinese.
- **MCP Integration:**
  - Visual MCP management, supports 49+ built-in multi-cluster MCP tools (combinable to 100+ operations).
  - Acts as an MCP server for other LLM software.
  - Detailed logging of every MCP call.
  - Supports mcp.so mainstream services.
- **Fine-Grained Permissions:**
  - Multi-cluster and MCP permissions linked: LLM operations run with the caller's permissions.
  - User/group-based permissions per cluster: read-only, exec, or admin roles.
- **Multi-Cluster Management:**
  - Auto-detects clusters via kubeconfig, supports InCluster mode, and manages multiple clusters.
- **Pod Management:**
  - Browse, edit, upload, download, delete files inside pods.
  - Real-time log viewing and downloading, in-pod shell execution.
- **CRD Management:**
  - Auto-discovery and management of Custom Resource Definitions.
- **Helm Integration:**
  - Add custom Helm repositories, one-click install, upgrade, and uninstall Helm apps.
- **Cross-Platform:**
  - Runs on Linux, macOS, Windows; supports x86 and ARM architectures.
- **Open Source:**
  - MIT license, fully open, customizable, and extensible for commercial or personal use.
- **Security:**
  - JWT-based authentication, 2FA support, environment variable and CLI parameter configuration.
- **Flexible Deployment:**
  - Single binary, Docker, docker-compose, or native Kubernetes deployment (KinD, Minikube, etc.).
- **Environment Variables/CLI Options:**
  - Extensive configuration via env vars and CLI flags (port, kubeconfig, AI model, logging, etc.).

---

## Pricing

**k8m is open source and free to use under the MIT license.**

---

## Source

- [GitHub Repository](https://github.com/weibaohui/k8m)
- [Documentation](https://github.com/weibaohui/k8m#readme)
