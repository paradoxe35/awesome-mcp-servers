# thunderboltsid/mcp-nutanix

**Description:**
A Go-based Model Context Protocol (MCP) server for interfacing with Nutanix Prism Central resources, enabling cloud and on-premises management via MCP. This project is experimental and not officially supported by Nutanix.

**Source:** [GitHub - thunderboltsid/mcp-nutanix](https://github.com/thunderboltsid/mcp-nutanix)

**Category:** cloud-devops-mcp-servers

**Tags:** mcp, nutanix, cloud, golang

---

## Features
- **Connects to Nutanix Prism Central:** Authenticate and connect to a Prism Central instance using user credentials.
- **Resource Listing:** List various Nutanix Prism Central resources, including:
  - Virtual Machines (VMs)
  - Clusters
  - Hosts
  - Images
  - Subnets
- **Resource Details via URI:** Retrieve detailed information for specific resources using URI-based access (e.g., `vm://{uuid}`).
- **LLM Integration:** Enables Large Language Models to interact with Nutanix Prism Central resources via MCP protocol.
- **Implements MCP in Go:** Built using the MCP Go library and Prism Go Client.
- **JSON Responses:** Returns resource lists and details in JSON format for easy parsing and analysis.
- **Code Generation:** Uses code generation for resource and tool handlers (via `make generate`).
- **Project Structure:** Organized with internal packages for client handling, code generation, JSON helpers, prompts, resources, and tools.
- **Experimental:** Intended for exploration and learning; not suitable for production use.

### Limitations
- Response size is limited by the MCP protocol.
- Large resources may cause errors due to response size limits.
- No pagination support.
- Read-only access (no create/update/delete operations).

## Pricing
- **Free and Open Source:** Licensed under the MIT License.

---

**Disclaimer:** This project is experimental, not an official Nutanix product, and is provided as-is with no warranties.