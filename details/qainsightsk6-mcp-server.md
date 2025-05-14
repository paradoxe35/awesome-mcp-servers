# qainsights/k6-mcp-server

**Description:**

qainsights/k6-mcp-server is a Model Context Protocol (MCP) server for running k6 load tests, enabling integration with k6 for automated performance test execution. It provides a simple API and can be configured for custom test durations and virtual users.

**Source:** [https://github.com/QAInsights/k6-mcp-server](https://github.com/QAInsights/k6-mcp-server)

**Category:** Testing & Debugging Tools

**Tags:** mcp, testing, performance, k6, grafana

---

## Features

- Integration with Model Context Protocol (MCP) framework
- Supports running k6 load tests via an easy-to-use API
- Customizable test durations and number of virtual users (VUs)
- Real-time test execution output
- Configurable via environment variables (e.g., K6 binary path)
- Two main execution options:
  - `execute_k6_test`: Run a test with default options (30s duration, 10 VUs)
  - `execute_k6_test_with_options`: Run a test with custom duration and VUs
- Can be integrated into various MCP clients (e.g., Claude Desktop, Cursor, Windsurf)
- Useful for LLM-powered results analysis and debugging of load tests
- Written primarily in Python, with some JavaScript components
- Licensed under the MIT License

## Installation & Setup

- Requires Python 3.12 or higher, k6 load testing tool, and uv package manager
- Clone the repository and install dependencies using `uv pip install -r requirements.txt`
- Optional: Configure environment variables for custom k6 binary locations

## API Reference

- `execute_k6_test(script_file: str, duration: str = "30s", vus: int = 10)`
- `execute_k6_test_with_options(script_file: str, duration: str, vus: int)`

## Use Cases

- Automated performance/load testing with k6
- Integration with LLM tools for results analysis
- Debugging and analysis of load test outcomes

## Pricing

- Free and open source (MIT License)