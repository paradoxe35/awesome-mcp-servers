# gateway

[Source code](https://github.com/centralmind/gateway)

## Description

gateway is an AI-powered data gateway that automatically generates secure, LLM-optimized APIs from your structured database schema and data. It is designed for use cases where AI agents and LLM applications require fast, secure, and compliant access to data without direct SQL access. It supports multiple databases and protocols and includes features for security, compliance, and performance.

## Features

- **Automatic API Generation**: Uses LLMs to generate APIs based on your database schema and sampled data.
- **Structured Database Support**: Connects with PostgreSQL, MySQL, ClickHouse, Snowflake, and more.
- **Multiple Protocols**: Offers REST and Model Context Protocol (MCP) APIs, including SSE mode.
- **Auto-generated Documentation**: Produces Swagger documentation and OpenAPI 3.1.0 specs automatically.
- **PII Protection**: Redacts sensitive data using regex or Microsoft Presidio plugins to ensure compliance with GDPR, CPRA, SOC 2, etc.
- **Traceability and Auditing**: Integrates with OpenTelemetry (OTel) for request tracking and audit trails.
- **Optimized for AI Workloads**: Adds metadata for AI agents, supports caching, and model context.
- **Flexible Configuration**: Extensible via YAML files and plugin system.
- **Deployment Options**: Can be deployed as a binary, Docker container, or via Helm chart for Kubernetes.
- **Multiple AI Provider Support**: Integrates with OpenAI, Anthropic, Amazon Bedrock, Google Gemini, Google VertexAI, and allows for self-hosted LLMs.
- **Row-Level Security**: Fine-grained access control through Lua scripting.
- **Authentication**: Built-in API key and OAuth support.
- **Performance Optimization**: Provides time-based and LRU caching strategies.
- **Local & On-Premises Support**: Can connect to local or on-premise LLM endpoints.
- **Integration with AI Tools**: Works with LangChain, OpenAI, Claude Desktop, and more.
- **Roadmap Features** (planned):
  - Additional database integrations (Redshift, S3, Oracle DB, MS SQL Server, Elasticsearch)
  - SSH tunneling for secure connections
  - Advanced query and aggregation functions
  - Schema management and API versioning
  - Advanced traffic management (rate limiting, throttling)
  - Support for write operations (insert, update)

## Pricing

No pricing information is provided; gateway is open source under the Apache-2.0 license.

## Category

mcp-middleware-orchestration

## Tags

mcp, gateway, sse, database, auto-generation
