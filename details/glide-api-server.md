# Glide Api Server

**Category:** API Integration MCP Servers  
**Tags:** api-integration, glide, automation, mcp, data-access

## Description
The Glide API MCP Server is a Model Context Protocol (MCP) server that bridges the Glide API (supporting both v1 and v2) to MCP tools, enabling automated management and data operations for Glide applications. It allows users to manage Glide apps, tables, and data through standardized interfaces.

## Features
- **API Version Support:** Works with both Glide API v1 and v2.
- **Automated Management:** Enables automated operations for Glide apps, tables, and data.
- **Standardized MCP Interface:** Interact with Glide apps using MCP tools.
- **Tools Provided:**
  - `set_api_version`: Configure API version and authentication at runtime.
  - `get_app`: Retrieve app information.
  - `get_tables`: List tables within an app.
  - `get_table_rows`: Fetch data rows from a specific table.
  - `add_table_row`: Add a new row to a table.
  - `update_table_row`: Update an existing row in a table.
- **Configuration:**
  - Supports environment variable configuration for secure API key management.
  - Runtime configuration is possible for overriding API settings per session.
- **Integration:**
  - Can be installed globally (available for all projects) or per project in Cursor via the `.cursor/mcp.json` file.
- **Security Practices:**
  - Encourages use of environment variables.
  - Advises against storing API keys in version control.
  - Recommends regular API key rotation and proper file permissions.

## Installation & Setup
- Install by adding the server to the appropriate MCP configuration file (global or project-specific).
- Configure API credentials using environment variables in the MCP settings file.
- Optionally, adjust settings at runtime with provided tools.

## Pricing
No pricing information is provided.

## Source / More Info
[https://playbooks.com/mcp/knmurphy-glide-api](https://playbooks.com/mcp/knmurphy-glide-api)
