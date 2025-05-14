# RSS Aggregator MCP

[Source Code](https://github.com/imprvhub/mcp-rss-aggregator)

## Category
Data Access Integration MCP Servers

## Description
RSS Aggregator MCP is a Model Context Protocol (MCP) server that allows Claude Desktop and other LLMs to fetch, process, and analyze content from RSS feeds for real-time information aggregation and trend analysis.

## Features
- **RSS Feed Aggregation:** Fetches and reads content from multiple RSS feeds within Claude Desktop.
- **Feed Configuration:** Supports both OPML (recommended) and JSON formats for managing feed subscriptions. Users can export/import feeds from common RSS readers using OPML.
- **Customizable Sources:** Easily add or modify feed sources via configuration files.
- **Auto-Start Integration:** Can be auto-started by Claude Desktop as needed or run manually.
- **Command-Line Tool:** Provides a `rss` tool with several commands:
  - `latest`: Show latest articles from all feeds (with optional limit)
  - `top` or `best`: Show top articles from all feeds (with optional limit)
  - `list`: List all available feeds
  - `--[feed-id]`: Show articles from a specific feed (with optional limit)
  - `[category]`: Show articles from a specific category (with optional limit)
  - `set-feeds-path --[path]`: Set the path to OPML/JSON feed file
- **Natural Language Queries:** Supports natural language interaction with Claude for fetching and analyzing feed content.
- **Category and Source Filtering:** Focus on specific content categories or sources.
- **Multiple Request Handling:** Combine multiple sequential requests for more comprehensive workflows.
- **Trend Analysis and Summarization:** Allows Claude to summarize articles, identify key trends, and compare coverage across sources.
- **Demo and Example Usage:** Includes sample OPML files and walkthroughs for setup and usage.
- **Multi-Language Feed Support:** Supports feeds in various languages (e.g., Spanish).
- **Open Source:** Licensed under the Mozilla Public License 2.0.

## Pricing
No pricing information is provided. The project is open source.

## Tags
rss, real-time, data-extraction, trend-analysis