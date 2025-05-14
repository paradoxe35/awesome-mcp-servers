# hn

A Model Context Protocol (MCP) server offering search and fetch capabilities for Hacker News, demonstrating news data integration via MCP.

- **Category:** Data Access Integration MCP Servers
- **Tags:** hacker-news, news, data-access, mcp
- **Source:** [GitHub Repository](https://github.com/pskill9/hn-server)

## Features
- Fetch different types of Hacker News stories: **top**, **new**, **ask**, **show**, **jobs**
- Provides structured data for each story, including:
  - Title
  - URL
  - Points (upvotes)
  - Author
  - Timestamp
  - Number of comments
  - Rank (position in list)
- Configurable limit on number of stories returned (1-30, default 10)
- Clean error handling and validation for:
  - Invalid story types
  - Network failures
  - HTML parsing errors
  - Invalid parameter values
- Easy integration with Claude desktop app or VSCode Claude extension via MCP configuration
- Built with TypeScript, uses MCP SDK, Axios (HTTP), and Cheerio (HTML parsing)
- Open source under MIT License

## Usage
- Exposes a `get_stories` tool with parameters:
  - `type`: 'top', 'new', 'ask', 'show', 'jobs' (default: 'top')
  - `limit`: number of stories to fetch (1-30, default: 10)
- Returns an array of structured story objects
- Can be integrated into MCP-compatible environments for natural language querying

## Installation
- Clone the repository and install dependencies via npm
- Build the server with `npm run build`
- Configure in MCP settings for Claude or VSCode

## Pricing
- **Free and open source** (MIT License)

## License
- MIT License