# Azuredevops MCP

[GitHub Repository](https://github.com/RyanCardin15/azuredevops-mcp)

## Description
Azuredevops MCP is a Model Context Protocol (MCP) server that provides an API for interacting with Azure DevOps services. It enables management and automation of work items, repositories, boards, sprints, and other DevOps resources, supporting both Azure DevOps Services (cloud) and Azure DevOps Server (on-premises). It is designed for integration with AI assistants and other tools.

## Features
- **API for Azure DevOps**: Provides a convenient API for managing Azure DevOps resources.
- **Tool Categories**:
  - Work Item Tools (list, create, update, etc.)
  - Boards & Sprints Tools
  - Project Tools
  - Git Tools (repositories, pull requests, etc.)
  - Testing Capabilities Tools
  - DevSecOps Tools
  - Artifact Management Tools
  - AI-Assisted Development Tools
- **Authentication**:
  - Supports multiple authentication methods: Personal Access Token (PAT), Entra ID (DefaultAzureCredential), NTLM, and Basic Auth.
- **Deployment**:
  - Supports both Azure DevOps Services (cloud) and Azure DevOps Server (on-premises).
  - Can be configured via environment variables (with examples provided for both cloud and on-premises).
- **Tool Filtering**: The `ALLOWED_TOOLS` environment variable allows restricting which tool methods are available.
- **Tool Registration**: Tools must be explicitly registered; documentation is provided for registering additional tools.
- **Service and Tools Layer**: Clear separation between direct API communication (services) and MCP protocol interface (tools).
- **Customizable**: Environment variables allow flexibility in configuration and deployment.
- **Docker Support**: Dockerfile included for containerized deployment.
- **TypeScript Codebase**: Built with TypeScript, providing type safety and maintainability.

## Installation
- Can be installed via Smithery for Claude Desktop or manually by cloning the repository.
- Requires setup of environment variables and dependencies.
- Supports both cloud and on-premises Azure DevOps configurations.

## Usage
- Interact with the MCP server via the MCP protocol.
- Example operations include listing/creating work items, listing repositories, and creating pull requests.
- Tools can be enabled/disabled as needed via configuration.

## Configuration
- Environment variables control server behavior, authentication, and tool access.
- Detailed guide provided in the repository for configuring both cloud and on-premises deployments.

## Pricing
No pricing information provided; this appears to be an open-source project.

## Tags
`azure` `devops` `project-management` `api-integration`

## Category
Project Management MCP Servers

## Source
[https://github.com/RyanCardin15/azuredevops-mcp](https://github.com/RyanCardin15/azuredevops-mcp)