# azure-resource-graph-mcp-server

A Model Context Protocol (MCP) server for querying and analyzing Azure resources at scale using Azure Resource Graph. This tool enables AI assistants and developers to monitor Azure infrastructure by providing programmatic access to resource information across subscriptions.

**Source:** [GitHub Repository](https://github.com/hardik-id/azure-resource-graph-mcp-server)

## Features
- Query Azure resources using Azure Resource Graph queries
- Default query returns resource ID, name, type, and location
- Supports custom Resource Graph queries for advanced filtering and data retrieval
- Uses Azure DefaultAzureCredential for flexible authentication (supports Azure CLI, Managed Identity, Visual Studio Code credentials, and environment variables)
- Integrates with Cursor IDE and Visual Studio Code for development workflows
- Provides a `query-resources` tool with parameters for subscription ID and custom queries
- Robust error handling for client initialization, query execution, and invalid parameters
- Open source (MIT License)

## Prerequisites
- Node.js installed
- Azure subscription
- Azure CLI installed and logged in (or other Azure credentials configured)

## Environment Setup
- Requires Azure credentials (via CLI, environment variables, or managed identity)
- Environment variables supported: `AZURE_SUBSCRIPTION_ID`, `AZURE_TENANT_ID`, `AZURE_CLIENT_ID`, `AZURE_CLIENT_SECRET`

## Integration Options
- **Cursor IDE:** Configure via settings to run the MCP server as a command
- **Visual Studio Code:** Configure via settings (JSON) to integrate the server as a stdio MCP server

## Usage
- Start the server and use the `query-resources` tool to retrieve resource information
- Supports both default and custom queries

## License
MIT License

## Pricing
- Open source and free to use (MIT License)

## Tags
`mcp`, `azure`, `cloud`, `monitoring`