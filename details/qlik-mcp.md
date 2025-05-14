# qlik-mcp

MCP Server for Qlik Cloud API, enabling authenticated querying of Qlik applications, sheets, and extraction of data from visualizations, with robust rate limiting.

**Source:** [https://github.com/jwaxman19/qlik-mcp](https://github.com/jwaxman19/qlik-mcp)

**Category:** data-access-integration-mcp-servers

**Tags:** mcp, qlik, data-visualization, cloud, api-integration

---

## Features
- **Qlik Cloud API Integration:** Enables interaction with Qlik applications and extraction of data from visualizations.
- **Authentication:** Uses Qlik Cloud API keys for secure access.
- **Robust Rate Limiting:** Configurable settings to avoid API overuse and handle rate limits.
- **Tools/Endpoints:**
  - `qlik_get_apps`: List all Qlik applications in the workspace (supports pagination and limit).
  - `qlik_get_app_sheets`: Retrieve all sheets in a Qlik application.
  - `qlik_get_sheet_charts`: List all charts in a specific sheet (with chart metadata).
  - `qlik_get_chart_data`: Fetch data from a specific chart, including headers, rows, metadata, and pagination.
- **Environment Configuration:**
  - Supports environment variables for API key, tenant URL, default app ID, rate limits, and retry settings.
- **Deployment Options:**
  - Native Deno support (recommended).
  - Node.js support for IDE integration.
  - Docker support for containerized deployment.
- **Integration Support:**
  - Can be used with Claude Desktop and Cursor via configuration.
- **Troubleshooting Guidance:**
  - Detailed error handling and common issue resolution (API permissions, rate limits, etc).
- **MIT Licensed:** Free to use, modify, and distribute under the MIT License.

## Setup & Usage
- **API Key Setup:** Requires Qlik Cloud API key with appropriate permissions.
- **.env File:** Environment variables needed for API connection and rate limiting.
- **Docker:** Provided Dockerfile and .env.example for easy deployment.
- **Local Development:** Deno and Node.js supported; install dependencies for IDE support if needed.

## Pricing
- **Open Source / MIT License:** No cost; free to use and deploy.

---