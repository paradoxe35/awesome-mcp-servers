# pulumi/mcp-server

**Description:**
Pulumi MCP Server is a server implementation of the Model Context Protocol (MCP) for interacting with Pulumi via Automation and Cloud APIs. It enables programmatic access to Pulumi operations, such as deployments and retrieving stack outputs, without requiring the Pulumi CLI to be installed in the client environment. It is designed for integration with applications that use MCP servers as tools, and can be run as a Docker container or directly via Node.js.

**Source:** [https://github.com/pulumi/mcp-server](https://github.com/pulumi/mcp-server)

**Category:** cloud-devops-mcp-servers

**Tags:** pulumi, cloud, automation, mcp

---

## Features

- **MCP Protocol Support:** Implements the Model Context Protocol for standardized interoperation.
- **Pulumi Automation:** Provides programmatic access to Pulumi operations using Automation and Cloud APIs.
- **No Direct CLI Dependency:** Allows MCP clients to run Pulumi commands without needing the Pulumi CLI installed locally.
- **Docker Support:** Can be run as a Docker container to simplify setup and avoid needing Node.js or direct package installs on the host.
- **Available Commands:**
  - `preview`: Runs `pulumi preview` on a specified stack.
  - `up`: Runs `pulumi up` to deploy changes for a specified stack.
  - `stack-output`: Retrieves outputs from a specified stack after deployment.
  - `get-resource`: Fetches information about a specific Pulumi Registry resource, including inputs and outputs.
  - `list-resources`: Lists available resources within a provider package, optionally filtered by module.
- **Integration Ready:** Can be integrated into applications (e.g., via configuration in Claude desktop's MCP tools).
- **Flexible Project Access:** Supports mounting local project directories into the container for Pulumi operations requiring project files.
- **Active Development:** API and commands are experimental and may change.
- **Open Source:** Licensed under Apache-2.0.

## Pricing

No pricing information is provided; as an open source project, usage is free under the Apache-2.0 license.