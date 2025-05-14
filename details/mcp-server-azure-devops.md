# mcp-server-azure-devops

**Source:** [GitHub - Tiberriver256/mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops)

**Category:** cloud-devops-mcp-servers

**Tags:** mcp, azure, devops, repository-management

---

## Overview

`mcp-server-azure-devops` is a Model Context Protocol (MCP) server implementation for Azure DevOps. It allows AI assistants (such as Claude) to interact with Azure DevOps APIs through a standardized protocol, enabling secure access and management of Azure DevOps resources including projects, repositories, work items, and pipelines.

---

## Features

- **Implements MCP for Azure DevOps:** Acts as a bridge between AI models and Azure DevOps APIs.
- **Resource Management:**
  - Access and manage projects, work items, repositories, pull requests, branches, and pipelines.
  - Create and update work items, branches, and pull requests.
- **Workflow Automation:** Execute common DevOps workflows through natural language interfaces.
- **Multiple Authentication Methods:**
  - Personal Access Token (PAT)
  - Azure Identity (DefaultAzureCredential)
  - Azure CLI
- **Configurable via Environment Variables:**
  - Supports organization URL, authentication method, PAT, default project, API version, Azure AD credentials, and logging level.
- **Modular Tool Handlers:** Each Azure DevOps operation is provided as a modular tool handler.
- **Integration with AI Assistants:** Designed for use with AI tools like Claude Desktop and Cursor AI.
- **Core Tools Provided:**
  - Navigation: `list_organizations`, `list_projects`, `list_repositories`
  - Project tools: `get_project`
  - Repository tools: `get_repository`
  - Work item tools: `get_work_item`, `create_work_item`
- **Extensible:** Modular architecture for adding more tools and handlers.
- **Open Source:** Licensed under MIT.

---

## Authentication Methods

- **PAT (Personal Access Token):** Simple token-based authentication.
- **Azure Identity:** Uses Azure Identity SDK for flexible authentication.
- **Azure CLI:** Uses the credentials from Azure CLI login.
- **AAD (Azure Active Directory) Support:** Environment variables for tenant ID, client ID, and client secret.

---

## Environment Variables

- `AZURE_DEVOPS_AUTH_METHOD`: Authentication method (pat, azure-identity, azure-cli)
- `AZURE_DEVOPS_ORG_URL`: Full URL to Azure DevOps organization
- `AZURE_DEVOPS_PAT`: Personal Access Token (for PAT auth)
- `AZURE_DEVOPS_DEFAULT_PROJECT`: Default project
- `AZURE_DEVOPS_API_VERSION`: API version
- `AZURE_AD_TENANT_ID`, `AZURE_AD_CLIENT_ID`, `AZURE_AD_CLIENT_SECRET`: For AAD auth
- `LOG_LEVEL`: Logging level

---

## License

MIT

---

## Pricing

No pricing information provided; the project is open source under the MIT license.