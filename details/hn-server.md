# hn-server

A Model Context Protocol (MCP) server that fetches and parses stories from Hacker News, providing structured data for news aggregation and trend analysis.

## Features
- Fetches different types of Hacker News stories: `top`, `new`, `ask`, `show`, and `jobs`.
- Provides structured data for each story, including:
  - Title
  - URL (may be internal HN URL for text posts)
  - Points (upvotes)
  - Author
  - Timestamp
  - Comment count
  - Rank (position in the list)
- Configurable limit on the number of stories returned (1-30, default 10).
- Exposes a `get_stories` tool for querying stories by type and limit.
- Clean error handling and validation for:
  - Invalid story types
  - Network failures
  - HTML parsing errors
  - Invalid parameter values
- Sample integration with Claude desktop app or VSCode Claude extension via MCP configuration.
- Built with TypeScript, MCP SDK, Axios (HTTP), and Cheerio (HTML parsing).
- Open source under the MIT License.

## Installation
- Clone the repository: `git clone https://github.com/pskill9/hn-server`
- Install dependencies: `npm install`
- Build the server: `npm run build`
- Configure as an MCP server in your Claude app or VSCode extension settings.

## Usage
- Use the `get_stories` tool with parameters:
  - `type`: 'top', 'new', 'ask', 'show', or 'jobs' (default: 'top')
  - `limit`: number of stories to return (1-30, default: 10)
- Returns an array of story objects with the fields listed above.

## Development
- Modify `src/index.ts` as needed
- Rebuild with `npm run build`

## License
MIT License

## Source
[https://github.com/pskill9/hn-server](https://github.com/pskill9/hn-server)

## Pricing
- Open source, free to use under the MIT License.
