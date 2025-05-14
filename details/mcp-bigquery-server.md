# MCP BigQuery Server

A Model Context Protocol (MCP) server implementation for Google BigQuery, enabling secure, read-only access to BigQuery datasets. This allows Large Language Models (LLMs) to directly query and analyze data through a standardized interface.

- **Source:** [GitHub Repository](https://github.com/ergut/mcp-bigquery-server)
- **Category:** database-messaging-mcp-servers
- **Tags:** mcp, bigquery, database, cloud

## Features
- Implements the Model Context Protocol (MCP) for AI-database communication.
- Provides secure, read-only access to Google BigQuery datasets.
- Enables LLMs (such as Claude) to interact with BigQuery data via a standardized API.
- Allows natural language queries to be translated into SQL and executed on BigQuery.
- Supports integration with Claude Desktop for AI-assisted data analysis.
- Offers installation via Smithery or manual setup.
- Supports authentication with Google Cloud via multiple methods, including service accounts.
- Provides command line arguments for configuration.
- Developer setup instructions for customization or local development.
- Open source under the MIT License.

## Limitations
- Currently only supports read-only operations on BigQuery datasets.
- Designed primarily for use with Claude Desktop as of the current developer preview.

## Pricing
- Open source and free to use (MIT License).
