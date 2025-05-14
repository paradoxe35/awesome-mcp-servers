# Honeycomb MCP

**Category:** Monitoring  
**Tags:** honeycomb, observability, monitoring, api-integration

## Description
Honeycomb MCP is a Model Context Protocol (MCP) server that enables direct querying and analysis of Honeycomb observability data. It is designed for Honeycomb Enterprise customers and allows integration with LLMs (like Claude) to analyze datasets, alerts, dashboards, and cross-reference production behavior with codebases. The server acts as a complete alternative interface to Honeycomb, requiring appropriate API permissions and configuration.

## Features
- **Direct Honeycomb API Integration**: Interact with Honeycomb observability data via MCP protocol.
- **Multi-environment Support**: Access datasets across multiple Honeycomb environments by configuring environment variables.
- **Caching**: Implements caching for non-query API calls to improve performance and reduce API usage; configurable via environment variables.
- **Resource Access**: Use URIs like `honeycomb://{environment}/{dataset}` to access datasets.
- **Tools for Data Analysis**:
  - `list_datasets`: List all datasets in an environment.
  - `get_columns`: Retrieve column information for a dataset.
  - `run_query`: Run analytics queries with rich specification options (calculations, filters, breakdowns, ordering, time ranges, etc.).
  - `analyze_columns`: Perform statistical analysis and compute metrics for specific columns.
  - `list_slos` and `get_slo`: List and get detailed information on SLOs.
  - `list_triggers` and `get_trigger`: List and get detailed information on triggers.
  - `get_trace_link`: Generate deep links to specific traces in the Honeycomb UI.
  - `get_instrumentation_help`: Get OpenTelemetry instrumentation guidance.
- **Optimized Tool Responses**: Tool responses are concise to optimize LLM context usage.
- **Flexible Query Specification**: Supports advanced query parameters, including calculations, filters, filter combinations (AND/OR), breakdowns, sorting, relative and absolute time ranges, and post-query filtering (having clause).
- **Client Compatibility**: Tested with various clients, designed to work broadly across compatible systems.

## Requirements
- Honeycomb Enterprise account
- API keys with broad permissions
- Self-hosted process (run the MCP server on your own infrastructure)

## Installation & Configuration
- Build artifact located in `/build` directory.
- Configure via environment variables (including API keys and optional EU endpoint).

## License
MIT

## Source Code
[https://github.com/honeycombio/honeycomb-mcp](https://github.com/honeycombio/honeycomb-mcp)

## Pricing
- Only available to Honeycomb Enterprise customers (no separate pricing information provided).