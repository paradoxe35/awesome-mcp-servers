# mcp-webresearch

**Description:**  
mcp-webresearch is an open-source MCP (Model Context Protocol) server designed for conducting web research and integrating real-time information—such as Google search results and webpage content—into the Claude desktop app.

**Source:** [https://github.com/mzxrai/mcp-webresearch](https://github.com/mzxrai/mcp-webresearch)

**Category:** data-access-integration-mcp-servers

**Tags:** mcp, google, web-search, research

---

## Features
- **Google Search Integration:** Perform Google searches and extract results programmatically.
- **Webpage Content Extraction:** Retrieve and extract content from visited web pages.
- **Research Session Tracking:** Maintains a session log recording search queries, visited pages, extracted content, screenshots, and timestamps.
- **Screenshot Capture:** Take and save screenshots of visited web pages as MCP resources.
- **Agentic-Research Prompt:** A guided prompt for Claude that assists in conducting thorough, iterative, and source-cited research.
- **Resource Management:** Exposes screenshots and research sessions as MCP resources for easy access within Claude Desktop.
- **Interactive Research:** Allows users to guide and refine research direction interactively, with Claude citing sources.
- **Tools:**
  - `search_google`: Performs Google search and extracts results.
  - `visit_page`: Visits a webpage and extracts content (optionally takes a screenshot).
  - `take_screenshot`: Captures a screenshot of the current page.
- **Platform Support:** Verified on macOS and Linux.
- **Pre-alpha Status:** Early-stage software; bugs may be present.
- **Open Source:** Licensed under MIT.

## Requirements
- Node.js >= 18
- Claude Desktop app
- Playwright (installed as a dependency)

## Pricing
- **Open Source** (MIT License)
- No pricing plans; free to use and modify.

---

**Note:** The repository is currently archived and in pre-alpha state. Users may encounter bugs and are encouraged to check logs for troubleshooting.