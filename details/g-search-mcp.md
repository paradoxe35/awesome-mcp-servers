# g-search-mcp

A powerful MCP server for Google search that enables parallel searching with multiple keywords simultaneously.

- **Source:** [https://github.com/jae-jae/g-search-mcp](https://github.com/jae-jae/g-search-mcp)
- **Category:** data-access-integration-mcp-servers
- **Tags:** mcp, google, web-search, search, data-access

## Features

- **Parallel Searching:** Supports searching with multiple keywords on Google at the same time, improving efficiency.
- **Browser Optimization:** Opens multiple tabs in a single browser instance for efficient parallel searches.
- **Automatic CAPTCHA Handling:** Detects Google CAPTCHAs and switches to a visible browser mode for user verification if needed.
- **User Behavior Simulation:** Simulates real user browsing patterns to reduce the chance of being detected as a bot by Google.
- **Structured Results:** Returns search results in structured JSON format for easy processing and analysis.
- **Configurable Parameters:**
    - `queries`: Array of search queries (required)
    - `limit`: Number of results per query (default: 10, configurable)
    - `timeout`: Page load timeout in milliseconds (default: 60000, configurable)
    - `noSaveState`: Whether to avoid saving browser state (default: false)
    - `locale`: Locale setting for search results (default: en-US, configurable)
    - `debug`: Enable debug mode to show browser window (overrides command line flag)
- **Uses Playwright:** Utilizes Playwright browser automation for performing searches.
- **Installation and Usage:**
    - Can be run directly with `npx -y g-search-mcp`
    - Requires Node.js 18+ and Playwright browser installed
    - Supports development workflows with auto-rebuild and debugging tools
- **Integration:** Can be configured as an MCP server in tools like Claude Desktop.

## Example Usage
- Search for multiple keywords (e.g., "machine learning", "artificial intelligence") and receive structured results for each.
- Adjust search result limits, timeouts, and locale as needed.
- Enable debug mode for troubleshooting or CAPTCHA resolution.

## Installation
- Requires Node.js 18+
- Install dependencies and Playwright browser as described in the README
- Build and run the server or use with `npx`

## License
MIT License

## Pricing
No pricing information available. The project is open-source under the MIT License.