# octomind-mcp

An MCP server for Octomind tools, resources, and prompts. It enables AI agents to create and run fully managed Octomind end-to-end (e2e) tests from your codebase or external sources, supporting advanced automated testing workflows.

## Features
- **E2E Test Management**: Create, execute, and manage end-to-end tests using Octomind tools.
- **Auto-Fix Support**: Platform includes capabilities for test auto-fixing.
- **Integration with Local Environments**: Use Octomind tools directly in your local development environment.
- **API Key Authentication**: Requires API key for secure access to Octomind API.
- **Configurable API Endpoints**: Supports custom API endpoints and logging via environment variables.
- **Logging**: Optional logging features with configurable log file and log level.
- **Implemented Tools:**
  - `search`: Search Octomind documentation for a given query.
  - `getTestCase`: Retrieve a test case by target and test case ID.
  - `executeTests`: Trigger test execution on a specified URL.
  - `getEnvironments`: List environments for a test target.
  - `createEnvironment`: Create a new environment for a test target.
  - `updateEnvironment`: Update an existing environment.
  - `deleteEnvironment`: Delete an environment.
  - `getTestReports`: Retrieve all test reports for a test target.
  - `getTestReport`: Get a specific test report by ID.
  - `discovery`: Create a test case from a description or prompt.
  - `getPrivateLocations`: List all private locations for the organization.
  - `getVersion`: Retrieve the current version of the MCP server.
- **Client Configuration Snippets**: Provides configuration examples for Claude Desktop, Cursor, Windsurf, and others.
- **Installation via Smithery**: Supports automated installation for some clients using Smithery CLI.
- **Open Source**: Licensed under the MIT license.

## Installation
- Installable via npm (`npx @octomind/octomind-mcp`) or through Smithery for supported clients.
- Requires configuration of environment variables: `APIKEY`, `OCTOMIND_API_URL`, `LOG_FILENAME`, and `LOG_LEVEL`.
- Configuration snippets available for common clients in the documentation.

## Pricing
No pricing information provided. The MCP server is open source under the MIT license.

## Links
- [Source Code & Documentation](https://github.com/OctoMind-dev/octomind-mcp)