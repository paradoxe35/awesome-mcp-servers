# keboola-mcp-server

**Category:** data-access-integration-mcp-servers  
**Tags:** mcp, data-access, integration, keboola  
**Source:** [GitHub Repository](https://github.com/keboola/keboola-mcp-server)

## Overview
Keboola MCP Server is an open-source middleware that connects Keboola projects with modern AI tools and MCP clients (such as Claude, Cursor, CrewAI, LangChain, Amazon Q, and others). It exposes Keboola features—like storage access, SQL transformations, and job triggers—as callable tools for AI agents and assistants, enabling seamless data access and integration without the need for additional glue code.

## Features
- **Integration with AI & MCP Clients:** Bridges Keboola with AI tools (Claude, Cursor, Windsurf, Zed, Replit, Codeium, Sourcegraph, and custom clients) via stdio or HTTP+SSE.
- **Storage Tools:**
  - List all storage buckets in a Keboola project
  - Retrieve detailed information about specific buckets
  - List all tables within a bucket
  - Get detailed information for a specific table
  - Update bucket and table descriptions
- **SQL Tools:**
  - Execute custom SQL queries on your data
  - Identify SQL dialect (Snowflake or BigQuery)
- **Component Tools:**
  - List all extractors, writers, and applications (components)
  - Retrieve detailed configuration for a component
  - List all transformation configurations
  - Create new SQL transformations with custom queries
- **Job Tools:**
  - List and filter jobs by status, component, or configuration
  - Retrieve comprehensive details about specific jobs
  - Trigger component or transformation jobs to run
- **Documentation Search:**
  - Perform natural language search over Keboola documentation
- **Multiple Deployment Options:**
  - Integrated mode (auto-started by clients like Claude or Cursor)
  - Local development mode
  - Manual CLI mode (for testing)
  - Docker deployment
- **Supports BigQuery and Snowflake backends** (requires appropriate environment variables)
- **Authentication/Authorization:** Uses Keboola Storage API tokens (custom or master) for fine-grained access control.
- **Region-aware API endpoints** for AWS, Google Cloud, and Azure deployments.

## Compatibility
- **Supported MCP Clients:**
  - Claude (Desktop & Web)
  - Cursor
  - Windsurf, Zed, Replit
  - Codeium, Sourcegraph
  - Custom clients via HTTP+SSE or stdio

## Requirements
- Keboola Storage API token (with desired level of access)
- Workspace schema (for SQL queries)
- For BigQuery, a Google application credentials file
- Knowledge of your Keboola project's region for correct API URL

## Pricing
- **Open Source**: No pricing plans; available for free under open-source license.
