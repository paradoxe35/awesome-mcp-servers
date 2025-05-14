# MCP Grafana

- **Category**: Monitoring
- **Source**: [GitHub - grafana/mcp-grafana](https://github.com/grafana/mcp-grafana)
- **Tags**: grafana, monitoring, dashboard, mcp

## Description
MCP Grafana is a Model Context Protocol (MCP) server for Grafana. It provides programmatic access to a Grafana instance and its ecosystem, enabling searching dashboards, investigating incidents, and querying datasources. It is designed to be modular, allowing you to configure which tools to expose to the MCP client.

## Features
- **Configurable Tools**: Select which tools to make available to the MCP client for tailored use cases.
- **Dashboard Search**: Search for dashboards within Grafana.
- **Datasource Management**:
  - List all datasources
  - Get a datasource by UID
  - Get a datasource by name
- **Prometheus Integration**:
  - Execute queries against a Prometheus datasource
  - List metric metadata
  - List available metric names
  - List label names matching a selector
  - List values for a specific label
- **Incident Management (Grafana Incident)**:
  - List incidents
  - Create new incidents
  - Add activity items to existing incidents
  - Resolve incidents
- **Deployment Options**: Can be installed via pre-built releases or built from source (Go toolchain). Also supports Docker deployment.
- **Testing and Development**: Includes unit and integration tests, with instructions for local and cloud testing.
- **Open Source**: Licensed under the Apache License, Version 2.0.

## Pricing
No pricing information is provided. MCP Grafana is open source and available for free under the Apache License, Version 2.0.