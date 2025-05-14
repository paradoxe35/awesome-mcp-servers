# Hny Mcp

A Model Context Protocol (MCP) server for enabling analysis and querying of Honeycomb observability datasets by LLMs. It acts as an alternative interface to Honeycomb, allowing AI models to access, analyze, and interact with observability data, alerts, dashboards, and related metrics.

**Source:** [https://github.com/austinlparker/hny-mcp](https://github.com/austinlparker/hny-mcp)

## Category
- Monitoring

## Tags
- mcp
- honeycomb
- observability
- data-analysis

## Features
- **MCP Server for Honeycomb**: Provides a Model Context Protocol server for interacting with Honeycomb observability data.
- **LLM Integration**: Enables LLMs (such as Claude) to directly analyze and query Honeycomb datasets across multiple environments.
- **Alternative Interface**: Serves as a complete alternative interface to Honeycomb, requiring broad API permissions.
- **Multiple Environment Support**: Allows access to datasets across different environments.
- **Caching**: Implements caching for all non-query API calls to improve performance and reduce API usage. Configurable via environment variables.
- **Resource Access**: Access datasets using URIs (`honeycomb://{environment}/{dataset}`) and retrieve dataset metadata.
- **Tools**:
  - `list_datasets`: List all datasets in an environment.
  - `get_columns`: Get column information for a dataset.
  - `run_query`: Run analytics queries with rich options (calculations, filters, breakdowns, orders, time ranges, etc.).
  - `analyze_columns`: Perform statistical analysis on dataset columns and return computed metrics.
  - `list_slos` / `get_slo`: List and get detailed Service Level Objective (SLO) information.
  - `list_triggers` / `get_trigger`: List and get detailed trigger information.
  - `get_trace_link`: Generate a deep link to a specific trace in the Honeycomb UI.
  - `get_instrumentation_help`: Provides OpenTelemetry instrumentation guidance.
- **Optimized Tool Responses**: Tool responses are optimized to minimize context window usage, providing concise yet complete information.
- **Query Specification**: Supports complex queries with calculations, filters, breakdowns, sorting, time ranges, and post-calculation filtering (`having`).
- **Self-hosted**: Runs as a single server process on your own machine; not authenticated by default.
- **Honeycomb Enterprise Only**: Currently available for Honeycomb Enterprise customers.
- **Client Compatibility**: Tested with various LLM clients.
- **Configuration**: Requires setup of Honeycomb API keys and endpoint configuration for EU users.

## Requirements
- Honeycomb Enterprise account
- Proper API keys and permissions
- Self-hosted server setup

## Pricing
- Not specified (open source, MIT License)

## License
- MIT License