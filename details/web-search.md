# web-search

[Source Code & Documentation](https://github.com/pskill9/web-search)

## Description
web-search is an open-source Model Context Protocol (MCP) server that enables free web searching by scraping Google search results, without requiring API keys or authentication.

## Features
- Provides web search functionality using Google search results
- No API keys or authentication required
- Returns structured search results containing titles, URLs, and descriptions
- Configurable number of results per search (default: 5, max: 10)
- Simple integration into MCP-compatible environments, such as VSCode (Claude Dev Extension) or Claude Desktop
- Offers a single tool named `search` with parameters for query and optional result limit

## Usage
- Accepts a search query and an optional limit on the number of results
- Returns a list of objects with `title`, `url`, and `description`

## Limitations
- **Rate Limiting:** Excessive searching may trigger blocks from Google; users should limit frequency and consider delays between searches
- **Result Accuracy:** Relies on Google's HTML structure which may change; some results may lack descriptions or metadata; complex search operators may not always work
- **Legal Considerations:** Intended for personal use; users should comply with Google's terms of service and implement appropriate rate limiting

## Pricing
- Free and open-source (no cost to use)

## Tags
mcp, web-search, google, open-source

## Category
Data Access Integration MCP Servers