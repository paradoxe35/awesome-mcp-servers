# mcp-mongo-server

**Description:**
A Model Context Protocol (MCP) server for MongoDB. It enables database operations through MCP, allowing LLMs and compatible tools to inspect MongoDB collection schemas and execute read-only queries.

**Source:** [GitHub - kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server)

**Category:** database-messaging-mcp-servers

**Tags:** mcp, mongodb, database, integration

---

## Features

- **MCP Server for MongoDB:** Provides access to MongoDB databases via the Model Context Protocol.
- **Collection Listing and Access:** List and access MongoDB collections using `mongodb://` URIs.
- **Schema Inspection:** Each collection exposes name, description, and schema (in JSON mime type).
- **Read-Only Queries:**
  - **query tool:** Execute read-only MongoDB queries against the connected database.
  - **aggregate tool:** Execute read-only aggregate queries against the database.
- **Collection Analysis Prompts:**
  - Provide insights about a collection's structure, data types, and basic statistics.
- **Schema Resources:**
  - Access JSON schema information for each collection, including field names and data types, inferred from collection documents.
- **Integration:**
  - Usable with Claude Desktop (Anthropic) and can be installed/configured for use with Claude Desktop via configuration files.
  - Installable via Smithery and mcp-get tools.
- **Development Support:**
  - Debugging with MCP Inspector (browser-based debugging tools).
  - Scripts for development, build, watch, and inspector modes.
- **Open Source:**
  - Licensed under the MIT License.

## Pricing

- This project is open source and free to use under the MIT License.
