# Web Search MCP Server

**Category:** Data Access & Integration MCP Servers  
**Tags:** web-search, google, open-data, ai-integration

## Description
Web Search MCP Server is a Model Context Protocol (MCP) server that enables free web searches using Google search results, without requiring API keys or authentication. It provides a simple, accessible solution for retrieving online information and integrates easily with MCP-compatible clients.

## Features
- Free web search functionality using Google search results
- No API keys or authentication required
- Returns structured results with titles, URLs, and descriptions
- Configurable number of results per search (default: 5, max: 10)
- Provides a single tool (`search`) with parameters for query and result limit
- Example integration code provided for VSCode (Claude Dev Extension) and Claude Desktop
- Open source (repository available)

## Usage
- Accepts a search query and an optional result limit
- Returns an array of results with title, URL, and description fields

## Limitations
- Subject to Google rate limiting if too many searches are performed in a short time
- Accuracy depends on Google's HTML structure (may break if structure changes)
- Some results may lack descriptions or metadata
- Complex Google search operators may not function as expected
- Intended for personal use; users should respect Google's terms of service

## Installation
- Clone or download the repository: [GitHub Repository](https://github.com/pskill9/web-search)
- Install dependencies: `npm install`
- Build the server: `npm run build`
- Add the server to your MCP configuration (instructions provided for VSCode and Claude Desktop)

## Source & Documentation
- [Project Page](https://www.claudemcp.com/servers/web-search)
- [GitHub Repository](https://github.com/pskill9/web-search)

## Pricing
- The server is free and open source; no pricing plans are listed.