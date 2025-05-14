# apify/actors-mcp-server

**Description:**  
The Apify Model Context Protocol (MCP) Server provides access to over 3,000 pre-built cloud tools (Actors) for data extraction from websites, e-commerce, social media, and more. It enables interaction between AI agents/applications and Apify Actors via the open Model Context Protocol.

**Source:** [GitHub Repository](https://github.com/apify/actors-mcp-server)

**Category:** data-access-integration-mcp-servers

**Tags:** data-extraction, cloud, integration, open-source

---

## Features

- **MCP Protocol Implementation:** Exposes Apify Actors as tools via the Model Context Protocol, allowing AI agents and applications to use them for data extraction, web search, and other automation tasks.
- **Supports 3,000+ Apify Actors:** Any Apify Actor can be configured and used as a tool.
- **Flexible Deployment:**
  - Can be run as an Apify Actor on the Apify platform.
  - Can be run as a standalone local server on your machine.
- **Multiple Client Support:**
  - Works with MCP clients, such as Claude Desktop and VS Code extensions.
  - Interact via Server-Sent Events (SSE) or standard input/output (stdio).
- **Dynamic Actor Loading:** Actors can be loaded dynamically (supported in Tester MCP Client).
- **Helper Tools:** Includes tools to discover available Actors and retrieve their details.
- **Automatic Argument Handling:** LLMs can select Actors and provide input arguments automatically.
- **Actor Schema Support:** Loads Actor input schemas and exposes them as tool schemas for clients.
- **HTTP API:** Standby web server mode exposes an HTTP API for interacting with Actors.
- **Resource Roadmap:** Planned support for Apify's datasets and key-value stores as additional resources.
- **Development & Debugging:**
  - Debugging support with MCP Inspector.
  - Example clients for SSE and stdio communication.
- **Memory Limits:**
  - Each Actor limited to 4GB memory.
  - Free users have an 8GB limit (128MB allocated for Actors-MCP-Server).

## Usage
- Deploy on Apify platform or run locally.
- Configure which Actors to expose via configuration files or arguments.
- Interact programmatically via HTTP, SSE, or stdio.
- Integrate with Claude Desktop, VS Code, or other MCP-compatible clients.

## Pricing
No pricing information is provided in the repository content.

## License
Open-source software (see LICENSE.md in the repository).
