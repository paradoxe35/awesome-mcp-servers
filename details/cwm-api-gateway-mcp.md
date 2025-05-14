# Cwm Api Gateway Mcp

**Category:** Business & Commerce / MCP Servers  
**Source:** [GitHub Repository](https://github.com/jasondsmith72/cwm-api-gateway-mcp)

## Overview
Cwm Api Gateway Mcp is a Model Context Protocol (MCP) server that facilitates integration between Claude and the ConnectWise Manage API. It provides an interface for natural language search, API discovery, execution, and workflow memory features to streamline IT service management.

## Features
### API Discovery Tools
- **search_api_endpoints:** Search for API endpoints by query string.
- **natural_language_api_search:** Find endpoints using natural language descriptions.
- **list_api_categories:** List all available API categories.
- **get_category_endpoints:** List all endpoints in a specific category.
- **get_api_endpoint_details:** Get detailed information about a specific endpoint.

### API Execution Tools
- **execute_api_call:** Execute an API call with specified path, method, parameters, and data.
- **send_raw_api_request:** Send a raw API request in the format "METHOD /path [JSON body]".

### Fast Memory Tools
- **save_to_fast_memory:** Manually save an API query for later use.
- **list_fast_memory:** List all queries saved in Fast Memory.
- **delete_from_fast_memory:** Delete a specific query from Fast Memory.
- **clear_fast_memory:** Clear all queries in Fast Memory.

### Integration & Configuration
- NPM package installation and manual installation methods supported (Windows, macOS, Linux).
- Works with Claude Desktop via configuration or direct script execution.
- Uses environment variables for ConnectWise API authentication (API URL, company ID, public/private keys, auth prefix).

### Fast Memory System
- Powered by a SQLite database to store and manage frequently used API queries.
- Optimizes workflow by enabling quick retrieval and reuse of saved queries.

### Advanced Usage & Troubleshooting
- Supports advanced API query optimization: specific conditions, limited field selection, pagination.
- Provides database management, diagnostics, and logging tools.
- Guidance for resolving common issues such as missing databases or authentication errors.

## Pricing
No pricing information is provided. The software is proprietary and confidential; unauthorized use is prohibited.

## Tags
`mcp` `api-integration` `business` `memory`