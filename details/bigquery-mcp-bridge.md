# BigQuery MCP Bridge

**Category:** database-messaging-mcp-servers  
**Source:** [GitHub Repository](https://github.com/haginot/bigquery-mcp)

## Description
BigQuery MCP Bridge is an official Model Context Protocol (MCP) server that provides access to Google BigQuery functionality. It enables petabyte-scale analytics and allows integration with other MCP servers for advanced querying and automation. The bridge is fully compliant with the MCP specification (rev 2025-03-26) and is designed to be used by LLM agents and other MCP clients.

## Features
- Full implementation of the Model Context Protocol for server-client communication
- Surfaces all Google BigQuery operations as MCP tools, enabling advanced analytics
- Allows integration with other MCP servers for automation and advanced querying
- Supports multiple deployment methods:
  - Command line
  - Python API
  - Docker
  - Docker Compose
- Authentication via Google Cloud credentials
- Optional resource exposure via `--expose-resources` flag
- Compatible with Claude Desktop for LLM agent access

## Installation & Usage
- Can be run directly, via Docker, or with docker-compose
- Authentication setup required using Google Cloud credentials
- Can be integrated into workflows using the command line, Python API, or as part of a larger MCP network

## Licensing
- MIT License

## Tags
`mcp` `bigquery` `database` `integration`

## Pricing
No pricing information is provided; the project is open source under the MIT license.