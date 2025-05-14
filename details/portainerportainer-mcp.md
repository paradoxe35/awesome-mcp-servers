# portainer/portainer-mcp

**Description:**  
Portainer MCP is a server implementing the Model Context Protocol (MCP) for Portainer environments. It enables natural language access to Portainer instances, allowing AI assistants and tools to manage containers, perform deployment operations, and monitor infrastructure via a standardized protocol.

**Source:** [https://github.com/portainer/portainer-mcp](https://github.com/portainer/portainer-mcp)

**Category:** cloud-devops-mcp-servers

**Tags:** mcp, container-management, portainer, cloud, natural-language

---

## Features

- **Natural Language Access:** Connects AI assistants to Portainer, enabling management through natural language queries.
- **MCP Protocol Implementation:** Standardizes access to environment data and operations for LLMs and tools.
- **Portainer Resource Management:**
  - Manage users, teams, environments, and access policies.
  - List and manage environment groups (Edge Groups) and access groups (Endpoint Groups).
  - Manage Docker stacks (Edge Stacks): list, create, update, retrieve compose files.
  - Manage tags for environments.
- **Direct Docker & Kubernetes API Access:**
  - Proxy any Docker API requests (from v0.2.0).
  - Proxy any Kubernetes API requests (from v0.3.0).
- **Customizable Tools:**
  - Tool definitions are customizable via YAML files; descriptions can be modified for AI model interpretation.
  - Supports specifying custom tools file paths.
- **Read-Only Mode:**
  - Can be run in a mode that only allows read operations, preventing modifications for security.
- **Portainer Version Validation:**
  - Validates Portainer server version at startup; supports specific versions (e.g., 2.28.1, 2.29.2).
- **Pre-built Binaries:**
  - Available for Linux (amd64, arm64) and macOS (arm64).
- **Token Counting Utilities:**
  - Includes scripts to estimate token usage for tool definitions when used with LLMs.

### Supported Operations (by resource)
- **Environments:** List, update tags, update user/team access.
- **Environment Groups:** List, create, update name/environments/tags.
- **Access Groups:** List, create, update name/user/team access, add/remove environments.
- **Stacks:** List, get stack file, create, update stacks.
- **Tags:** List and create environment tags.
- **Teams:** List, create, update name, update members.
- **Users:** List, update users, get settings.
- **Docker & Kubernetes:** Proxy any API requests.

---

## Installation
- Download pre-built binaries from the [Latest Release Page](https://github.com/portainer/portainer-mcp/releases) for your OS and architecture.
- Optional: verify checksums for integrity.
- Extract and move the executable to a directory in your PATH.

---

## Pricing
No pricing information is provided; the project appears to be open source.

---

## Notes
- This project is under active development.
- Requires a Portainer administrator API token for operation.
- Tool customization and read-only options provide flexibility and security.
