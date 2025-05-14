# mcp-server-sqlalchemy

**Source:** [GitHub - OpenLinkSoftware/mcp-sqlalchemy-server](https://github.com/OpenLinkSoftware/mcp-sqlalchemy-server)

**Category:** database-messaging-mcp-servers

**Tags:** mcp, database, sqlalchemy, python

## Description
mcp-server-sqlalchemy is a lightweight Model Context Protocol (MCP) server built with Python, FastAPI, ODBC (via pyodbc), and SQLAlchemy. It enables database connectivity and integration with multiple DBMS backends (including Virtuoso, PostgreSQL, MySQL, and SQLite) that support SQLAlchemy. The server exposes endpoints for schema and table exploration, SQL query execution, and Virtuoso-specific features, facilitating integration in MCP environments.

## Features
- **Database Schema and Table Exploration:**
  - List all schema names from the connected database.
  - Retrieve information about tables for specific schemas or all schemas.
  - Filter and search tables based on name substrings.
  - Describe table structures, including column names, data types, nullability, autoincrement, primary and foreign keys.
- **SQL Query Execution:**
  - Execute SQL queries and return results in JSON, JSONL (one object per line), or Markdown table formats.
- **Stored Procedures:**
  - Execute stored procedures and retrieve results (Virtuoso DBMS specific).
- **SPASQL & SPARQL Support (Virtuoso-specific):**
  - Execute SPASQL (SQL/SPARQL hybrid) and SPARQL queries and retrieve results in various formats.
- **AI Assistant Integration (Virtuoso-specific):**
  - Interact with the Virtuoso Support Assistant/Agent for AI-powered database assistance.
- **Multiple DBMS Backends Supported:**
  - Works with Virtuoso, PostgreSQL, MySQL, SQLite, and other databases compatible with SQLAlchemy.
- **ODBC DSN Configuration:**
  - Uses ODBC Data Source Names for flexible connection setup.
- **REST API via FastAPI:**
  - Exposes all operations as RESTful endpoints.
- **Configuration via Environment Variables:**
  - Supports easy configuration of ODBC credentials, API keys, etc.
- **Integration with Claude Desktop:**
  - Can be configured to run as an MCP server for Claude Desktop AI workflows.
- **Troubleshooting Tools:**
  - Supports MCP Inspector for debugging and troubleshooting server interactions.

## Tools Provided (API endpoints)
| Name                     | Description                                                                                           |
|--------------------------|------------------------------------------------------------------------------------------------------|
| podbc_get_schemas        | List database schemas accessible to the connected DBMS.                                                |
| podbc_get_tables         | List tables for a specified schema.                                                                   |
| podbc_describe_table     | Describe a table (columns, types, nulls, keys, etc.).                                                 |
| podbc_filter_table_names | List tables matching a substring pattern.                                                              |
| podbc_query_database     | Execute SQL query and return results in JSON format.                                                  |
| podbc_execute_query_md   | Execute SQL query and return results in Markdown table format.                                        |
| podbc_query_database_jsonl| Execute SQL query and return results in JSONL format.                                                |
| podbc_spasql_query       | Execute SPASQL query (Virtuoso-specific).                                                             |
| podbc_sparql_query       | Execute SPARQL query (Virtuoso-specific).                                                             |
| podbc_virtuoso_support_ai| Use Virtuoso Support AI Assistant (Virtuoso-specific).                                                |

## Installation & Configuration
- Clone the repository and install dependencies.
- Configure ODBC Data Source Name for your target database.
- Set environment variables for ODBC credentials and API key.
- Start the server using `uv` or similar Python runners.
- Optionally, integrate with Claude Desktop or use MCP Inspector for troubleshooting.

## Supported Databases (Connection Examples)
- **Virtuoso DBMS:** `virtuoso+pyodbc://user:password@ODBC_DSN`
- **PostgreSQL:** `postgresql://user:password@localhost/dbname`
- **MySQL:** `mysql+pymysql://user:password@localhost/dbname`
- **SQLite:** `sqlite:///path/to/database.db`

## Pricing
No pricing information provided. The project is open source under the MIT license.