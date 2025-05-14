# airtable-server

[View Source](https://mcphubs.top/p/airtable-mcp-server)

## Description
The `airtable-server` is a Model Context Protocol (MCP) server that provides read and write access to Airtable databases. It enables AI models, particularly Large Language Models (LLMs), to interact with Airtable by inspecting schemas, retrieving records, modifying data, and managing tables and fields. The server is designed for easy integration with MCP-compatible clients, using standard input/output and HTTP/SSE for communication.

## Features
- **Read Airtable Data:**
  - List records from specified tables (with filtering and limiting)
  - Search records by text within specific fields
  - Fetch individual records by ID
- **Write Airtable Data:**
  - Create new records in tables
  - Update existing records
  - Delete records
- **Discover Airtable Schema:**
  - List all accessible Airtable bases (IDs, names, permission levels)
  - List tables within a base (IDs, names, descriptions, fields, views)
  - Describe detailed table schemas
- **Table and Field Management:**
  - Create new tables
  - Update table names and descriptions
  - Create new fields in a table
  - Update field names and descriptions
- **Integration & Communication:**
  - Seamless integration with the MCP ecosystem
  - Supports standard input/output and HTTP/SSE for flexible deployment
  - Handles authentication, data formatting, and error handling
- **Automation & AI Agent Support:**
  - Enables building AI agents for automating data entry, generating reports, and creating intelligent workflows based on Airtable data

## Category
- database-messaging-mcp-servers

## Tags
- airtable
- database
- integration
- mcp

## Pricing
No pricing information was provided in the available content.
