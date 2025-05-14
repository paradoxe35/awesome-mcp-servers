# Couchbase-Ecosystem/mcp-server-couchbase

[GitHub Repository](https://github.com/Couchbase-Ecosystem/mcp-server-couchbase)

## Description
Couchbase MCP Server is an implementation that enables unified access to Couchbase clusters, both self-managed and Capella cloud, through the Model Context Protocol (MCP). It allows large language models (LLMs) and agentic applications to interact directly with Couchbase databases for document operations, SQL++ queries, and natural language analysis.

## Features
- **Unified Couchbase Access**: Connects to both Capella (cloud) and self-managed Couchbase clusters.
- **Document Operations**:
  - Get a list of all scopes and collections in a specified bucket
  - Retrieve the structure of a collection
  - Get a document by ID from a specified scope and collection
  - Upsert (insert/update) a document by ID
  - Delete a document by ID
- **SQL++ Query Support**:
  - Run SQL++ queries on a specified scope
  - Configurable read-only query mode (enabled by default) to restrict queries that modify data or structure
- **Natural Language Analysis**: Enables LLMs and agentic apps to query and manipulate documents using natural language via MCP clients
- **MCP Client Integration**: Compatible with clients such as Claude Desktop, Cursor, and Windsurf Editor
- **Server-Sent Events (SSE) Transport Mode**: Supports SSE for real-time data streaming to clients
- **Docker Support**: Can be built and deployed as a Docker container with prebuilt images available on DockerHub
- **Configurable via Environment Variables**: Connection details, authentication, bucket selection, and query mode can all be set via environment variables
- **Port Configuration**: Default port is 8080, configurable via `FASTMCP_PORT`
- **Managed Option**: Can be used as a managed MCP server in agentic applications via Smithery.ai

## Configuration
- **Prerequisites**:
  - Python 3.10+
  - Couchbase cluster (Capella or self-managed)
  - `uv` installed for running the server
  - MCP client (e.g., Claude Desktop, Cursor, Windsurf Editor)
- **Environment Variables**:
  - `CB_CONNECTION_STRING`: Couchbase cluster connection string
  - `CB_USERNAME`: Username for database access
  - `CB_PASSWORD`: Password for the user
  - `CB_BUCKET_NAME`: Name of the Couchbase bucket
  - `READ_ONLY_QUERY_MODE`: Enable/disable mutating SQL++ queries (default: true)
  - `MCP_TRANSPORT`: Transport mode (e.g., `stdio`, `sse`)
  - `FASTMCP_PORT`: Port for server (default: 8080)
- **Docker Deployment**: Supports running as a container with the above variables

## Usage
- Clone the repository and configure as per your environment
- Integrate with compatible MCP clients for natural language and direct query access
- Optionally deploy as a Docker container

## Pricing
No pricing information is provided. This is an open-source project licensed under Apache-2.0.

## License
Apache-2.0

## Tags
`mcp` `couchbase` `database` `cloud`