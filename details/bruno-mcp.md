# bruno-mcp

**Description:**  
bruno-mcp is an MCP (Model Context Protocol) server that enables running Bruno Collections, designed to provide integration and automation capabilities for MCP workflows, particularly for API automation. It allows LLMs or other clients to execute API tests using Bruno and receive detailed, standardized results.

**Source:** [https://github.com/hungthai1401/bruno-mcp](https://github.com/hungthai1401/bruno-mcp)

**Category:** api-integration-mcp-servers

**Tags:** mcp, bruno, api-integration, automation, workflow

---

## Features

- Execute Bruno collections using the Bruno CLI via MCP server interface
- Support for environment files to manage test contexts
- Support for specifying environment variables as key-value pairs
- Returns detailed test results, including:
  - Overall success/failure status
  - Test summary (total, passed, failed)
  - Detailed information on failures
  - Execution timings (start, completion, duration)
- Provides a standardized interface for LLMs to interact with API testing workflows
- Includes a `run-collection` tool with configurable parameters (collection path, environment file, variables)
- Returns results in structured JSON format for easy integration
- Designed for integration with Claude Desktop and other MCP-compatible clients
- Project includes scripts for building, testing, and cleaning build artifacts
- MIT licensed open source project

## Pricing

No pricing information provided. The project is open source and available under the MIT license.