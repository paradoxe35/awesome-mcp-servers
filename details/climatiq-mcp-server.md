# climatiq-mcp-server

A Model Context Protocol (MCP) server for accessing the Climatiq API, enabling real-time carbon calculations and climate impact insights via MCP. It is intended for use by AI assistants and other applications needing programmatic access to carbon emission calculations.

**Source:** [https://github.com/jagan-shanmugam/climatiq-mcp-server](https://github.com/jagan-shanmugam/climatiq-mcp-server)

## Features
- MCP server integration with the Climatiq API for carbon emission calculations
- Enables AI assistants to perform real-time carbon calculations and generate climate impact insights
- **Tools Provided:**
  - `set-api-key`: Configure the Climatiq API key for authentication
  - `electricity-emission`: Calculate carbon emissions from electricity consumption
  - `travel-emission`: Calculate emissions from travel by car, plane, or train
  - `search-emission-factors`: Search for specific emission factors in the Climatiq database
  - `custom-emission-calculation`: Perform custom calculations using specified emission factors
  - `cloud-computing-emission`: Calculate emissions from cloud computing resource usage
  - `freight-emission`: Calculate emissions from freight transportation
  - `procurement-emission`: Calculate emissions from procurement spending
  - `hotel-emission`: Calculate emissions from hotel stays
  - `travel-spend`: Calculate emissions from travel expenses
- **Resources:**
  - Carbon calculation results are exposed as resources with a `climatiq://calculation/{id}` URI scheme, containing detailed emission factor and calculation result information
- **Prompts:**
  - `climate-impact-explanation`: Generates natural language explanations of climate impacts for specific emission calculations
- **Utilities and Examples:**
  - Jupyter notebook and Python scripts for direct API usage and testing
  - CLI tool for direct API access without MCP server complexity
  - LLM (Large Language Model) example client for demonstrating AI assistant integration
- **Key Features:**
  - Complete API wrapper with error handling and timeout management
  - Resource and result caching to preserve calculation history
  - Example prompts for generating natural language explanations
  - Demonstrates electricity emission, travel emission, and emission factor search capabilities
- **Calculation Methods Supported:**
  - Distance-based and spend-based methods for travel emissions
  - Advanced travel calculations using origin-destination pairs
  - Direct calculations using specific emission factors
- **Installation:**
  - Install from source using `uv` or via the command line
  - Requires a Climatiq API key (configurable via environment variable, config file, or runtime)
- **MIT License**

## Pricing
- No pricing information is provided. The project is open source under the MIT License.

## Category
- data-access-integration-mcp-servers

## Tags
- mcp
- climate
- real-time
- api-integration