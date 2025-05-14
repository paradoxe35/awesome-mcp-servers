# mcp-openapi

**Source:** [https://github.com/ReAPI-com/mcp-openapi](https://github.com/ReAPI-com/mcp-openapi)

## Description

`mcp-openapi` is an open-source Model Context Protocol (MCP) server that loads and serves multiple OpenAPI specifications to enable LLM-powered IDE integrations. It acts as a bridge between your local OpenAPI specs and LLM-powered development tools such as Cursor and other code editors, providing comprehensive API context for code generation, explanation, and mock data creation.

## Features

- **Load Multiple OpenAPI Specifications**: Loads OpenAPI 3.x specs (JSON/YAML) from a directory, supporting both .json, .yaml, and .yml files.
- **API Catalog**: Maintains a catalog of all available APIs, operations, and schemas.
- **MCP Protocol**: Exposes API operations and schemas through the MCP protocol for IDE integrations.
- **LLM Integration**: Enables LLMs to understand and work with APIs directly in the IDE for intelligent code completion, API-aware code snippets, and integration assistance.
- **Dereferenced Schemas**: Supports full dereferencing of schemas for a complete API context.
- **Custom Specification IDs**: Allows setting custom `x-spec-id` fields for distinguishing between multiple specs with overlapping paths, schema names, or operation IDs.
- **Automatic Discovery**: Scans the specified directory for all valid OpenAPI spec files and auto-discovers them.
- **Configurable Integration**: Supports both project-specific and global configuration for integration with Cursor IDE.
- **Catalog Refresh**: Provides tools to refresh the API catalog when new specifications are added.
- **Search and Query Tools**:
  - Refresh the API catalog
  - Get the full API catalog
  - Search for operations and schemas across all specs or within a specific spec
  - Load operation details by operationId or by path and method
  - Load schema details by schema name
- **Example Prompts**: Offers example prompts for API discovery, code generation, mock data, validation, and more within Cursor IDE.
- **Roadmap**:
  - Semantic search for natural language API queries
  - Remote specification sync
  - Code template generation for LLMs
  - Enhanced community contribution support

## Pricing

- **Open Source**: Licensed under the MIT license. Free to use and modify.

## Category

`api-integration-mcp-servers`

## Tags

openapi, api-integration, llm, documentation