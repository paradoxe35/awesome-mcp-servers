# azure-mcp-server

**Description:**  
Azure MCP Server is an open-source server that implements the Model Context Protocol (MCP), enabling AI agents to securely manage, manipulate, and query cloud data resources via integration with Azure services such as Blob Storage and Cosmos DB. It allows agents to leverage Azure resources for workflows like file storage, database and logs querying, and direct CLI command execution.

**Category:** database-messaging-mcp-servers

**Source:** [Introducing the Azure MCP Server](https://devblogs.microsoft.com/azure-sdk/introducing-the-azure-mcp-server/)

**Tags:** mcp, azure, cloud-storage, database

---

## Features
- **Supports multiple Azure services:**
  - **Azure Cosmos DB (NoSQL):**
    - List Cosmos DB accounts
    - List and query databases
    - Manage containers and items
    - Execute SQL queries against containers
  - **Azure Storage:**
    - List Storage accounts
    - Manage blob containers and blobs
    - List and query Storage tables
    - Access container properties and metadata
  - **Azure Monitor (Log Analytics):**
    - List Log Analytics workspaces
    - Query logs using Kusto Query Language (KQL)
    - List available tables
    - Configure monitoring options
  - **Azure App Configuration:**
    - List App Configuration stores
    - Manage key-value pairs
    - Handle labeled configurations
    - Lock/unlock configuration settings
  - **Azure Resource Groups:**
    - List resource groups
    - Perform resource group management operations
- **Azure Tools Integration:**
  - Execute Azure CLI commands directly (full functionality, JSON output)
  - Execute Azure Developer CLI (`azd`) commands for template discovery, initialization, provisioning, and deployment
- **Agent Compatibility:**
  - Usable by any agent that supports the MCP protocol (e.g., GitHub Copilot Agent Mode, custom MCP clients)
  - Tutorials and SDKs available for Python, .NET, and Semantic Kernel
- **Open-source:**
  - Publicly available on GitHub
- **Extensibility:**
  - Designed for agentic workflows and can be integrated with development tools (e.g., VS Code extensions)

## Pricing
- **Public Preview:** No pricing information is provided; availability is currently in public preview.

## Notes
- The Azure MCP Server is currently in public preview. More features, integrations, and documentation are planned for future releases.
- Feedback, issues, and feature requests are welcomed via the GitHub repository.
