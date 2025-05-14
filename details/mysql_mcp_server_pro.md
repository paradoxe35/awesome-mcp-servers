# mysql_mcp_server_pro

**Category:** Database Messaging MCP Servers  
**Tags:** mcp, mysql, database, developer-tools

[Source Code on GitHub](https://github.com/wenb1n-dev/mysql_mcp_server_pro)

## Description
mysql_mcp_server_pro is an advanced MySQL MCP server that supports SSE and STDIO communication modes. It provides not only standard MySQL CRUD operations but also features comprehensive database anomaly analysis and is designed for extensibility, allowing developers to add custom tools.

## Features
- **SSE and STDIO Support:** Compatible with Server-Sent Events and standard input/output modes for integration with various clients.
- **CRUD Operations:** Full support for MySQL operations: SELECT, SHOW, DESCRIBE, EXPLAIN, INSERT, UPDATE, DELETE, CREATE, ALTER, DROP, TRUNCATE.
- **Role-based Permissions:** Operations can be restricted based on configurable permissions.
- **Database Anomaly Analysis:** Tools and prompts for analyzing MySQL health status, locks, index usage, and other anomalies.
- **Extensible Developer Tools:** Easily create and integrate custom tools by inheriting from a base handler class.
- **Built-in Toolset:**
  - **execute_sql:** Run a wide range of SQL commands with permission checks.
  - **get_chinese_initials:** Convert Chinese field names to pinyin initials.
  - **get_db_health_running:** Analyze the MySQL server's health, including connections, transactions, running status, and lock detection.
  - **get_table_desc:** Search and describe table structures, supporting multi-table queries.
  - **get_table_index:** Retrieve index information for tables, supporting multi-table queries.
  - **get_table_lock:** Check for row-level and table-level locks.
  - **get_table_name:** Search for table names based on comments and descriptions.
  - **get_db_health_index_usage:** Analyze index usage, including redundant/unused/poorly performing indexes and slow queries.
- **Prompt System:**
  - **analyzing-mysql-prompt:** For MySQL issue analysis.
  - **query-table-data-prompt:** Assists in querying table data.
- **Custom Tool Extension:** Developers can add new tools by extending the base handler and updating the server's initialization.

## Pricing
No pricing information is provided; appears to be an open-source project.

---