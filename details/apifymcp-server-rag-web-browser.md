# apify/mcp-server-rag-web-browser

**Source:** [GitHub Repository](https://github.com/apify/mcp-server-rag-web-browser)

## Description

`apify/mcp-server-rag-web-browser` is an open-source MCP (Model Context Protocol) server designed for Apify's RAG Web Browser Actor. It enables integration with AI assistants and LLM (Large Language Model) pipelines to perform automated web search, scrape content from URLs, and return cleaned content in Markdown format within the MCP protocol.

## Features

- **Web Search via MCP:** Allows AI assistants (such as Claude Desktop) to perform web searches programmatically, scrape the top N results, and retrieve their cleaned content as Markdown.
- **Fetch & Scrape URLs:** Supports fetching a single URL and returning its cleaned content as Markdown.
- **Search Tool:**
  - `search` tool queries Google Search, scrapes the top N URLs from results, and returns cleaned content in Markdown.
  - Arguments:
    - `query` (string, required): Search term or URL.
    - `max_results` (number, optional): Maximum number of search results to scrape (default: 1).
- **Prompt Integration:**
  - Prompts can trigger search actions and return crawled web pages as text or Markdown.
- **MCP Protocol:** Implements the Model Context Protocol for secure, controlled interaction with AI agents and external data sources.
- **SSE (Server-Sent Events) Support:** Can stream responses back to clients using SSE, allowing for real-time updates.
- **Local Development & Testing:**
  - Example clients for stdio and chat interfaces.
  - SSE transport example for streaming.
  - Debugging support with MCP Inspector.
- **Cross-platform:** Works on MacOS and Windows.
- **Open Source:** Licensed under Apache-2.0.

## Configuration & Requirements

- Prerequisites:
  - MacOS or Windows
  - Node.js v18 or higher
  - Apify API Token (`APIFY_API_TOKEN`)
  - Claude Desktop or another MCP client
- Setup involves cloning the repository, installing dependencies, building the project, and configuring the MCP client (e.g., Claude Desktop) to connect to the server.

## Pricing

No pricing information is provided; this is an open-source project under the Apache-2.0 license.

## Tags

mcp, web, scraping, rag, automation

## Category

code-execution-automation-mcp-servers