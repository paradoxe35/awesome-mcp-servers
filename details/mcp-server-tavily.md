# mcp-server-tavily

**MCP server for accessing Tavily AI search API, offering advanced search within the MCP framework.**

- **Source:** [GitHub - Tomatio13/mcp-server-tavily](https://github.com/Tomatio13/mcp-server-tavily)
- **Category:** data-access-integration-mcp-servers
- **Tags:** mcp, search, ai-integration, api-integration, data-access

---

## Features

- **Tavily API Integration:** Uses the Tavily API to perform web searches based on user queries.
- **AI-powered Search Results:** Returns results with AI-generated answers, search result URIs, and titles.
- **Search Tool:** Implements a `search` tool:
  - **Required argument:** `query` (search query)
  - **Optional argument:** `search_depth` (choose between `basic` or `advanced`)
- **Multi-platform Support:**
  - Can be integrated with Claude Desktop (Windows/MacOS)
  - Can be run locally via Docker Compose (Linux/other OS)
  - Supports execution via custom shell scripts (e.g., for Cursor's MCP Server)
- **Log Management:** Stores logs in a specified directory depending on the OS (e.g., for Claude Desktop on Windows)
- **Open Source:** Licensed under MIT.
- **Docker Support:** Includes Dockerfile and docker-compose configuration for containerized setup.
- **Smithery Install:** Can be installed and managed via Smithery CLI for Claude Desktop.
- **Usage Examples:** Detailed usage steps and configuration examples for different environments (Claude Desktop, Cursor, Docker Compose).

---

## Installation & Setup

- **Via Smithery:**
  - `npx -y @smithery/cli install tavily-search --client claude`
- **Manual Download:**
  - `git clone https://github.com/Tomatio13/mcp-server-tavily.git`
- **Docker Compose:**
  - `docker compose up -d`
  - Run the client: `docker exec mcp_server uv --directory /usr/src/app/mcp-server-tavily/src run client.py`
- **Configuration:**
  - Set `TAVILY_API_KEY` environment variable
  - Update relevant configuration files for Claude Desktop or Cursor

---

## Pricing

- **No pricing information provided.**
- **Open Source:** Project is MIT licensed (free to use, but Tavily API may have its own costs).

---

## License

- MIT License
