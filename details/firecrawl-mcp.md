# Firecrawl MCP

**Category:** Data Access / Integration MCP Servers  
**Source:** [GitHub Repository](https://github.com/pashpashpash/mcp-server-firecrawl)

## Description
FireCrawl MCP Server is an open-source Model Context Protocol (MCP) server that integrates FireCrawl's advanced web scraping, crawling, and search capabilities for Large Language Models (LLMs) such as Claude. It supports both cloud and self-hosted deployments, enabling complex web research and data extraction tasks with robust customization and automation options.

## Features
- **Web Scraping with JavaScript Rendering:** Scrape dynamic web pages that require JS execution.
- **Batch Processing:** Efficiently handle multiple URLs with built-in rate limiting and parallel processing.
- **URL Discovery and Crawling:** Automatically discover and crawl URLs to specified depths, with options to restrict external links and deduplicate similar URLs.
- **Web Search Integration:** Perform web searches and extract content from search results.
- **Advanced Content Extraction:** Extract structured data from web pages using LLM prompts and custom schemas.
- **Automatic Retries:** Support for retrying failed requests with exponential backoff.
- **Comprehensive Logging:** Built-in logging system for monitoring and debugging.
- **Content Filtering:** Include or exclude specific HTML tags to focus on main content or omit navigation/footers.
- **Cloud and Self-Hosted Support:** Use the official cloud API or your own FireCrawl instance.
- **Viewport Emulation:** Choose between mobile and desktop viewport rendering.
- **Credit Usage Monitoring:** Set warning and critical thresholds for API credit usage.
- **Configurable via Environment Variables:** Adjust retry logic, endpoints, credit thresholds, and more.

### Available Tools
- **Scrape Tool:** Scrape a single URL with custom options (formats, tags, timeouts, viewports).
- **Batch Scrape Tool:** Scrape multiple URLs in parallel with efficiency.
- **Search Tool:** Search the web and scrape/extract content from results.
- **Crawl Tool:** Perform asynchronous site crawls with depth and link controls.
- **Extract Tool:** Use LLMs to extract structured data from web pages based on custom prompts and schemas.

## Installation & Usage
- Clone the repository and install dependencies using `npm install`.
- Build the project with `npm run build`.
- Configure environment variables for cloud or self-hosted API usage.
- Integrate with Claude Desktop or other LLM platforms via MCP interface.

## Pricing
No pricing information is available; the project is open-source under the MIT license.

## License
MIT License

---
**Tags:** mcp, web-crawling, data-extraction, llm