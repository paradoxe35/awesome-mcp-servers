# Iceberg MCP

[Source on GitHub](https://github.com/morristai/iceberg-mcp)

## Description
Iceberg MCP is a specialized MCP (Metadata Catalog Protocol) server that provides AI and programmatic access to Apache Iceberg catalogs, enabling exploration and analytics on data lake structures. It is designed for data engineering and analytics use cases.

## Features
- Provides an MCP server interface for Apache Iceberg catalogs
- Supports asynchronous operations and logging
- Supported catalog types:
  - REST Catalogs: Supported
  - AWS Glue: Supported
  - Hive Metastore: Not supported
  - S3 Table: Not supported
- Supported tools and operations:
  - `namespaces`: Retrieve all namespaces in the Iceberg catalog
  - `tables`: List all tables within a specified namespace
  - `table_schema`: Retrieve the schema for a specific table
  - `table_properties`: Get table properties for a specific table
- Installation options:
  - Download pre-built release binaries
  - Build from source using Rust
- Client integration steps documented (e.g., with Claude Desktop)
- Logging for debugging and troubleshooting

## Category
Data Analysis & Exploration MCP Servers

## Tags
`apache-iceberg`, `data-lake`, `analytics`, `mcp`, `exploration`

## Pricing
No pricing information is provided; open source on GitHub.