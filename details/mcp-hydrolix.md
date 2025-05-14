# mcp-hydrolix

Hydrolix MCP server for time-series datalake integration, supporting schema exploration and query capabilities for LLM workflows.

- **Source:** [GitHub Repository](https://github.com/hydrolix/mcp-hydrolix)
- **License:** Apache-2.0

## Features

- Provides an MCP (Model Control Protocol) server for Hydrolix time-series datalake.
- Allows integration with LLM (Large Language Model) workflows for querying and schema exploration.
- Tools provided:
  - `run_select_query`: Execute SQL queries on Hydrolix (read-only).
  - `list_databases`: List all databases in the Hydrolix cluster.
  - `list_tables`: List all tables in a specified database.
- All queries are executed with `readonly = 1` for safety.
- Designed to be used with LLM agents and tools, such as Claude Desktop.
- Supports configuration via standard MCP server entry (JSON or YAML).
- Environment variables for connection:
  - **Required:**
    - `HYDROLIX_HOST`: Hydrolix server hostname
    - `HYDROLIX_USER`: Authentication username
    - `HYDROLIX_PASSWORD`: Authentication password
  - **Optional:**
    - `HYDROLIX_PORT`: Port (default: 8088)
    - `HYDROLIX_VERIFY`: SSL certificate verification (default: "true")
    - `HYDROLIX_DATABASE`: Default database
- Can be launched using the [`uv` project manager](https://github.com/astral-sh/uv) for isolated dependency management.
- Example configuration provided for integration with Claude Desktop on macOS and Windows.
- 100% Python implementation.

## Configuration

- Supports both JSON and YAML configuration formats for MCP server definition.
- Environment variables can be set via MCP config block, `.env` file, or directly in the environment.
- Recommended to provide absolute path to `uv` executable for reliability.
- Example config snippets are provided in the README for quick setup.

## Pricing

No pricing information is provided. The project is open source under the Apache-2.0 license.

## Tags

`mcp` `hydrolix` `time-series` `datalake` `llm-integration`