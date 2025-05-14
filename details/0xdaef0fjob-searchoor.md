# 0xdaef0f/job-searchoor

A simple MCP server that provides job search functionality with filtering options.

**Source:** [GitHub Repository](https://github.com/0xDAEF0F/job-searchoor)

## Features
- Implements the MCP server protocol for job search.
- `get_jobs` endpoint with the following filtering options:
  - `sinceWhen`: Filter jobs by date (e.g., '1d' for one day, '1w' for one week; only days and weeks supported).
  - `keywords`: Filter jobs by specific keywords (optional).
  - `excludeKeywords`: Exclude jobs that contain certain keywords (optional).
  - `isRemote`: Filter jobs for remote work (optional).
- Can be integrated with Claude Desktop via configuration.
- Open-source and licensed under the MIT License.

## Pricing
- Free and open-source under the MIT License.

## Tags
mcp, job-search, search, open-source