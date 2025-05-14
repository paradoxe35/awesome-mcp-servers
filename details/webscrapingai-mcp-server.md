# WebScraping.ai MCP Server

A Model Context Protocol (MCP) server implementation that integrates with WebScraping.AI for advanced web data extraction and scraping capabilities.

**Source:** [GitHub Repository](https://github.com/webscraping-ai/webscraping-ai-mcp-server)

## Features
- **Question Answering:** Ask questions about web page content and receive answers based on page data.
- **Structured Data Extraction:** Extract structured data fields from web pages using natural language instructions.
- **HTML Retrieval:** Get full HTML content of web pages, including with JavaScript rendering.
- **Plain Text Extraction:** Extract visible text from web pages.
- **CSS Selector-Based Extraction:** Extract content using specific CSS selectors (single or multiple elements).
- **Multiple Proxy Types:** Supports datacenter and residential proxies, with country selection.
- **JavaScript Rendering:** Uses headless Chrome/Chromium for rendering JS-heavy pages.
- **Custom JavaScript Execution:** Run custom JS code on target pages during extraction.
- **Device Emulation:** Emulate desktop, mobile, or tablet devices during scraping.
- **Concurrent Request Management:** Manage concurrent requests with configurable rate limiting.
- **Account Usage Monitoring:** Retrieve information about your WebScraping.AI account usage and limits.
- **Integration with LLMs:** Implements MCP, making it compatible with MCP-enabled LLM platforms (e.g., Claude, Cursor).
- **Robust Error Handling:** Automatic retries, rate limit handling, detailed error messages, and network resilience.

### Available Tools
- **Question Tool:** Ask questions about web page content.
- **Fields Tool:** Extract structured fields from web pages.
- **HTML Tool:** Retrieve full HTML content with JS rendering.
- **Text Tool:** Extract visible text from a page.
- **Selected Tool:** Extract content from a specific CSS selector.
- **Selected Multiple Tool:** Extract content from multiple CSS selectors.
- **Account Tool:** Get account usage and quota info.

### Common Options (for all tools)
- `timeout`: Max page retrieval time (default 15000ms, max 30000ms)
- `js`: Enable/disable JavaScript rendering (default: true)
- `js_timeout`: Max JS rendering time (default: 2000ms)
- `wait_for`: CSS selector to wait for before scraping
- `proxy`: Proxy type (datacenter or residential, default: residential)
- `country`: Proxy country (default: US, supports multiple countries)
- `custom_proxy`: Supply your own proxy URL
- `device`: Device emulation type (desktop, mobile, tablet)
- `error_on_404`: Error on 404 status (default: false)
- `error_on_redirect`: Error on redirect (default: false)
- `js_script`: Custom JS code to execute

## Installation & Configuration
- Can be run with `npx`, or cloned and run manually with `npm`.
- Requires a WebScraping.AI API key.
- Configurable via environment variables for concurrency, proxy type, JS rendering, timeouts, etc.
- Integrates with LLM platforms (e.g., Cursor, Claude Desktop) via MCP configuration.

## Pricing
- **No pricing information is provided in the repository.**
  - Requires a WebScraping.AI API key (obtainable from [WebScraping.AI](https://webscraping.ai)).

## License
- MIT License

---
**Category:** Data Access Integration MCP Servers

**Tags:** scraping, data-extraction, web, mcp