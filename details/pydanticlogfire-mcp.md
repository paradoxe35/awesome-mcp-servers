# pydantic/logfire-mcp

**Category:** Monitoring  
**Source:** [GitHub Repository](https://github.com/pydantic/logfire-mcp)

## Description
Logfire MCP Server is a Model Context Protocol (MCP) server that provides access to OpenTelemetry traces and metrics via Logfire. It enables robust monitoring and observability by allowing LLMs and clients to retrieve, analyze, and query telemetry data collected from your applications.

## Features
- **OpenTelemetry Integration:** Access traces and metrics collected via OpenTelemetry and sent to Logfire.
- **LLM-Accessible:** Enables large language models and other clients to retrieve and analyze telemetry data.
- **Trace Analysis Tools:**
  - `find_exceptions`: Retrieve exception counts from traces grouped by file within a specified time window.
  - `find_exceptions_in_file`: Get detailed trace information about exceptions in a specific file.
- **Custom Metrics Querying:**
  - `arbitrary_query`: Execute arbitrary SQL queries on your OpenTelemetry traces and metrics.
  - `get_logfire_records_schema`: Retrieve the OpenTelemetry schema for custom queries.
- **Time Window Specification:** All analysis tools accept a configurable time window (up to 7 days).
- **Multiple Client Support:** Easily configurable for popular MCP clients such as Cursor, Claude Desktop, and Cline.
- **Customizable API Endpoint:** Supports overriding the default Logfire API base URL.
- **Authentication:** Requires a project-specific Logfire read token for secure access.
- **Examples Provided:** Includes example queries and JSON responses for trace analysis.
- **Python Implementation:** 100% Python codebase.
- **MIT Licensed:** Free to use, modify, and distribute.

## Setup & Usage
- **Installation:** Requires the `uv` tool for running the MCP server.
- **Authentication:** Obtain a Logfire read token from your project settings in Logfire.
- **Running the Server:** Can be started manually via `uvx logfire-mcp --read-token=YOUR_TOKEN` or through MCP clients with appropriate configuration.
- **Client Configuration:** Example configurations available for Cursor, Claude Desktop, and Cline.
- **Custom Base URL:** Set via `--base-url` argument or `LOGFIRE_BASE_URL` environment variable.

## Pricing
No pricing information is provided; the project is open source and licensed under MIT.

## Tags
`mcp`, `monitoring`, `observability`, `opentelemetry`, `metrics`
