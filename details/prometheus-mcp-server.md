# prometheus-mcp-server

A Model Context Protocol (MCP) server for Prometheus that enables AI assistants to query and analyze Prometheus metrics through standardized interfaces.

**Source:** [GitHub - pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server)

## Features
- **Execute PromQL Queries:**
  - Execute instant and range PromQL queries against a Prometheus server.
- **Metric Discovery and Exploration:**
  - List all available metrics in Prometheus.
  - Retrieve metadata for specific metrics.
  - View instant query results.
  - View range query results with different step intervals.
- **Authentication Support:**
  - Basic authentication via environment variables.
  - Bearer token authentication via environment variables.
- **Multi-tenancy Support:**
  - Supports Org ID for multi-tenant setups (e.g., Cortex, Mimir, Thanos).
- **Docker Support:**
  - Official Dockerfile and docker-compose configuration for easy deployment.
  - Multi-stage Docker build for proper MCP communication.
- **Configurable Toolset:**
  - Tools available to the MCP client are configurable to limit context window usage.
- **Comprehensive Test Suite:**
  - Includes configuration validation, server functionality, error handling, and main application tests.
- **Interactive Tools for AI Assistants:**
  - MCP tools include:
    - `execute_query`: Execute instant PromQL queries.
    - `execute_range_query`: Execute range queries with time intervals.
    - `list_metrics`: List all available metrics.
    - `get_metric_metadata`: Get metadata for a specific metric.
    - `get_targets`: Get information about all scrape targets.
- **Development-Friendly:**
  - Uses `uv` for dependency management.
  - Source structure with clear separation of main application and server logic.
- **Open Source:**
  - Licensed under the MIT License.

## Pricing
No pricing information is provided. The project is open source under the MIT license.
