# higress-mcp-server-hosting

**Category:** cloud-devops-mcp-servers  
**Tags:** mcp, higress, gateway, wasm, hosting  
**Source:** [GitHub - alibaba/higress](https://github.com/alibaba/higress)

## Description
Higress is a cloud-native API gateway based on Istio and Envoy, extendable via WASM plugins. It provides robust MCP (Model Context Protocol) server hosting and seamless protocol integration, enabling AI agents and applications to easily call various tools and services.

## Features
- **MCP Server Hosting:**
  - Hosts MCP Servers (AI-friendly APIs) via plugin mechanisms.
  - Unified authentication and authorization for tool calls.
  - Fine-grained rate limiting to protect against abuse and resource exhaustion.
  - Comprehensive audit logs of all tool call behaviors.
  - Rich observability for monitoring tool call performance and health.
  - Simplified deployment and management through plugins; supports quick addition of new MCP Servers.
  - Dynamic, traffic-lossless updates of MCP Server logic using Envoy and WASM plugin dynamic update mechanisms.
- **API Gateway Capabilities:**
  - Extensible with WASM plugins written in Go, Rust, or JS.
  - Dozens of ready-to-use general-purpose plugins (traffic management, security, etc.).
  - Out-of-the-box console UI for management.
  - High availability (production-grade, 99.99% SLA in Alibaba Cloud).
  - Streaming processing for request/response bodies, optimized for high-bandwidth AI scenarios.
  - Deep integration with microservice registries (Nacos, ZooKeeper, Consul, Eureka).
  - Security gateway features: WAF, key-auth, hmac-auth, jwt-auth, basic-auth, oidc, and more.
  - Kubernetes ingress controller compatibility.
  - Supports automatic certificate management via Let's Encrypt.
- **Developer & Operations:**
  - Easy local start via Docker or Helm for Kubernetes.
  - Hot updates for plugins and configurations with no traffic disruption.
  - Sandbox isolation for WASM plugins, multi-language support, independent plugin upgrades.

## Pricing
No pricing information is provided; Higress is open-source and available under the Apache-2.0 license.
