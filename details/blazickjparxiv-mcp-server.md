# blazickjp/arxiv-mcp-server

**Source:** [GitHub Repository](https://github.com/blazickjp/arxiv-mcp-server)

**Category:** API Integration / MCP Servers

**Tags:** mcp, arxiv, research, search

## Description

The ArXiv MCP Server is a Model Context Protocol (MCP) server that enables AI assistants and other clients to search, download, and analyze research papers from the arXiv repository via a programmatic interface. It acts as a bridge between the MCP ecosystem and arXiv, facilitating academic paper discovery and analysis workflows.

## Features

- **Paper Search:** Query arXiv papers with filters for date ranges and categories.
- **Paper Access:** Download and read paper content by arXiv ID.
- **Paper Listing:** View a list of all papers downloaded to local storage.
- **Local Storage:** Downloaded papers are saved locally for faster access and offline analysis.
- **MCP Integration:** Easily integrate with MCP clients using provided configuration examples.
- **Research Prompts:** Includes a set of prompts for systematic academic paper analysis, covering:
  - Executive summary
  - Research context
  - Methodology analysis
  - Results evaluation
  - Practical and theoretical implications
  - Future research directions
  - Broader impacts
- **Configurable Storage:** Storage path for papers can be set via environment variable (`ARXIV_STORAGE_PATH`).
- **Testing Suite:** Includes tests runnable via `pytest`.
- **Docker Support:** Dockerfile provided for containerized deployment.
- **Open Source:** Released under the Apache-2.0 license.

## Tools Provided

1. **search_papers**: Search arXiv with query, date, category, and result limits.
2. **download_paper**: Download a paper by arXiv ID.
3. **list_papers**: List all papers currently in local storage.
4. **read_paper**: Access the content of a downloaded paper.
5. **deep-paper-analysis (Prompt)**: Automated workflow for in-depth academic paper analysis.

## Installation

- Install via Smithery or manually with `uv`.
- Configuration can be added to MCP client files for seamless integration.
- Development setup instructions provided for cloning and testing the repository.

## Pricing

- The ArXiv MCP Server is open source and free to use under the Apache-2.0 license.

## License

- Apache-2.0

---

**Note:** No commercial pricing or paid plans are mentioned; the project is open source.