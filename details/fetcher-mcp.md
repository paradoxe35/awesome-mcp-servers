# Fetcher MCP

Fetcher MCP is an MCP server for fetching and extracting web page content using Playwright's headless browser capabilities. It is designed to extract clean, readable content from JavaScript-heavy or dynamic websites and output it in HTML or Markdown format.

## Features

- **JavaScript Rendering:** Uses Playwright to execute JavaScript, enabling scraping of modern, dynamic web applications.
- **Intelligent Content Extraction:** Built-in Readability algorithm automatically extracts the main content, removing ads, navigation, and other non-essential elements.
- **Flexible Output Formats:** Supports both HTML and Markdown output formats.
- **Parallel Processing:** The `fetch_urls` tool allows concurrent fetching of multiple URLs for efficient batch operations.
- **Resource Optimization:** Automatically blocks unnecessary resources (images, stylesheets, fonts, media) to reduce bandwidth usage and improve performance.
- **Robust Error Handling:** Comprehensive error handling and logging for reliable operation.
- **Configurable Parameters:** Fine-grained control over timeouts, content extraction, and output formatting. Key parameters include:
  - `url` or `urls`: URL(s) to fetch
  - `timeout`: Page loading timeout (default 30s)
  - `waitUntil`: Navigation completion trigger (options: 'load', 'domcontentloaded', etc.)
  - `extractContent`: Whether to extract main content (default true)
  - `maxLength`: Maximum length of returned content
  - `returnHtml`: Return HTML instead of Markdown (default false)
  - `waitForNavigation`: Wait for additional navigation (for anti-bot, CAPTCHAs)
  - `navigationTimeout`: Additional navigation timeout (default 10s)
  - `disableMedia`: Disable loading of media resources (default true)
  - `debug`: Enable debug mode to show browser window
- **Batch Operations:** `fetch_urls` supports parallel fetching of multiple URLs with combined results.
- **Debug Mode:** Option to run with browser window visible for debugging or manual authentication.
- **Custom Authentication:** Supports manual login via debug mode, allowing scraping of authenticated pages.
- **Development Tools:** Includes scripts for installing dependencies, browsers, building the server, and debugging.

## Usage
- Run directly with `npx -y fetcher-mcp`.
- Debug mode available with `--debug` flag.
- Can be configured as an MCP server for integration with other tools (e.g., Claude Desktop).

## Licensing
- Licensed under the MIT License.

## Source
- [GitHub Repository](https://github.com/jae-jae/fetcher-mcp)

## Pricing
- Fetcher MCP is open source and available for free under the MIT License.