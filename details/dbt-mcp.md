# dbt-mcp

[Source Code](https://github.com/dbt-labs/dbt-mcp)

## Description

dbt-mcp is an open-source MCP (Model Context Protocol) server designed for integration with dbt (data build tool). It enables interaction with dbt resources, providing metadata discovery, model information, and semantic layer querying capabilities. It works with both dbt Core and dbt Cloud environments.

## Features

### Integration with dbt
- Connects to both dbt Core and dbt Cloud installations
- Allows running commands through the local dbt Core or dbt Cloud CLI

### Model Information and Metadata Discovery
- Retrieve information about models and transformations in a dbt project
- Discovery API:
  - `get_mart_models`: Fetch all mart models
  - `get_all_models`: Fetch all models
  - `get_model_details`: Fetch details for a specific model
  - `get_model_parents`: Fetch parent models of a specific model

### Semantic Layer Querying
- Interact with the dbt Cloud Semantic Layer gateway
- Retrieve and query analytics metrics and dimensions:
  - `list_metrics`: List all defined metrics
  - `get_dimensions`: Get dimensions for specified metrics
  - `get_entities`: Get entities for specified metrics
  - `query_metrics`: Query metrics with grouping, ordering, filtering, and limiting

### dbt CLI Command Support
- `build`: Execute models, tests, snapshots, and seeds
- `compile`: Generate executable SQL from models, tests, and analyses
- `docs`: Generate documentation for the dbt project
- `ls`: List resources in the dbt project
- `parse`: Parse and validate project files for syntax
- `run`: Execute models to materialize them in the database
- `test`: Run tests to validate data and model integrity
- `show`: Run a query against the data warehouse

### Flexible Configuration
- Enable or disable CLI, Semantic Layer, and Discovery features via environment variables
- Support for multi-cell dbt Cloud configurations
- Customizable connection and authentication settings

### Client Integrations
- Can be used with MCP clients such as Claude Desktop, Cursor, and VS Code
- Example configurations provided for client setup

### Installation and Setup
- Easy installation via shell script or manual setup
- Environment variable-based configuration

## Pricing

No pricing information is provided; dbt-mcp is an open-source project.

## Tags

mcp, dbt, data-integration, metadata, data-analysis