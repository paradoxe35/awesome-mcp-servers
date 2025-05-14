# azure-devops-mcp

**Category:** cloud-devops-mcp-servers  
**Tags:** mcp, azure, devops, project-management

## Description
azure-devops-mcp is a reference server implementation of the Model Context Protocol (MCP) integrated with Azure DevOps. It allows AI assistants and other clients to interact with Azure DevOps resources programmatically using MCP. This implementation is provided as a Server-Sent Events (SSE) server.

## Features
- Integration with Azure DevOps via MCP
- Enables querying work items in Azure DevOps
- Supports creating tasks programmatically
- Allows searching code repositories
- Retrieves project information from Azure DevOps
- Reference implementation of an SSE server for MCP
- Configurable server port via environment variables
- Can be added to tools like Cursor using a specified SSE endpoint

## Installation & Setup
- Requires setting environment variables in a `.env` file
- Server port and endpoint can be configured

## Source Code
[GitHub Repository](https://github.com/kevinmeyvaert/azure-devops-mcp)

## Pricing
No pricing information available; the project is open source under the MIT License.