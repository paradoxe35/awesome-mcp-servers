# influxdb-mcp-server

[Source Code](https://github.com/idoru/influxdb-mcp-server)

## Description
A Model Context Protocol (MCP) server that enables query execution and management of InfluxDB instances via the InfluxDB OSS API v2.

## Features
- **Resources**
  - List all organizations in the InfluxDB instance
  - List all buckets and their metadata
  - List all measurements within a specified bucket
  - Execute Flux queries and return results as resources
- **Tools**
  - Write time-series data in InfluxDB line protocol format (parameters: org, bucket, data, precision)
  - Execute Flux queries (parameters: org, query)
  - Create new buckets (parameters: name, orgID, retentionPeriodSeconds)
  - Create new organizations (parameters: name, description)
- **Prompts**
  - Common Flux query examples
  - Guide to InfluxDB line protocol format
- **Configuration**
  - Requires `INFLUXDB_TOKEN` for authentication
  - Optional: `INFLUXDB_URL` (defaults to `http://localhost:8086`), `INFLUXDB_ORG` for default organization
- **Integration**
  - Can be integrated with Claude for Desktop as an MCP server
- **Installation Options**
  - Run directly with `npx`
  - Install globally via NPM
  - Run from source
- **Testing**
  - Comprehensive integration tests using Docker to spin up InfluxDB and validate all server functionality
- **Code Structure**
  - Modular organization (separate folders for config, utils, handlers, prompts)
  - Easily maintainable and testable

## Category
- database-messaging-mcp-servers

## Tags
- mcp
- database
- influxdb
- open-source

## License
- MIT

## Pricing
This project is open-source and free to use under the MIT license.