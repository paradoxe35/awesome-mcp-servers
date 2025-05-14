# oura-mcp-server

An MCP (Model Context Protocol) server for integrating with the Oura API, enabling access to health and sleep data from the Oura app.

**Source:** [oura-mcp-server on GitHub](https://github.com/tomekkorbak/oura-mcp-server)

## Features
- Provides access to Oura API data for sleep, readiness, and resilience metrics.
- Exposes several tools via MCP:
  - `get_sleep_data(start_date: str, end_date: str)`: Retrieve sleep data for a specific date range (ISO format).
  - `get_readiness_data(start_date: str, end_date: str)`: Retrieve readiness data for a specific date range.
  - `get_resilience_data(start_date: str, end_date: str)`: Retrieve resilience data for a specific date range.
  - `get_today_sleep_data()`: Retrieve today's sleep data.
  - `get_today_readiness_data()`: Retrieve today's readiness data.
  - `get_today_resilience_data()`: Retrieve today's resilience data.
- Designed for integration with language models (such as Claude) for querying Oura data conversationally.
- Human-readable error messages for:
  - Invalid date formats
  - API authentication errors
  - Network connectivity problems
- Requires an Oura API token for access (instructions provided in the README).
- Licensed under the MIT License.

## Pricing
No pricing information provided. The project is open-source under the MIT license.

## Tags
health, oura, wellness, api-integration

## Category
data-access-integration-mcp-servers