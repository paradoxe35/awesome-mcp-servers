# rohitg00/kubectl-mcp-server

A Model Context Protocol (MCP) server for Kubernetes, enabling AI assistants (like Claude, Cursor, Windsurf) to interact with Kubernetes clusters using natural language via the MCP protocol.

**Source:** [GitHub - rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server)

**Category:** cloud-devops-mcp-servers

**Tags:** mcp, kubernetes, cloud-native, ai-integration

---

## Features

### Core Kubernetes Operations
- Connect to a Kubernetes cluster
- List and manage pods, services, deployments, and nodes
- Create, delete, and describe pods and other resources
- Get pod logs and Kubernetes events
- Support for Helm v3 operations (install, upgrade, uninstall)
- `kubectl explain` and `api-resources` support
- Choose namespace for next commands (memory persistence)
- Port forward to pods
- Scale deployments and statefulsets
- Execute commands in containers
- Manage ConfigMaps and Secrets
- Rollback deployments to previous versions
- Ingress and NetworkPolicy management
- Context switching between clusters

### Natural Language Processing
- Process natural language queries for kubectl operations
- Context-aware commands with memory of previous operations
- Human-friendly explanations of Kubernetes concepts
- Intelligent command construction from intent
- Fallback to kubectl when specialized tools aren't available
- Mock data support for offline/testing scenarios
- Namespace-aware query handling

### Monitoring
- Cluster health monitoring
- Resource utilization tracking
- Pod status and health checks
- Event monitoring and alerting
- Node capacity and allocation analysis
- Historical performance tracking
- Resource usage statistics via `kubectl top`
- Container readiness and liveness tracking

### Security
- RBAC validation and verification
- Security context auditing
- Secure connections to Kubernetes API
- Credentials management
- Network policy assessment
- Container security scanning
- Security best practices enforcement
- Role and ClusterRole management
- ServiceAccount creation and binding
- PodSecurityPolicy analysis
- RBAC permissions auditing
- Security context validation

### Diagnostics
- Cluster diagnostics and troubleshooting
- Configuration validation
- Error analysis and recovery suggestions
- Connection status monitoring
- Log analysis and pattern detection
- Resource constraint identification
- Pod health check diagnostics
- Common error pattern identification
- Resource validation for misconfigurations
- Detailed liveness and readiness probe validation

### Advanced Features
- Multiple transport protocols support (stdio, SSE, HTTP)
- Integration with multiple AI assistants
- Extensible tool framework
- Custom resource definition (CRD) support
- Cross-namespace operations
- Batch operations on multiple resources
- Intelligent resource relationship mapping
- Error explanation with recovery suggestions
- Volume management and identification

### Architecture & Operation
- Implements the Model Context Protocol (MCP) for standardized AI-Kubernetes interaction
- MCP server handles requests from AI assistants
- Tools registry for Kubernetes operations exposed as MCP tools
- Transport layer supports stdio, SSE, and HTTP
- CLI mode and server mode supported
- Response formatter for MCP-compliant responses

### Installation
- Installable via PyPI: `pip install kubectl-mcp-tool`
- Python 3.9+, kubectl CLI, access to Kubernetes cluster required
- Supports global and local development installation
- Includes installation script for automatic configuration with supported AI assistants

### Usage
- Designed to run as an MCP server for AI tools (not a direct kubectl replacement)
- Integration guides for Claude, Cursor, and Windsurf
- Provides configuration templates for each assistant
- Example commands for listing pods, deploying apps, checking logs, port forwarding

### Development
- Includes comprehensive test suite for core, security, monitoring, NLP, diagnostics
- Modular project structure for easy contribution and extension

### Known Issues
- JSON parsing issues are currently being debugged for some AI assistants (Claude, Cursor, Windsurf)

---

## Pricing
- **Open Source**: Free to use under the MIT License. No paid plans.

---

## License
- MIT License

---

## Contributors
- Rohit Ghumare
- Ian Moroney
- Sajeeva Lakmal

---