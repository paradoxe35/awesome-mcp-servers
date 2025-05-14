# mcp-server

**Description:**

MCP server for RAD Security, providing AI-powered security insights for Kubernetes and cloud environments via the Model Context Protocol.

**Source:** [https://github.com/rad-security/mcp-server](https://github.com/rad-security/mcp-server)

**Category:** cloud-devops-mcp-servers

**Tags:** mcp, security, kubernetes, cloud

---

## Features

- **Account Inventory**
  - List clusters and their details (requires authentication)
- **Containers Inventory**
  - List containers and their details (requires authentication)
- **Security Findings**
  - List and analyze security findings (requires authentication)
- **Runtime Security**
  - Get process trees of running containers (requires authentication)
  - Get runtime baselines of running containers (requires authentication)
  - Analyze process behavior of running containers (requires authentication)
- **Network Security**
  - Monitor HTTP requests (requires authentication)
  - Track network connections (requires authentication)
  - Analyze network patterns (requires authentication)
- **Identity and Access**
  - List identities (requires authentication)
  - Get identity details (requires authentication)
- **Audit**
  - List who shelled into a pod (requires authentication)
- **Cloud Security**
  - List and monitor cloud resources (requires authentication)
  - Get resource details and compliance status (requires authentication)
- **Images**
  - Get SBOMs (requires authentication)
  - List images and their vulnerabilities (requires authentication)
  - Get top vulnerable images (requires authentication)
- **Kubernetes Objects**
  - Get details of a specific Kubernetes resource (requires authentication)
  - List Kubernetes resources (requires authentication)
  - List Kubernetes resource misconfiguration policies (publicly accessible)
- **Threat Vector**
  - List threat vectors (requires authentication)
  - Get details of a specific threat vector (requires authentication)
- **CVEs**
  - List CVEs (publicly accessible)
  - Get details of a specific CVE (publicly accessible)
  - Get latest 30 CVEs (publicly accessible)

**Note:** Features marked as "requires authentication" need a valid Rad Security account and credentials. Some CVE and policy operations do not require authentication.

---

## Installation & Usage

- Install via npm: `npm install @rad-security/mcp-server`
- Requires Node.js 20.x or higher
- Can be run via Node.js, Docker, or integrated with IDEs (Cursor, Claude Desktop)

---

## License

- MIT License

---

## Pricing

No pricing information provided; open-source under MIT License.