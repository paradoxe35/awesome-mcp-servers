# dune-analytics-mcp

A Model Context Protocol (MCP) server that bridges Dune Analytics data to AI agents for advanced blockchain analytics.

**Source:** [https://github.com/kukapay/dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp)

## Features
- **Dune Analytics Integration:** Connects to Dune Analytics API to fetch blockchain analytics data.
- **AI Agent Bridge:** Exposes Dune Analytics data to AI agents via MCP server protocol.
- **Tools Provided:**
  - `get_latest_result`: Fetch the latest results of a Dune Analytics query by its ID.
  - `run_query`: Execute a Dune Analytics query by its ID and retrieve results.
- **CSV Output:** All query results are returned as CSV-formatted strings for easy processing.
- **Environment Setup:**
  - Requires Python 3.10+
  - Needs a valid Dune Analytics API key
- **Deployment Options:**
  - Development mode with hot reloading
  - Installable as a service for use with Claude Desktop
- **Open Source:** MIT License

## Installation & Usage
- Clone the repository and set the required environment variables (`DUNE_API_KEY`).
- Run the server in development or install as a service for Claude Desktop.
- Use provided tools via API or Claude Desktop commands.

## Pricing
- Open source and free to use under the MIT License.

## Tags
`dune-analytics` `blockchain` `analytics` `ai-integration`