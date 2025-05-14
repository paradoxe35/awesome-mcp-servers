# stefan-xyz/mcp-server-runescape

**Category:** Data Access Integration MCP Servers  
**Tags:** runescape, game-data, analytics, open-source

[GitHub Repository](https://github.com/stefan-xyz/mcp-server-runescape)

## Description
A Model Context Protocol (MCP) server that provides tools for interacting with RuneScape and Old School RuneScape (OSRS) data. It enables access to item prices, player hiscores, top rankings, player counts, and more, utilizing accurate data sources and supporting both RS and OSRS.

## Features
- **Item Details (`get_item_details`)**
  - Retrieve comprehensive information about tradeable items, including:
    - Current price in the Grand Exchange
    - Price trends (24h, 30, 90, and 180 days)
    - Name, category, description (examine text), image, members, ID
- **Item Price History (`get_item_price_history`)**
  - Access 180 days of price history for items, including daily prices and average prices by timestamp
- **Player Hiscore (`get_player_hiscore`)**
  - Fetch player rankings and experience for skills and activities:
    - Player rank, skill level, experience points, activity scores
- **Top Rankings (`get_top_rankings`)**
  - View the top (up to 50) players for a specific skill or activity:
    - Name, score, rank
- **Player Count (`get_player_count`)**
  - Real-time number of players online in RuneScape and OSRS
- **Account Totals (`get_rsuser_total`)**
  - Number of accounts created (including historical data and accounts across different platforms/versions)
- **API uses endpoints that support both RS and OSRS data for consistency**
- **Integration with MCP clients** (e.g., Claude desktop, Cursor)
- **Open-source with Apache-2.0 license**

## Example Use Cases
- Querying current or historical item prices and trends
- Fetching item details such as description, image, or ID
- Checking player hiscores and experience
- Retrieving top player rankings for specific skills or activities
- Monitoring real-time player counts
- Accessing total account creation statistics

## Getting Started
- Install via NPM or clone from source
- Integrate with compatible MCP clients (e.g., Claude desktop, Cursor)
- Node.js is required for running from source

## Pricing
- **Open Source:** Free to use under the Apache-2.0 license

## License
Apache-2.0