# MongoDB Lens

A full-featured Model Context Protocol (MCP) server for MongoDB databases, enabling advanced natural language interaction and management of MongoDB instances.

- **Website:** [MongoDB Lens](https://playbooks.com/mcp/furey-mongodb-lens)
- **Category:** database-messaging-mcp-servers
- **Tags:** mongodb, database, mcp, ai-integration

---

## Features

- **Natural Language Interaction:** Query and manage MongoDB databases using conversational language via any MCP-compatible client (e.g., Claude Desktop).
- **Database Browsing:** List databases, switch between them, and create new databases.
- **Collection Management:** List, create, rename, and check consistency of collections.
- **Querying:** Execute find, aggregate, and count operations. Supports advanced queries, aggregations, and data exploration.
- **Schema Analysis:** Analyze collection schemas, compare schemas, generate schema validators, and analyze common query patterns.
- **Data Modification:** Insert, update, and delete documents (with confirmation for destructive operations).
- **Performance & Index Management:** Create indexes, explain query execution plans, and retrieve database/collection statistics.
- **Security:** Supports use of read-only MongoDB user accounts for safer operations.
- **Destructive Operation Confirmation:** Token-based confirmation system for sensitive actions (e.g., dropping databases/collections, deleting documents).
- **Disable Destructive Tools:** Option to disable specific destructive tools via configuration.
- **Multiple Connection Support:** Configure and switch between multiple MongoDB connections using aliases and natural language commands.
- **Custom Configuration:** Extensive customization via a JSON configuration file. Supports environment variable for config path.
- **Flexible Installation:**
  - NPX (Node.js)
  - Docker Hub
  - Node.js from source
  - Docker from source
- **Client Compatibility:** Designed to integrate with Claude Desktop, Cursor, and MCP Inspector for testing and debugging.
- **Usage Examples:** Includes a wide range of natural language commands for database and collection operations, querying, schema analysis, data modification, and performance management.

---

## Installation Methods

- **NPX:** `npx -y mongodb-lens@latest [mongodb://your-connection-string]`
- **Docker:** `docker run --rm -i --network=host furey/mongodb-lens [mongodb://your-connection-string]`
- **From Source:** Clone from GitHub and run via Node.js or Docker.

---

## Pricing

_No pricing information provided._
