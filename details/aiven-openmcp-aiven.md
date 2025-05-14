# Aiven-Open/mcp-aiven

[Source Code](https://github.com/Aiven-Open/mcp-aiven)

## Description
Aiven MCP Server is a Model Context Protocol (MCP) server for managing and interacting with Aiven projects and services. It provides access to Aiven's PostgreSQL, Kafka, ClickHouse, Valkey, and OpenSearch services, enabling navigation and operations across multiple data services within the Aiven platform.

## Features
- List all projects on your Aiven account (`list_projects`).
- List all services in a specific Aiven project (`list_services`).
- Get details of a specific service in an Aiven project (`get_service_details`).
- Supports integration with Aiven for PostgreSQL, Apache Kafka, ClickHouse, Valkey, and OpenSearch services.
- Enables LLMs (Large Language Models) to build full stack solutions using Aiven services.
- Native support for connectors within the Aiven ecosystem.
- Can be configured for use with Claude Desktop and Cursor environments.
- Requires environment variables for API authentication (AIVEN_BASE_URL, AIVEN_TOKEN).
- Self-managed: users are responsible for deployment, updates, maintenance, and security.
- Adheres to principle of least privilege for API tokens and security best practices.

## Configuration & Usage
- Can be run locally by setting the required environment variables and using the provided commands.
- Integrates with Claude Desktop and Cursor via configuration files and command-line invocation.
- Requires user management of API tokens and credentials for secure operations.

## Security Considerations
- Users are responsible for operational management, security, and compliance of the MCP server.
- API token permissions strictly govern access and capabilities.
- Principle of least privilege should be applied to all API tokens and credentials.

## Pricing
No pricing information provided. The project is open source and licensed under the Apache-2.0 license.

## License
Apache-2.0