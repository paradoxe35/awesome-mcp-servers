# MCP GraphQL

- **Repository:** [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql)
- **Category:** api-integration-mcp-servers
- **Tags:** mcp, graphql, api-integration, ai-integration

## Description
MCP GraphQL is a Model Context Protocol (MCP) server that enables LLMs (Large Language Models) or AI agents to interact with GraphQL APIs. It provides schema introspection and query execution capabilities, allowing AI models to dynamically discover and use any GraphQL API as a data source or tool.

## Features
- **GraphQL API Integration:** Connects any GraphQL API endpoint to the MCP protocol, making it accessible to AI agents.
- **Automatic Schema Introspection:** Automatically fetches the GraphQL schema from the endpoint or uses a local schema file if provided.
- **Query Execution:** Supports execution of GraphQL queries against the connected endpoint.
- **Mutation Support:** Mutations are disabled by default for security. Can be enabled via environment variable (`ALLOW_MUTATIONS=true`).
- **Custom Headers:** Allows custom HTTP headers to be set for requests (e.g., for authentication).
- **Configurable via Environment Variables:** All settings are controlled via environment variables (`ENDPOINT`, `HEADERS`, `ALLOW_MUTATIONS`, `NAME`, `SCHEMA`).
- **Exposes GraphQL Schema as a Resource:** Clients can access the schema directly from the server.
- **Tools Provided:**
  - `introspect-schema`: Retrieves the GraphQL schema (via introspection or local file).
  - `query-graphql`: Executes GraphQL queries (and optionally mutations if enabled).
- **Security Considerations:** Mutations are disabled by default to prevent unintended data modifications by AI agents.
- **Installation Options:**
  - Can be installed automatically via Smithery for Claude Desktop.
  - Manual installation instructions provided for integration into custom setups.
- **Open Source:** Licensed under MIT.

## Pricing
No pricing information is provided; MCP GraphQL is open source under the MIT license.

## Resources
- [GitHub Repository](https://github.com/blurrah/mcp-graphql)
- [Releases](https://github.com/blurrah/mcp-graphql/releases)

---

**Note:** Mutations should only be enabled in trusted environments due to potential security risks.