# crypto-whitepapers-mcp

**Source:** [crypto-whitepapers-mcp on GitHub](https://github.com/kukapay/crypto-whitepapers-mcp)

**Category:** blockchain-crypto-mcp-servers

**Tags:** mcp, crypto, knowledge-base, documentation

---

## Description

crypto-whitepapers-mcp is an MCP server designed to act as a structured knowledge base of cryptocurrency whitepapers, enabling AI agents to access, analyze, and learn from a curated collection of crypto project documents.

---

## Features

- **Search Whitepapers:** Utilizes DuckDuckGo to find whitepaper PDFs for various cryptocurrency projects.
- **Load Whitepapers:** Downloads and indexes whitepaper PDFs into the knowledge base for future querying.
- **Query Knowledge Base:** Allows querying of whitepaper content, with the option to filter results by specific project.
- **List Projects:** Displays all crypto projects available in the knowledge base.
- **Claude Desktop Integration:** Enables access to MCP tools and prompts within Claude Desktop.
- **Tools (API Methods):**
    - `list_available_projects()`: Lists all projects in the knowledge base.
    - `search_whitepaper(project_name: str)`: Searches for a project's whitepaper PDF using DuckDuckGo.
    - `load_whitepaper(project_name: str, url: str)`: Downloads and loads a whitepaper PDF into the knowledge base.
    - `ask_whitepapers(query: str, project_name: str = None)`: Searches the knowledge base for a query, optionally filtered by project.
- **Prompts:**
    - `analyze_tokenomics(project_name: str)`: Analyzes tokenomics (distribution, supply, incentives) in a project's whitepaper.
- **Python-based:** Requires Python 3.10+ and uses `uv` for dependency management and running.
- **Open Source:** Licensed under the MIT License.

---

## Prerequisites

- Python 3.10+
- `uv` for dependency management and running
- Internet access
- (Optional) Claude Desktop for MCP integration

---

## Pricing

No pricing information is provided. The project is open source and licensed under the MIT license.

---

## License

MIT License