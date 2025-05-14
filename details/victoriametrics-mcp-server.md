# victoriametrics-mcp-server

An MCP server for interacting with VictoriaMetrics time-series database via the Model Context Protocol.

**Source:** [GitHub Repository](https://github.com/yincongcyincong/VictoriaMetrics-mcp-server)

**Category:** database-messaging-mcp-servers

**Tags:** mcp, victoriametrics, time-series, database, metrics

---

## Features

- **Write Data (vm_data_write):**
  - Write data to the VictoriaMetrics database.
  - Accepts metric tags, values (array of numbers), and timestamps (array of Unix seconds).

- **Import Prometheus Data (vm_prometheus_write):**
  - Import metrics in Prometheus exposition format into VictoriaMetrics.

- **Query Time Series Data (vm_query_range):**
  - Query time series data over a specific time range using PromQL expressions.
  - Supports optional start, end, and step parameters for flexible queries.

- **Query Current Value (vm_query):**
  - Query the current value of a time series using PromQL.
  - Supports optional evaluation timestamp.

- **Retrieve Unique Labels (vm_labels):**
  - Get all unique label names in the VictoriaMetrics database.

- **Retrieve Label Values (vm_label_values):**
  - Get all unique values for a specified label name.

## Pricing

No pricing information is provided in the available content.
