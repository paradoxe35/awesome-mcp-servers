# adx-mcp-server

A Model Context Protocol (MCP) server for querying and analyzing Azure Data Explorer databases, designed to support time-series and analytics MCP use cases and enable AI assistants to interact with Azure Data Explorer through standardized interfaces.

**Source:** [https://github.com/pab1it0/adx-mcp-server](https://github.com/pab1it0/adx-mcp-server)

## Features
- **Execute KQL queries**: Run Kusto Query Language (KQL) queries against Azure Data Explorer databases.
- **Database discovery and exploration**:
  - List tables in the configured database
  - View table schemas
  - Sample data from tables (with optional sample size)
  - Get table statistics/details
- **Authentication support**:
  - Token credential support (Azure CLI, Managed Service Identity, etc.)
  - Workload Identity credential support for Azure Kubernetes Service (AKS)
  - Automatic fallback to DefaultAzureCredential if workload identity is not present
- **Docker containerization**: Includes Dockerfile and docker-compose setup for easy deployment and isolation.
- **Configurable interactive tools for AI assistants**: Select which tools (query execution, listing tables, schema viewing, etc.) are available to MCP clients.
- **Development container support**: Can be used as a dev container or in GitHub Codespaces for seamless development experience.
- **Comprehensive test suite**: Includes configuration validation, server functionality, error handling, and main application tests.

### Provided Tools (APIs)
- `execute_query`: Execute a KQL query against Azure Data Explorer
- `list_tables`: List all tables in the configured database
- `get_table_schema`: Get the schema for a specific table
- `sample_table_data`: Get sample data from a table

## Usage
- Configure environment variables for Azure Data Explorer cluster and database.
- Supports running directly, via Docker, or as a development container.
- Integrates with MCP clients (e.g., Claude Desktop) via configuration.

## License
MIT

## Pricing
Open-source software (no pricing; freely available under MIT license).