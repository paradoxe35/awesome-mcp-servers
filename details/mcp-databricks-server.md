# mcp-databricks-server

A Model Context Protocol (MCP) server that connects to the Databricks API, enabling large language models (LLMs) to interact with Databricks environments for data access and job management.

## Features
- Run SQL queries on Databricks SQL warehouses
- List all Databricks jobs in your workspace
- Get status of specific Databricks jobs by job ID
- Retrieve detailed information about specific Databricks jobs
- Provides MCP tools for integration with LLMs:
  - `run_sql_query(sql: str)` – Execute SQL queries
  - `list_jobs()` – List jobs
  - `get_job_status(job_id: int)` – Get status of a job
  - `get_job_details(job_id: int)` – Get job details

## Prerequisites
- Python 3.7+
- Access to a Databricks workspace with:
  - Personal access token
  - SQL warehouse endpoint
  - Appropriate permissions to run queries and access jobs

## Setup & Usage
- Clone the repository
- Set up a Python virtual environment and install dependencies
- Configure `.env` file with Databricks credentials
- Run the server using `python main.py`
- Test connection with `python test_connection.py`

## Security Considerations
- Secure your Databricks personal access token
- Protect your `.env` file and avoid committing secrets to version control

## Source
[https://github.com/JordiNeil/mcp-databricks-server](https://github.com/JordiNeil/mcp-databricks-server)

## Category
Data Access & Integration MCP Servers

## Tags
mcp, databricks, data-access, sql, llm

## Pricing
No pricing information is provided; this appears to be an open-source project.