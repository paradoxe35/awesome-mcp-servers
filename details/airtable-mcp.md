# airtable-mcp

Airtable-mcp is an open-source server that integrates Airtable with Anthropic's Model Context Protocol (MCP), allowing AI-powered applications and tools (such as Claude Desktop) to perform CRUD operations and manage Airtable data directly from code editors or AI interfaces.

**Source:** [https://github.com/rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp)

## Features
- **Base Management:** List and select Airtable bases.
- **Table Operations:** Browse tables, fields, and records.
- **Data Access:** Read, create, update, and delete records.
- **Schema Management:** Export, compare, and update schemas.
- **Natural Language Interface:** Use plain English to interact with Airtable data through AI tools.
- **Standardized MCP Interface:** Compatible with Claude Desktop and other Claude-powered editors.
- **Available Tools:**
  - `list_bases`: List all accessible Airtable bases.
  - `list_tables`: List all tables in the current base.
  - `list_records`: List records with optional filtering.
  - `get_record`: Retrieve a specific record.
  - `create_records`: Create new records.
  - `update_records`: Update existing records.
  - `set_base_id`: Switch to a different base.
- **Quick Start & Configuration:** Easily set up with Claude Desktop using a simple JSON configuration.
- **Error Handling:** Guidance for common issues such as connection or JSON parsing errors.
- **Cross-Platform:** Implemented in Python and JavaScript; can be run via Node.js or Python environments.

## Pricing
- **Open Source:** Free to use under the MIT License.

## License
MIT License

## Tags
`airtable` `database` `integration` `mcp`
