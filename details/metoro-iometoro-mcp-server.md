# metoro-io/metoro-mcp-server

[Source Code](https://github.com/metoro-io/metoro-mcp-server)

## Description
Metoro MCP Server is an implementation of the Model Context Protocol (MCP) that allows users to query and interact with Kubernetes environments monitored by Metoro. It serves as a bridge between LLM-powered applications (such as the Claude Desktop App) and the deep observability data collected by Metoro's eBPF-based instrumentation for Kubernetes clusters.

## Features
- **MCP Server for Kubernetes:** Exposes Metoro's Kubernetes monitoring APIs to applications via the Model Context Protocol.
- **Integration with LLM Apps:** Designed to work with LLM-powered tools (e.g., Claude Desktop App) to enable AI-driven queries and analysis of Kubernetes clusters.
- **eBPF-based Observability:** Utilizes Metoro's eBPF agents for deep, code-less instrumentation of microservices running on Kubernetes.
- **Supports Multiple Accounts:** Can be configured for both authenticated Metoro accounts and a public live demo cluster.
- **Easy Setup:** Offers quick setup with provided configuration instructions for integration with the Claude Desktop App.
- **Built with Go:** The server and its SDK are implemented in Golang.
- **Open Source:** Licensed under the MIT license.
- **Demo Cluster Available:** Allows experimentation without a Metoro account via a publicly available demo token.
- **Active Development:** Includes regular commits, releases, and support for the latest features.

## Pricing
No pricing information is provided. The project is open source and available under the MIT license.

## Category
cloud-devops-mcp-servers

## Tags
kubernetes, monitoring, cloud-native, integration