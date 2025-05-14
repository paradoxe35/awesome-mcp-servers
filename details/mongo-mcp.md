# mongo-mcp

**Description:**
MongoDB MCP server integration for allowing LLMs to interact directly with MongoDB databases via the Model Context Protocol (MCP). It enables querying, schema inspection, document management, and index operations through natural language interfaces.

**Source:** [https://github.com/QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp)

**Category:** database-messaging-mcp-servers

**Tags:** mcp, mongodb, database, integration

---

## Features
- **Collection Schema Inspection:** Explore and view the schema of MongoDB collections.
- **Document Querying and Filtering:** Perform queries on documents with filtering and projection options.
- **Index Management:** Create, list, and drop indexes on collections.
- **Document Operations:** Insert, update, and delete documents.
- **Integration with LLMs:** Allows large language models (LLMs) to interact with MongoDB databases through natural language prompts.
- **Supported Operations:**
  - `find`: Query documents
  - `listCollections`: List available collections
  - `insertOne`: Insert a single document
  - `updateOne`: Update a single document
  - `deleteOne`: Delete a single document
  - `createIndex`: Create an index
  - `dropIndex`: Remove an index
  - `indexes`: List indexes for a collection
- **Test Sandbox Setup:**
  - Docker Compose for local MongoDB instance
  - Seed script to populate test data (Users, Products, Orders collections)
- **Example Prompts:**
  - Get collection names
  - Show collection schema
  - Find users/products/orders based on complex criteria
  - Manage indexes and documents via natural language
- **Installation Options:**
  - Via npx command
  - Via Smithery CLI
- **Prerequisites:**
  - Node.js 18+
  - npx
  - Docker and Docker Compose (for sandbox)
  - MCP Client (e.g., Claude Desktop App)

## Pricing
- No pricing information provided; the project is open source under the MIT License.

## License
- MIT License