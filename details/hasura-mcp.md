# Hasura MCP

**Category:** Database Messaging MCP Servers  
**Tags:** hasura, graphql, database, ai-integration  
**Source:** [Hasura MCP on playbooks.com](https://playbooks.com/mcp/husamabusafa-hasura-graphql)

## Description
Hasura MCP is a server that enables AI agents to interact with Hasura GraphQL endpoints. It allows schema discovery, data querying, and database operations through natural language requests. The server exposes various database tools to facilitate these interactions.

## Features
- **AI Interaction:** Enables AI agents to interact with Hasura GraphQL APIs for schema discovery, data access, and operations.
- **Natural Language Requests:** Supports executing queries, mutations, and data operations based on natural language prompts.
- **Schema Discovery:** Provides the full GraphQL schema definition via introspection.
- **Data Querying:** Executes read-only GraphQL queries (`run_graphql_query`).
- **Data Mutation:** Executes GraphQL mutations (`run_graphql_mutation`).
- **Table Management:**
  - Lists available tables (`list_tables`).
  - Describes the structure of specific tables (`describe_table`).
  - Previews sample data from tables (`preview_table_data`).
- **Field and Type Information:**
  - Lists root fields (queries, mutations, subscriptions) (`list_root_fields`).
  - Describes specific GraphQL types (`describe_graphql_type`).
- **Data Aggregation:** Performs aggregations such as count, sum, average, min, and max (`aggregate_data`).
- **Health Check:** Verifies the Hasura endpoint is operational (`health_check`).
- **Integration:**
  - Can be added to Cursor or Claude Desktop via configuration files.
  - Runs as a Node.js server (requires Node.js v18+ and pnpm/npm/yarn).
  - Supports use with or without Hasura Admin Secret.
- **Example Usage:** Supports prompts like "List all tables", "Describe the 'users' table", "Preview data from 'orders' table", "Run the query { products { name price } }", and more.

## Installation Requirements
- Node.js v18 or higher
- pnpm (or npm/yarn)
- Access to a running Hasura GraphQL endpoint
- (Optional) Hasura Admin Secret

## Configuration
- Can be integrated with MCP clients like Cursor and Claude Desktop via configuration files (`settings.json`, `claude_desktop_config.json`).
- Supports both global and project-specific installation for Cursor.

## Pricing
No pricing information is provided in the available content.
