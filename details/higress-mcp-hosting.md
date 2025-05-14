# higress-mcp-hosting

A hosting solution for MCP (Model Context Protocol) servers within the Higress API gateway. Designed to provide enterprise-grade centralized management, security, and operational features for MCP deployments.

**Source:** [Higress Blog: Remote MCP Server Hosting Solution](https://higress.ai/blog/higress-opensource-remote-mcp-server-hosting-solution)

## Category
cloud-devops-mcp-servers

## Tags
mcp, higress, gateway, hosting, enterprise

## Features
- **Centralized Hosting for MCP Servers:** Deploy and manage MCP servers in the cloud via the Higress API gateway.
- **Full Protocol Support:** Supports both 20241105 and 20250326 versions of the MCP protocol, including POST+SSE and Streamable HTTP modes; native WebSocket support for real-time, bidirectional communication.
- **Authentication & Authorization:** Offers unified OAuth2 authentication and fine-grained access control, eliminating the need for custom authentication logic.
- **Rate Limiting:** Fine-grained, plugin-based rate limiting per user or tool to prevent resource abuse and service overload.
- **Audit Logging:** Comprehensive logging of all tool invocations to meet compliance needs and support security analysis.
- **Observability:** Built-in integration with Prometheus and OTel for metrics, monitoring, and distributed tracing of MCP services.
- **Resilience & Scalability:** Based on Kubernetes for auto-scaling and high availability; supports grey releases and A/B testing for safe updates.
- **Flexible Server Integration:** Three modes to connect MCP servers:
    - Built-in (via Wasm plugins inside Higress)
    - Proxy to external MCP services
    - Dynamic discovery via service registries like Nacos
- **Wasm-based Extensibility:** Add new MCP servers using WebAssembly plugins, with support for multiple languages (Go SDK available), secure sandboxing, and hot updates.
- **Enterprise Features:**
    - 99.99% SLA for enterprise customers
    - Compliance certifications for regulated industries (e.g., finance, healthcare)
    - Managed service marketplace for MCP servers (public and private options)
- **Easy Deployment:** Provides Helm charts for one-click deployment and simplified maintenance.
- **Unified Protocol Bridging:** Can bridge different MCP protocol versions and convert between MCP and REST/Dubbo.
- **Community and Marketplace:** Open MCP marketplace for easy access and deployment of MCP servers; community contribution and review mechanisms.

## Pricing
No explicit pricing or plan details are provided in the source content. The solution includes both open-source community options and enterprise offerings (with SLAs and compliance), but specific pricing tiers or costs are not listed.
