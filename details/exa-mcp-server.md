# exa-mcp-server

**Description:**
Model Context Protocol (MCP) server that connects to Exa AI Search API, enabling real-time web search access for AI models within the MCP framework.

**Source:** [GitHub - exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server)

**Category:** data-access-integration-mcp-servers

**Tags:** mcp, web-search, ai-integration, real-time, api-integration

---

## Features
- **Real-time Web Search:** Enables AI assistants (such as Claude Desktop) to perform web searches using the Exa AI Search API, providing up-to-date information.
- **Structured Search Results:** Returns search results with titles, URLs, and content snippets for easy consumption by AI models.
- **Caching:** Caches recent searches for quick reference and efficiency.
- **Rate Limiting & Error Handling:** Gracefully manages API rate limits and error cases.
- **Real-time Crawling:** Supports live web crawling to fetch the latest content.
- **Multiple Search Tools:**
    - `web_search`: General-purpose real-time web search with optimized results and content extraction.
    - `research_paper_search`: Focused search for academic papers and research content.
    - `twitter_search`: Searches Twitter/X.com for tweets, profiles, and conversations.
    - `company_research`: Crawls and gathers detailed information from company websites.
    - `crawling`: Extracts content from specific URLs, including articles, PDFs, and web pages.
    - `competitor_finder`: Identifies competitors for a given company by searching for similar businesses.
- **Tool Selection:** Users can enable or disable specific search tools in the server configuration.
- **Integration with Claude Desktop:** Easily integrates with Claude Desktop via configuration and supports developer mode options.
- **Direct CLI Usage:** Can be run directly via `npx` or as a globally installed npm package.
- **Testing Support:** Compatible with MCP Inspector for interactive testing and debugging.
- **Open Source:** Licensed under the MIT license.

## Installation & Configuration
- **Prerequisites:** Node.js (v18+), Claude Desktop, Exa API key, Git.
- **Install via npm:** `npm install -g exa-mcp-server`
- **Install via Smithery:** `npx -y @smithery/cli install exa --client claude`
- **Manual installation:** Clone repo, install dependencies, build, and link globally.
- **Configuration:** Edit `claude_desktop_config.json` to add Exa MCP server and specify API key and enabled tools.

## Usage
- Once configured, allows Claude Desktop to perform real-time web searches, research paper lookups, Twitter searches, company research, content extraction from URLs, and competitor analysis.
- Results are formatted and returned to the AI assistant, with caching for efficiency.

## Pricing
No pricing information is provided in the available content (the software is open source and available under the MIT license).

---

**License:** MIT