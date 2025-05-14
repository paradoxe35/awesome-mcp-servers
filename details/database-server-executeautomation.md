# database-server-executeautomation

A Model Context Protocol (MCP) server that enables LLMs to interact with SQLite and SQL Server databases. It supports schema inspection and SQL query execution, serving as an exemplary database MCP server.

**Source:** [GitHub Repository](https://github.com/executeautomation/mcp-database-server)

## Features
- **Supports Multiple Databases:**
  - SQLite
  - SQL Server
  - (Mentions Postgresql in some documentation, but primary support is for SQLite and SQL Server)
- **Direct and Local Usage:**
  - Can be installed globally as an NPM package for direct use
  - Can be run locally for development and customization
- **Integration with Claude Desktop:**
  - Configurable as an MCP server within Claude Desktop for database access
- **Database Tools Provided:**
  - `read_query`: Execute SELECT queries to read data
  - `write_query`: Execute INSERT, UPDATE, or DELETE queries
  - `create_table`: Create new tables in the database
  - `alter_table`: Modify existing table schema
  - `drop_table`: Remove a table from the database (with safety confirmation)
  - `list_tables`: Retrieve a list of all tables
  - `describe_table`: View schema information for a table
  - `export_query`: Export query results as CSV or JSON
  - `append_insight`: Add a business insight to a memo
  - `list_insights`: List all business insights
- **Flexible Configuration:**
  - Allows command-line configuration for both SQLite and SQL Server connections
  - Supports both SQL Server authentication and Windows Authentication
- **Development Support:**
  - Includes scripts for development (`npm run dev`) and watching file changes (`npm run watch`)
  - Written in TypeScript and JavaScript
- **Requirements:**
  - Node.js 18+
  - SQL Server 2012 or later (for SQL Server connectivity)
- **Open Source:**
  - Available under the MIT license

## Pricing
- **Open Source:** Free to use under the MIT license.

## Tags
mcp, database, sql, sqlite, sql-server

## Category
Database Messaging MCP Servers
