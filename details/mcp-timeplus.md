# mcp-timeplus

**Source:** [GitHub Repository](https://github.com/jovezhong/mcp-timeplus)

## Overview
mcp-timeplus is an MCP server for Timeplus, designed to interact with Apache Kafka, Timeplus clusters, and Apache Iceberg databases. It enables users to execute SQL queries, manage databases, list topics, poll messages, store local data, and run streaming SQL queries.

## Features
- **SQL Execution**: Run SQL queries on your Timeplus cluster with support for read-only and DDL/DML operations (configurable via environment variable).
- **Database Management**:
  - List all databases in your Timeplus cluster.
  - List all tables in a specific database.
- **Kafka Integration**:
  - List all topics in a Kafka cluster.
  - Explore Kafka topics by showing messages from a specified topic.
  - Create streaming ETL jobs to save Kafka messages locally in Timeplus.
- **Apache Iceberg Integration**: Connect to databases based on Apache Iceberg (currently available for Timeplus Enterprise, with plans for Proton support).
- **Environment Variable Configuration**: Flexible configuration with support for various connection, authentication, and timeout settings for Timeplus and Kafka.
- **Docker Support**: Includes a Dockerfile for containerized deployment.
- **Development Tools**: Supports local development and testing with docker-compose and environment variable configuration.
- **User-friendly Interface**: Designed to enhance data workflows with accessible tools and a robust backend.

## Environment Variables
- `TIMEPLUS_HOST`, `TIMEPLUS_USER`, `TIMEPLUS_PASSWORD` (required)
- `TIMEPLUS_PORT`, `TIMEPLUS_SECURE`, `TIMEPLUS_VERIFY`, `TIMEPLUS_CONNECT_TIMEOUT`, `TIMEPLUS_SEND_RECEIVE_TIMEOUT`, `TIMEPLUS_DATABASE`, `TIMEPLUS_READ_ONLY` (optional)
- `TIMEPLUS_KAFKA_CONFIG` (JSON string for Kafka connection settings)

## Category
- database-messaging-mcp-servers

## Tags
- mcp
- kafka
- streaming
- data-integration

## License
- Apache-2.0

## Pricing
- No pricing information is provided; the repository is open-source under the Apache-2.0 license.