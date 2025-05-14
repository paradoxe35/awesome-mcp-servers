# domdomegg/airtable-mcp-server

A Model Context Protocol (MCP) server that enables AI systems and other clients to interact with Airtable databases, providing schema inspection and read/write capabilities.

**Source:** [GitHub Repository](https://github.com/domdomegg/airtable-mcp-server)

## Features

- **Read and Write Access:**
  - Provides both read and write access to Airtable databases via MCP protocol.
- **Schema Inspection:**
  - Allows clients to inspect Airtable base and table schemas, including field and view definitions.
- **MCP Tools/Components:**
  - `list_records`: List records from a specified table, with optional filtering and record limit.
  - `search_records`: Search for records containing specific text, with optional field selection and record limit.
  - `list_bases`: List all accessible Airtable bases.
  - `list_tables`: List all tables in a base, with configurable detail level.
  - `describe_table`: Get detailed information about a specific table.
  - `get_record`: Retrieve a specific record by ID.
  - `create_record`: Create a new record in a table with specified fields.
  - `update_records`: Update one or more records in a table.
  - `delete_records`: Delete one or more records from a table.
  - `create_table`: Create a new table in a base with specified fields and description.
  - `update_table`: Update a table's name or description.
  - `create_field`: Add a new field to a table with type and options.
  - `update_field`: Update a field's name or description.
- **Schema Information as JSON:**
  - Provides table schemas as JSON, including base and table IDs, field definitions, view definitions, and primary field ID.
  - Uses Airtable's metadata API for automatic schema discovery.
- **Integration:**
  - Can be integrated with AI tools such as Claude Desktop by specifying the MCP server in configuration.
- **Authentication:**
  - Requires Airtable personal access token with appropriate permissions.
- **Open Source:**
  - MIT licensed.
  - Written in TypeScript.
  - Community contributions welcome.

## Pricing

No pricing information is provided; the project is open source and available under the MIT license.