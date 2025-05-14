# mcp-server-jdbc

A lightweight Java-based Model Context Protocol (MCP) server for JDBC, designed for generic DBMS connectivity, including Virtuoso and any backend with a JDBC driver.

- **Source:** [GitHub - OpenLinkSoftware/mcp-jdbc-server](https://github.com/OpenLinkSoftware/mcp-jdbc-server)
- **Category:** database-messaging-mcp-servers
- **Tags:** mcp, database, jdbc, java, integration

---

## Features

- **JDBC Connectivity**: Connects to any database supporting JDBC drivers.
- **Schema Management**:
  - Fetch and list all schema names from the connected database.
  - Retrieve table information for specific or all schemas.
  - Filter and retrieve tables based on name substrings.
- **Table Description**:
  - Generate detailed descriptions of table structures, including column names, data types, nullable attributes, primary keys, and foreign keys.
- **Query Execution**:
  - Execute SQL queries with results in multiple formats:
    - **JSONL** (JSON Lines) for structured responses.
    - **Markdown Table** for reporting and visualization.
- **Stored Procedure Execution** (Virtuoso-specific): Execute stored procedures and retrieve results.
- **SPASQL & SPARQL Support** (Virtuoso-specific):
  - Execute SPASQL (SQL/SPARQL hybrid) and SPARQL queries.
- **Virtuoso AI Support**: Interact with Virtuoso Support Assistant/Agent for LLM-related tasks.
- **Tools Provided for MCP Clients:**
  - `jdbc_get_schemas`: List accessible schemas.
  - `jdbc_get_tables`: List tables in a schema.
  - `jdbc_describe_table`: Detailed table column info.
  - `jdbc_filter_table_names`: Filter tables by name substring.
  - `jdbc_query_database`, `jdbc_execute_query`: Run SQL queries, get JSONL results.
  - `jdbc_execute_query_md`: SQL queries, results as Markdown tables.
  - `jdbc_spasql_query`: Run SPASQL queries (Virtuoso).
  - `jdbc_sparql_query`: Run SPARQL queries (Virtuoso).
  - `jdbc_virtuoso_support_ai`: Use Virtuoso-specific AI Assistant.
- **Requirements**: Java 21 or above.
- **Configuration**: Supports environment variables for JDBC URL, user, password, and API key. Can be integrated with Claude Desktop.
- **Troubleshooting**: Optional MCP Inspector tool available via npm for debugging server interactions.

## Pricing

- Open source, licensed under the MIT license. No pricing plans.

---

## Links
- [Repository & Documentation](https://github.com/OpenLinkSoftware/mcp-jdbc-server)